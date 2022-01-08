# Clustering Cryptos

This notebook preprocesses data from all coins available at CryptoCompare.com. Coins that have at least 1 coin mined, are tradable, and have an algorithm which in some form is Proof of Work (PoW) were clustered to create classes for analysis using the PCA algorithm and K-Means. The ideal number of clusters chosen here was 5 based on the plotted elbow curve.

Deployment to Amazon SageMaker was optional for this homework and so was not completed. Here is a screenshot from the GitLab Homework Post:
![image](https://user-images.githubusercontent.com/90219722/148649655-6051dc83-d902-4222-9e93-d0c00f0da620.png)
