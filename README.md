# Cluster Analysis of the India Consumer Market  
*A focus on durable goods using household survey data (2014–2015)*  

## Overview  
This project analyses household expenditure in India with a focus on **durable goods** such as gold ornaments, motorcycles, mobile phones, and laptops. Using the 2014–2015 Indian Household Consumer Expenditure Survey, the study explores how socio-economic and cultural factors influence spending behaviour across rural and urban households.  

The aim was to segment households into clusters that reflect different expenditure priorities, providing insights for businesses and market analysts on how to target products effectively.  

---

## Methods  
- **Data Source:** India Household Consumer Expenditure Survey (2014–2015), covering 83,600+ households nationwide.  
- **Variables:**  
  - Spending: MPCE (monthly per capita expenditure), gold ornaments, motorcycles, mobile phones, laptops, toys  
  - Demographics: household size, rural/urban status, religion (Hindu)  
- **Techniques Used:**  
  - Exploratory data analysis (means, boxplots, distributions)  
  - Feature engineering (MPCE quartiles)  
  - **K-Means clustering** on spending + demographic variables  
  - Cluster evaluation using **silhouette scores**  

**Tools & Libraries:** R (`dplyr`, `ggplot2`, `factoextra`, `cluster`)  

---

## Key Findings  
- **Motorcycles** dominate household expenditure across income groups, especially in rural areas (necessity due to limited infrastructure).  
- **Gold ornaments** are consistently high across clusters, reflecting their **cultural and ceremonial importance** (especially weddings).  
- **Cluster insights:**  
  - *Cluster 1*: Urban, middle–high income, high gold spending → ideal for luxury jewellery marketing.  
  - *Cluster 2*: Rural, large households, very high motorcycle spending → premium motorcycle brands should target this group.  
  - *Cluster 3*: Lower spending on gold and motorcycles, but steady mobile phone purchases → suited for budget-friendly phone markets.  
- Cluster 2 showed the highest silhouette score (0.66), indicating strong separation and reliability for targeted strategies.  

---

## Limitations  
- Lack of gender and age variables limited deeper segmentation.  
- Household survey data may underrepresent individual-level purchasing patterns.  
- Overlap between clusters suggests further re-clustering or additional features may improve interpretability.  

---

## Practical Implications  
- Market research analysts and businesses can use these insights for **customer segmentation**, tailoring promotions around cultural events (e.g., weddings, Diwali), rural mobility needs, and budget-conscious consumer segments.  
- Highlights the importance of **combining socio-economic and cultural data** for more effective product targeting in emerging markets.  

---

## Repository Contents  
- `report.pdf` – Full research paper  
- `analysis.R` – R code for clustering, plots, and evaluation  
- `figures/` – Key visuals (boxplots, k-means clusters, centroid tables)  

---

## Author  
Joseph Barker – University of Manchester, Data Analytics & Criminology (2025)  
