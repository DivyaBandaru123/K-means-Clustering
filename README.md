This project demonstrates a complete implementation of the K-Means clustering algorithm from scratch, applied to real-world data from the FIFA 22 player dataset. 

K-Means is a popular unsupervised machine learning algorithm used to discover patterns and groupings in unlabeled data.

We’ll also visualize the results and compare our custom implementation with the reference algorithm from scikit-learn.

📌 Project Overview:

Goal: Build a K-Means clustering algorithm from scratch using Python and apply it to group FIFA 22 players based on selected performance metrics.

🔍 What is K-Means?

K-Means is an iterative, unsupervised learning algorithm used for clustering data into k groups based on feature similarity. It aims to minimize the within-cluster variance.

🧱 Project Steps:

Write pseudocode for the K-Means algorithm.

Implement the K-Means logic using NumPy and Pandas:

Random centroid initialization

Assigning data points to the closest centroid

Recalculating centroids

Repeating until convergence

Visualize clusters using PCA (to reduce dimensions to 2).

Compare performance with the scikit-learn version.

🗂️ File Overview:
	
Description : clustering.ipynb	Full code implementation and step-by-step output

Dataset : players_22.csv used for clustering

🧪 How It Works

Initialization: Choose number of clusters k and randomly assign initial centroids

Iteration: For each data point, compute its distance to each centroid and assign each point to the nearest cluster

Recalculate each centroid as the mean of its assigned points

Repeat until centroids stop changing or max_iterations reached

Visualization:

Reduce high-dimensional features to 2D using PCA

Color each cluster and plot centroids

Comparison:

Use sklearn.cluster.KMeans to validate accuracy and performance
