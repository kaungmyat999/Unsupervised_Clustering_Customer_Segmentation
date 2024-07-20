# Unsupervised Clustering Customer Segmentation Project

This project is about segment the Customers of [online+retail dataset](https://www.google.com/url?q=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F352%2Fonline%2Bretail) using Unsupervised Algorithms.\
In this project Unsupervised Algorithms like [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering) and [Hierarchical Clustering](https://en.wikipedia.org/wiki/Hierarchical_clustering) models are used.

## Data :bar_chart:

Name: Customer Segmentation Dataset\
Source: UC Irvine machine learning repository\
Link: https://archive.ics.uci.edu/dataset/352/online+retail

Dataset is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Outline Of The Project: :bookmark_tabs:

Here is the work flow of the project:

- Data exploration.
- Data Cleaning (Dropping Missing Values and removing outliers).
- Performed (EDA) & Visualising the distribution of data & their relationships to get some insights on the relationship between the feature-set.
- Appropriate Transformations will apply on the data to satisfy the key assumptions. Later follow by Standardization.
- Models Building & Hyperparameter Tuning
  - K Means algorithm will apply and k parameter will be tuned using the Elbow Plot and Silhouette and results will be plotted.
  - Hierarchical Clustering is applied and results are also plotted.
Make Inference on the customers of resulting clusters based on the clustering result of these models.

## Inference On The Results of Models: :golf:

### K-Means Clustering with 3 Cluster Ids
By using the plot, we know how each segment differs. It describes more than we use the summarized table. We infer that cluster 1 is frequent, spend more, and they buy the product recently. Therefore, it could be the cluster of a loyal customer. Then, the cluster 2 is less frequent, less to spend, but they buy the product recently. Therefore, it could be the cluster of new customer. Finally, the cluster 0 is less frequent, less to spend, and they buy the product at the old time. Therefore, it could be the cluster of churned customers.

### Hierarchical Clustering with 3 Cluster Ids

According to the plots of hierarchical clustering we can infer that customers in cluster 2 are frequent buyers and buy high amount. Cluster 1 customers are also high amount buyers but buy less frequent than the customers in cluster 1. Cluster 0 customers are the one who buy least amount and frequency is also lower than cluster 1 and cluster 2.

:heart: Please check out the [notebook](https://github.com/kaungmyat999/Unsupervised_Clustering_Customer_Segmentation/blob/main/Unsupervised_Clusterings_Final_Project.ipynb) for detail implementation. 
