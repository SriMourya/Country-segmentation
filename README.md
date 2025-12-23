# NGO Country Clustering Case Study

This project applies unsupervised machine learning techniques to segment countries
based on socio-economic and health indicators, helping NGOs identify and prioritize
countries that require urgent aid and intervention.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Problem Statement
An NGO needs to allocate limited resources effectively across countries.
The objective is to cluster countries based on key development indicators
to identify under-developed, developed, and highly developed regions.

## Dataset Overview
- Country-level socio-economic and health indicators
- Features include:
  - Child mortality
  - Income
  - GDP per capita (gdpp)
  - Life expectancy
  - Health expenditure
  - Imports, exports, inflation, fertility rate

## Key Highlights
- Performed correlation analysis and pair plots to understand feature relationships
- Identified strong correlations between income, gdpp, health, imports, and exports
- Applied feature scaling before clustering
- Used Elbow Curve and Silhouette Score to determine optimal clusters
- Finalized **3 clusters** representing different development levels
- Validated results using **Hierarchical Clustering**

## Clustering Techniques Used
- K-Means Clustering
- Hierarchical Clustering (Dendrogram analysis)

## Cluster Interpretation
- **Cluster 1:** Under-Developed Countries  
- **Cluster 2:** Developed Countries  
- **Cluster 3:** Highly Developed Countries  

Box-plot analysis was used to compare socio-economic variations across clusters.

## Business / Social Impact
This clustering approach helps NGOs:
- Identify countries requiring urgent aid
- Prioritize funding and development programs
- Make data-driven decisions for resource allocation

## Conclusion
The analysis successfully segments countries into meaningful clusters based on
development indicators. The results can directly support strategic planning and
policy decisions for NGOs and humanitarian organizations.
