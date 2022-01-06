# Cryptocurrencies with Unsupervised Machine Learning

## Project Overview

The purpose of this project is to create a report that includes what cryptocurrencies are on the trading market and  how client could be grouped to create a classification system for their new investment.


## Visualizing Cryptocurrencies Results

Clustering Cryptocurrencies Using K-means
[!image]()


With this new DataFrame, clustered_df , we start with a 3D Scatter plot using the Plotly Express scatter_3d() function to visualize the 4 Classes.
[!image]()






A table is created featuring the tradable cryptocurrencies using the hvplot.table().
[!image]()


A 2D hvplot scatter plot with x="TotalCoinsMined_scaled", y="TotalCoinSupply_scaled", and by="Class" with the CoinName displayed.
[!image]()

