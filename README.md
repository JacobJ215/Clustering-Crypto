# Clustering-Crypto

## Background 

The purpose of this project is to help simplfy the cryptocurrency space by generating a list of tradable currencies and grouping these currencies into particlular categories. 

Here we breakdown the cryptocurrency markey by utilizing unsuperized machine to cluster and classify our data and Amazon SageMaker to vizualize our results.

This is accmomplished by the running through following tasks as displayed below:


- Data Preprocessing: We are importing our data from a local file 'crypto_data.csv' we then prepare the data for dimension reduction with PCA and clustering using K-Means.

- Reducing Data Dimensions Using PCA: Here we reduce data dimension using the PCA algorithm from sklearn.

- Clustering Cryptocurrencies Using K-Means:  Next we predict clusters using the cryptocurrencies data using the KMeans algorithm from sklearn.

- Visualizing Results: In our first notebook clustering_crypto .ipynb we are visualizing our data using the hvplot libary.

- Finally we deploy the clustering_crypto .ipnyb  notebook to Amazon SageMaker and utilize altair to vizualize our data, this notebook is then saved as clustering_crypto_sm .ipynb
