# Cryptocurrency Portfolio Proposal with Unsupervised Learning
This project is designed for a financial advisor to propose a new approach to assembling investment portfolios based on cryptocurrencies. The advisor will use unsupervised learning techniques to cluster cryptocurrencies by their performance in different time periods and plot the results to visually show the performance to the board. The provided CSV file contains the price change data of cryptocurrencies in different periods.

## Steps
---
- Import the data and prepare it for analysis

- Find the best value for k by using the elbow method with the original data

- Cluster the cryptocurrencies with K-means using the original data

- Optimize the clusters with Principal Component Analysis (PCA)

- Find the best value for k by using the elbow method with the PCA data

- Cluster the cryptocurrencies with K-means using the PCA data

- Visualize and compare the results

The project starts with loading and preparing the data followed by finding the best value for K using the elbow method with the original data. The K-means algorithm is then applied to cluster the cryptocurrencies according to the provided price changes of the cryptocurrencies. The clusters are then optimized using PCA to reduce the features to three principal components. The elbow method is applied to find the best value for k with the PCA data followed by clustering the cryptocurrencies with K-means using the PCA data. Finally, the results are visualized and compared using a composite plot of the elbow curves and scatter plots of the cryptocurrency clusters.

The steps are detailed with code instructions and visualizations in the Jupyter notebook provided in the repository.
