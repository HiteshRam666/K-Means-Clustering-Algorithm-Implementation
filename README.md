# Unsupervised Learning (Clustering) Implementation

Unsupervised learning, also known as unsupervised machine learning, uses machine learning algorithms to analyze and cluster unlabeled datasets. These algorithms discover hidden patterns or data groupings without the need for human intervention.
Its ability to discover similarities and differences in information make it the ideal solution for exploratory data analysis, cross-selling strategies, customer segmentation, and image recognition.

Unsupervised learning models are utilized for three main tasks—clustering, association, and dimensionality reduction. Below we’ll define each learning method and highlight common algorithms and approaches to conduct them effectively.

## Clustering
Clustering is a data mining technique which groups unlabeled data based on their similarities or differences. Clustering algorithms are used to process raw, unclassified data objects into groups represented by structures or patterns in the information. Clustering algorithms can be categorized into a few types, specifically exclusive, overlapping, hierarchical, and probabilistic.

![unsupervised-machine-learning-1](https://github.com/HiteshRam666/Unsupervised-Learning-Clustering-Implementation/assets/116026459/7b36b404-be67-4817-9e89-194959cfe3c7)


### K-Means Clustering: 
K-means clustering is a common example of an exclusive clustering method where data points are assigned into K groups, where K represents the number of clusters based on the distance from each group’s centroid. The data points closest to a given centroid will be clustered under the same category. A larger K value will be indicative of smaller groupings with more granularity whereas a smaller K value will have larger groupings and less granularity. K-means clustering is commonly used in market segmentation, document clustering, image segmentation, and image compression.

![k-means-clustering-algorithm-in-machine-learning](https://github.com/HiteshRam666/Unsupervised-Learning-Clustering-Implementation/assets/116026459/8697912e-9833-4cfc-8f57-6c2063124f4e)


### Hierarchical clustering
Hierarchical clustering, also known as hierarchical cluster analysis (HCA), is an unsupervised clustering algorithm that can be categorized in two ways: agglomerative or divisive.

Agglomerative clustering is considered a “bottoms-up approach.” Its data points are isolated as separate groupings initially, and then they are merged together iteratively on the basis of similarity until one cluster has been achieved. Four different methods are commonly used to measure similarity:

- Ward’s linkage: This method states that the distance between two clusters is defined by the increase in the sum of squared after the clusters are merged.
- Average linkage: This method is defined by the mean distance between two points in each cluster.
- Complete (or maximum) linkage: This method is defined by the maximum distance between two points in each cluster.
- Single (or minimum) linkage: This method is defined by the minimum distance between two points in each cluster.
Euclidean distance is the most common metric used to calculate these distances; however, other metrics, such as Manhattan distance, are also cited in clustering literature.

Divisive clustering can be defined as the opposite of agglomerative clustering; instead it takes a “top-down” approach. In this case, a single data cluster is divided based on the differences between data points. Divisive clustering is not commonly used, but it is still worth noting in the context of hierarchical clustering. These clustering processes are usually visualized using a dendrogram, a tree-like diagram that documents the merging or splitting of data points at each iteration.

![0_afzanWwrDq9vd2g-](https://github.com/HiteshRam666/Unsupervised-Learning-Clustering-Implementation/assets/116026459/32c22c42-4ee9-4437-8a09-5f755076f2a5)


### DBSCAN Clustering
DBSCAN stands for Density-Based Spatial Clustering of Applications with Noise.

It groups ‘densely grouped’ data points into a single cluster. It can identify clusters in large spatial datasets by looking at the local density of the data points. The most exciting feature of DBSCAN clustering is that it is robust to outliers. It also does not require the number of clusters to be told beforehand, unlike K-Means, where we have to specify the number of centroids.
![1_yT96veo7Zb5QeswV7Vr7YQ](https://github.com/HiteshRam666/Unsupervised-Learning-Clustering-Implementation/assets/116026459/938e3c74-a11c-4428-a0e2-07506edde4e3)
