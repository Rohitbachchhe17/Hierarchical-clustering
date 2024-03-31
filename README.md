# Hierarchical-clustering
## What is Hierarchical Clustering?
Hierarchical clustering is an unsupervised learning technique used to group similar objects into clusters. It creates a hierarchy of clusters by merging or splitting them based on similarity measures.
Hierarchical clustering groups similar objects into a dendrogram. It merges similar clusters iteratively, starting with each data point as a separate cluster. This creates a tree-like structure that shows the relationships between clusters and their hierarchy.


# Types of Hierarchical Clustering
There are mainly two types of hierarchical clustering:

- 1) Agglomerative hierarchical clustering
- 2) Divisive Hierarchical clustering
Let’s understand each type in detail.

# 1) Agglomerative Hierarchical Clustering
- We assign each point to an individual cluster in this technique. Suppose there are 4 data points.

# 2) Divisive Hierarchical Clustering
Divisive hierarchical clustering works in the opposite way. Instead of starting with n clusters (in case of n observations), we start with a single cluster and assign all the points to that cluster.

Agglomerative Clustering is widely used in the industry and that will be the focus in this article. Divisive hierarchical clustering will be a piece of cake once we have handle on the agglomerative type

- # Q1. What is hierarchical agglomerative clustering?
A. Hierarchical agglomerative clustering (HAC) merges the most similar clusters together, starting with each data point as a separate cluster. HAC can be used to identify natural groupings in data and is often used in exploratory data analysis and machine learning tasks such as image segmentation and document clustering

- # Q2. What is dendrogram clustering?
A. A dendrogram clustering is a tree-like diagram that displays the hierarchical relationships between clusters in a clustering analysis. It is a useful tool for identifying natural groupings or structures present in the data and for identifying similarities, differences, and outliers between clusters.

- # Q3. What is an example of a hierarchical cluster?
A. An example of a hierarchical cluster is a dendrogram that shows the hierarchical relationships between different species based on their genetic similarities.

- # Q4. Where is hierarchical clustering used?
A. Hierarchical clustering is used in various fields such as biology, sociology, marketing, and computer science. It is commonly applied in biological taxonomy, customer segmentation, pattern recognition, and image analysis.

- # Q5.How is the similarity between two clusters calculated in hierarchical clustering?
A. In hierarchical clustering, we use distance metrics to assess how similar or different two clusters are. One common metric is Euclidean distance, which measures the straight-line distance between two points. Think of it as the shortest path between them. Another metric is Manhattan distance, which looks at the ‘horizontal’ and ‘vertical’ steps needed to get from one point to another, like moving in a grid.
