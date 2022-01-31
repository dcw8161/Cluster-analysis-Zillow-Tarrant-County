# Cluster-analysis-Zillow-Tarrant-County
Cluster analysis for Zillow Tarrant County dataset was performed and eventually to predict the real estate prices. 

## Data Preparation
- Total number of records = 1883

- Missing value percentages for two variables as follows.
   - exterior_walls    11.842804
   - roof              18.799788

- Missing values are treated using their modes.

## EDA
- Highly correlated features were found and the first feature that is correlated with anything other feature was removed.

## Data Visualization 
Data visualization was done by Tableau and SweetViz. Tableau link is as followed

### Tableau Link:
[Cluster-Analysis-Zillow](https://public.tableau.com/app/profile/darshika.keerthisinghe/viz/ZillowTarrantCountyDataAnalysis/ZillowTarrantCountyDataAnalysis?publish=yes)

## Cluster analysis
- PyCaret kmeans model was used for cluster analysis
<img width="1311" alt="image" src="https://user-images.githubusercontent.com/48637798/151740569-f9727e5f-ce85-4374-8328-ea8ff4edab62.png">
- Number of clusters were found using elbow method and elbow was found at k=5
<img width="781" alt="image" src="https://user-images.githubusercontent.com/48637798/151740650-3311338b-c3d9-44bb-936b-3aa928ac3573.png">
- Cluster distribution plot
<img width="1329" alt="image" src="https://user-images.githubusercontent.com/48637798/151740774-69ef297f-8dde-4680-980e-2b87b01b75a2.png">

## Machine learning Model and Evaluation
- First,Machine learning model was performed for the entire dataset
- Then, Machine learning Model was performed for the cluster 2 which has maximum data points assigned
- Accuracies were compaired for bothe the models
- 
