# Cryptocurrencies

## Overview of Analysis:

The purpose of this repository is to perform exploratory data analysis on a dataset of cryptocurrencies, and use the K-means clustering algorithm to group similar cryptocurrencies together.

## Results
The results of this project indicate that there are clear clusters of similar cryptocurrencies based on the total coins mined and total coin supply. By using the K-means clustering algorithm, we were able to group similar cryptocurrencies together, and visualize the clusters using a 3D scatter plot. 

![3D Scatter](https://github.com/JGarza4903/Cryptocurrencies/blob/main/Images/scatter3D.png)



Additionally, the TotalCoinSupply and TotalCoinsMined columns were scaled using MinMaxScaler().fit_transform method. 
Then, we created a new DataFrame using the clustered_df DataFrame index that contains the scaled data and used a scatter plot to visualize the scaled results.

![scatter](https://github.com/JGarza4903/Cryptocurrencies/blob/main/Images/scatter.png)

