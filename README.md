# Cryptocurrencies - Unsupervised Learning
![](Images/crypto-6713760_1920.jpg)
User unsupervised learning to create a portfolio for the cryptocurrency market.

## Overview
The purpose of this analysis is to create a report for company called Accountability Accounting. They would like to know if they could add cryptocurrencies in their portfolio as part of their investment for their clients.  

Unsupervised machine learning methods:
- Data processing and transforming

- Clustering and utilizing K-means Algorithm 

- Visualization & classification with 2D and 3D scatter plots



## Resources 

- **Data Source:** [crypto_data_.csv](Resources/crypto_data.csv) was retrieved from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

- **Language, Tools & Libraries:** Python, Anaconda, Jupyter Notebook, Pandas  



## Results: 
The following results on this analysis is below. 

In the process and cleaning it is determined that there are 532 tradeable cryptocurrencies based on the data provided. 



### Crypto Dataframe after processing
![](Images/Crypto_df.png)




### Dataframe with Three Principal Components after reducing Data Dimentions Using PCA.
![](Images/DataFrame%20with%20Three%20Pincipal%20Components.png)




### Finding the Best Value for k Using the Elbow Curve.
![](Images/Elbow%20Curve.png)




#### Clustered Dataframe before Visualization 
![](Images/Clustered%20df.png)





#### 3D-Scatter with PCA data and the Clusters
![](Images/3D-Scatter%20Plot%20with%20the%20PCA%20Data%20and%20Cluster.png)




### Tradeable Dataframe of Cryptocurrencies using hvplot.table()
![](Images/Tradeable%20Crypto%20Table.png)




### New DataFrame that has scalled data with clustered_df DataFrame
![](Images/New%20DataFrame%20with%20clustered_df.png)



### hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply"
![](Images/hvplot.scatter%20plot.png)



## Summary: 
In summary, after processing, transforming, clustering and visualization there are 532 cryptocurrencies that are treadeable. These are divided into four classes per hvplot.scatter plot. These classes can be determined be determined by utility, payment, security and stablecoins. In this analysis, performance and potential rate of return for each cryptocurrency were not completed in order to provide recommendations to Accountability Accounting clients.  

