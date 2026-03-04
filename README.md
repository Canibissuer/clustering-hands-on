# clustering-hands-on
## Dataset
The Iris dataset contains 150 observations of iris flowers with four numerical features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Each observation belongs to one of three species of iris.

## Methods Used
Two clustering algorithms were applied:

K-Means Clustering 
K-Means partitions the data into a specified number of clusters (K). In this project, K=3 was used to match the number of iris species.

DBSCAN (Density-Based Spatial Clustering) 
DBSCAN groups points based on density and can identify noise or outliers that do not belong to any cluster.

## Results
The visualizations show that petal length and petal width provide the clearest separation between groups. K-Means successfully identified three clusters that closely match the three iris species. DBSCAN produced two main clusters and labeled some points as noise, demonstrating its sensitivity to density parameters.

## Conclusion
Both clustering methods reveal natural patterns in the Iris dataset. K-Means performs well when the number of clusters is known, while DBSCAN is useful for detecting irregular cluster shapes and identifying noise in the data.
