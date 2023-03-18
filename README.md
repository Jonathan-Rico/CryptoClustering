# CryptoClustering

In this challenge, we use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

In order to use a K-means model to predict the clusters to group the cryptocurrencies in, we employ the elbow method to find the best value for k.
We then plot the results using a scatter plot (through the iuse of hvplot) to better visualize the data clusters.

Using the original scaled DataFrame, we perform a Principal Component Analysis to reduce the features to three principal components.
We then cluster the cryptocurrencies using a K-means model using the PCA data and plot the results using a scatter plot.

The results from both these models showed that the impact of using fewer features to cluster the data using K-means did not make a significant difference
in the visualization of cryptocurrency cluster groups.

