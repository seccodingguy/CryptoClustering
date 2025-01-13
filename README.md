# Module 11 - CryptoClustering
# Author: Mark Wireman

## Introduction
Understanding of the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price fluctuations across various timeframes. Specifically, examine price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

## Summary
The most significant shift occurs at k = 4. There is a slight shift at k = 2, however, the optimal value is 4 given the greatest elbow curve displayed in the graph.

For PCA1, the strongest influences are 200d at 1y, with 59.4% and 56.8% respectively. PCA2 is 30d and 14d, at 56.2% and 54.0% respectively. And PCA3 the, 7d and 60d, at 78.8% and -36.1% respectively.

## How to run
Either download the repository or perform a git pull. When downloaded, run the crypto_clustering.ipynb file using Jupyter Notebook or Visual Studio code.