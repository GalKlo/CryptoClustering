# CryptoClustering

Unsupervised learning methods were used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Preparation steps:
- Before conducting the analysis data was scaled using StandardScaler.

The analysis was performed on the original scaled data, as well as the optimized dataset, where a PCA was performed to reduce the featurs of the original DataFrame to 3 principal components.

Steps to cluster the cryptocurrenscies on both DataFrames (origianl scaled and optimized) included:
- Applying elbow method to find the best number of clusters (k value).
- Using the best identified k value fit the K-means model.
- Predicting the clusters to group the cryptocurrencies.
- Visualizing the results using a scatter plot. 