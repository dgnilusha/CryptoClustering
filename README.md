# CryptoClustering

This repository contains code to cluster cryptocurrencies using K-means and compare results between the original scaled data and PCA-transformed data.

Getting Started
Prerequisites
Python 3.x
Required packages: pandas, numpy, scikit-learn, matplotlib, hvplot

Task 1: Find the Best Value for k Using the Original Scaled DataFrame
Open the elbow_curve_original.py file.

Follow the instructions to compute the inertia values and plot the elbow curve.

Answer the question: "What is the best value for k?"

Task 2: Cluster Cryptocurrencies with K-means Using the Original Scaled Data
Open the kmeans_original.py file.

Initialize the K-means model with the best value for k.

Fit the K-means model using the original scaled DataFrame.

Predict the clusters and create a scatter plot using hvPlot.

Task 3: Optimize Clusters with Principal Component Analysis
Open the pca_optimization.py file.

Perform PCA on the original scaled DataFrame and calculate the explained variance.

Create a new DataFrame with the PCA data.

Task 4: Find the Best Value for k Using the PCA Data
Open the elbow_curve_pca.py file.

Follow the instructions to compute the inertia values and plot the elbow curve.

Answer the question: "What is the best value for k when using the PCA data?"

Task 5: Cluster Cryptocurrencies with K-means Using the PCA Data
Open the kmeans_pca.py file.

Initialize the K-means model with the best value for k.

Fit the K-means model using the PCA data.

Predict the clusters and create a scatter plot using hvPlot.

Answer the question: "What is the impact of using fewer features to cluster the data using K-Means?"

Summary
This repository provides code to cluster cryptocurrencies using K-means and compare results between the original scaled data and PCA-transformed data.
