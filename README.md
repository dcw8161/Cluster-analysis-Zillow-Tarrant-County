# Cluster-analysis-Zillow-Tarrant-County
Cluster analysis for Zillow Tarrant County dataset was performed and eventually to predict the real estate prices. 

# Data Preparation
Total number of records = 1883
Missing value percentages for two variables as follows.
  exterior_walls    11.842804
  roof              18.799788

Missing values are treated using their modes.

# EDA
- Highly correlated features were found and the first feature that is correlated with anything other feature was removed.

# Data Visualization 
Data visualization was done by Tableau and SweetViz. Tableau link is as followed

### Tableau Link:
[Cluster-Analysis-Zillow](https://public.tableau.com/app/profile/darshika.keerthisinghe/viz/ZillowTarrantCountyDataAnalysis/ZillowTarrantCountyDataAnalysis?publish=yes)

# Cluster analysis
- PyCaret kmeans model was used for cluster analysis
- Number of clusters were found using elbow method and elbow was found at k=5
