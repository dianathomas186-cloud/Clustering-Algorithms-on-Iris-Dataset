# Clustering-Algorithms-on-Iris-Dataset
Machine Learning - Clustering using Iris Dataset (KMeans and Hierarchical Clustering) 

##  Objective
The objective of this assignment is to evaluate understanding and ability to apply clustering techniques to a real-world dataset.

---

##  Dataset Used
- Iris Dataset
- Loaded from sklearn library

---

##  Preprocessing Steps
- Loaded Iris dataset from sklearn
- Converted into pandas DataFrame
- Dropped the species column (since clustering is unsupervised)
- Standardized the data using StandardScaler

---

##  Clustering Algorithms Implemented

### 1️⃣ KMeans Clustering
- Description: Partition-based clustering algorithm
- Groups data into K clusters by minimizing within-cluster variance
- Applied with n_clusters = 3
- Visualized using PCA (2D projection)

### 2️⃣ Hierarchical Clustering
- Description: Tree-based clustering method
- Used Agglomerative Clustering
- Applied with n_clusters = 3
- Visualized using PCA

---

##  Output
- Cluster centers printed
- Cluster labels displayed
- PCA scatter plots generated
- All required components implemented successfully

---

##  Conclusion
Both KMeans and Hierarchical clustering successfully grouped the Iris dataset into 3 clusters. The visualization clearly shows separation between clusters, demonstrating the effectiveness of clustering techniques on structured numerical datasets.
