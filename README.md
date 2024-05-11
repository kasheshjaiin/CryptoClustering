# CryptoClustering

## Overview
This project aims to analyze and cluster cryptocurrency data using unsupervised learning techniques, particularly K-Means clustering, with and without optimization techniques such as Principal Component Analysis (PCA).


## Results
The analysis includes the following key steps:

1. Data preprocessing: Loading and exploring the cryptocurrency market data.
2. Normalization: Scaling the data using StandardScaler.
3. Cluster analysis:
   - Using K-Means clustering on the original scaled data to find the optimal number of clusters (k).
   - Using PCA to reduce dimensionality and then applying K-Means clustering to find the optimal k.
4. Visualizing and comparing the results:
   - Contrasting the clusters obtained from the original scaled data and the PCA-transformed data.
   - Contrasting the Elbow curves obtained from both datasets.

## Conclusion
The analysis demonstrates the effectiveness of using optimization techniques like PCA in improving clustering results. By reducing the dimensionality of the data, PCA helps identify meaningful patterns and clusters more accurately.

Feel free to explore the notebook for more detailed insights into the analysis.
