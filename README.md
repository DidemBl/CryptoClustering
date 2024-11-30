# CryptoClustering

You are asked to analyze the data on cryptocurrencies as per the instructions provided below to predict the impact of 24-hr and 7-day price changes on the cryptocurrency market. 

Instructions: 

1- Normalize the data using the StandardScaler() module from scikit-learn. 
2- Make a dataframe and set the coin-id column as the index. 

3- Find the best K value using the elbow method. Create a list to hold the inertia values for each possible k value within a range of one to eleven. Create a dictionary for the elbow curve plot. Make a line chart to visualize the plot and find the best k value. 

4- Fit the data to the k-means model with the computed k value, predict the clusters and add the clusters to the scaled dataframe. 

5- Create a scatter plot using hvplot with the x-axis as "price_change_percentage_24h" and the y-axis as "price_change_percentage_7d". Add the coin-id information to the hover-cols parameter to view the cryptocurrency for each point.

6-Run a principal component analysis on the original dataframe with 3 principal components, find the explaind variance for all three principal components, make a dataframe with the scaled PCA data and set the coin-id as the index. Compute the best k value with for the PCA dataframe using the Elbow curve method and cluster the crypto-currencies using the K-means method. Finally, create a scatter plot using the PCA data with the x-axis as "PC1" and the y-axis as "PC2". Add the coin-id to the hover_cols parameter to view the cryptocurrency for each datapoint. Answer the question on the impact of using fewer features on the clusters.


