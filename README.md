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

🗂️ File Overview
File Name	Description
clustering.ipynb	Full code implementation and step-by-step output
players_22.csv	Dataset used for clustering

📊 Dataset
We use the FIFA 22 player dataset (specifically players_22.csv) which includes attributes like:

Pace

Shooting

Passing

Dribbling

Physical

📥 Download it from Kaggle (registration may be required).

⚙️ Local Setup Instructions
✅ Prerequisites
Python 3.8 or higher

Jupyter Notebook or any Python IDE

📦 Required Packages
Install the necessary packages using pip:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib
🧪 How It Works
Initialization:

Choose number of clusters k

Randomly assign initial centroids

Iteration:

For each data point, compute its distance to each centroid

Assign each point to the nearest cluster

Recalculate each centroid as the mean of its assigned points

Repeat until centroids stop changing or max_iterations reached

Visualization:

Reduce high-dimensional features to 2D using PCA

Color each cluster and plot centroids

Comparison:

Use sklearn.cluster.KMeans to validate accuracy and performance
