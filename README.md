# Clustering-Algorithm
#1. Loading and Preprocessing (1 Mark)
Load the Iris dataset from sklearn.
Drop the species column to focus solely on clustering features.


#A. KMeans Clustering
#1. Description:
#How it works:
KMeans is an iterative algorithm that partitions data into k clusters.
-Initialize centroids randomly.
-Assign each data point to the nearest centroid.
-Recalculate centroids based on assigned points.
-Repeat until centroids stabilize or maximum iterations are reached.
#Suitability for Iris Dataset:
The Iris dataset is small and well-separated, making it ideal for KMeans since it clusters linearly separable data effectively.


#B. Hierarchical Clustering
#1. Description:
#How it works:
#Hierarchical clustering creates a dendrogram to visualize nested clusters.
-Start with each point as its cluster.
-Iteratively merge the two closest clusters.
-Stop when only one cluster remains.
#Suitability for Iris Dataset:
Hierarchical clustering is effective for small datasets like Iris, allowing a hierarchical view of relationships between data points.
