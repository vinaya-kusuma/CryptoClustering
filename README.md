This study predicts if cryptocurrencies are affected by 24-hour or 7-day price changes using Python and unsupervised learning

- Procedure
  
  - Cluster Cryptocurrencies with K-means Using the Original Scaled Data
  - The cryptocurrency data read from the csv file is scaled using the Standardscalar() module from scikit-learn
  - Find the best value of k is found by elbow method
  - Cluster Cryptocurrencies with K-means algorithm
  - Create a scatter plot using hvPlot
    
- Optimize Clusters with Principal Component Analysis
  - Create a new DataFrame with the PCA data
  - Find best value of k by elbow method on the PCA data
  - Predict the clusters to group the cryptocurrencies using the PCA data.
  - Create a scatter plot using hvPlot 

<img width="524" alt="image" src="https://github.com/vinaya-kusuma/CryptoClustering/assets/81578500/ce12bbc6-ad2c-4f6b-a167-7d093c197660">

<img width="522" alt="image" src="https://github.com/vinaya-kusuma/CryptoClustering/assets/81578500/5b6bbbef-e4a9-4528-98f3-1c595448a415">

<img width="518" alt="image" src="https://github.com/vinaya-kusuma/CryptoClustering/assets/81578500/aaf77b22-5f9c-44cb-b64e-9ae015046fd7">

<img width="520" alt="image" src="https://github.com/vinaya-kusuma/CryptoClustering/assets/81578500/683cdb4f-1619-413d-b72f-07e77a8fca74">


- Conclusion
  - Visualizing the clusters in the original feature space reveals that the four clusters are not clearly separated.However, when visualized in the reduced dimensionality space, the clusters become more distinct and tightly clustered. This indicates that dimensionality reduction enabled the k-means algorithm to identify more coherent, well-separated clusters, despite using fewer features. Reducing dimensions has reduced the redundant or less informative features. The remaining features were able to better capture the key differences between the clusters and making them distinct.
  




