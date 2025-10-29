# Clustering Countires by Ease of Construction Permits
### Unsupervised Machine Learning - K-Means Clustering
------------------------------------------------------
## Overview
This project applies **K_means Clustering** to group contries based  on their performnace in obtaining construction permits across multiple years.The goal is to identify common patterns among high-performing, medium-performing, and low-performing regions globally.

The data includes country scores for:
- FY2017 — Dealing with construction permits
- FY2018 — Dealing with construction permits
- FY2019 — Dealing with construction permits
  These values represent how easy it is to get a construction permit in each country.
  -----------------------------------------------------
  ## Dataset Description

- Column1: 'country'
- Column2: 'fy2017'
- Column3: 'fy2019'
- Column4: 'fy2019'

-Total Countries: 191
 ------------------------------------------------------
 ## Machine Learning Model - K-Means Clustering
 We used **Elbow Method** to determin optiomal number of clusters and **Silhourette Score* to validate cluster performance with steps involved with **Data Preprocessing**, **Feature Scaling**, **Applying k-means for different values of K, **Evaluation WCSS**, **Selecting best K and analyzing clusters
 ------------------------------------------------------
 # Evaluation
 Evaluated by WCSS (Elbow Method) and Silhouette Score
 ------------------------------------------------------
 ## Technologies Used
 -Language: Python
 -Libraries: pandas, scikit-learn, matplotlib, numpy, seaborn
 - Model: K-Means Clustering
 
 
