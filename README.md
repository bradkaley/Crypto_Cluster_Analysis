# Clustering Cryptos

This notebook preprocesses data from all coins available at CryptoCompare.com. Coins that have at least 1 coin mined, are tradable, and have an algorithm which in some form is Proof of Work (PoW) were clustered to create classes for analysis using the PCA algorithm and K-Means. The ideal number of clusters chosen here was 5 based on the plotted elbow curve.