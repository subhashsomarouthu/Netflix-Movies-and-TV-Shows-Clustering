# Netflix-Movies-and-TV-Shows-Clustering
Clustering similar content by matching text-based features and building a recommendation system

The objective of this project is to gain insights and understanding from the Netflix dataset through Exploratory Data Analysis (EDA) and clustering. Additionally, the project aims to determine the type of content available in different countries, examine if Netflix has shifted its focus towards TV shows rather than movies in recent years, and cluster similar content based on text-based features.

# Dataset
The dataset contains information on Tv shows and movies available on netflix as of 2021. It consists of 7787 rows and 12 columns.

# Project Overview

Exploratory Data Analysis.

Clustering similar content

Recommendation system


# Machine learning models

KMeans Clustering

Hierarichal Clustering (Agglomerative approach)

# Best Model

Kmeans, using silhouette analysis and Elbow method the best model produced a silhouette score of 0.3 with 8 clusters. It also has davis-bould score of 1.39.

Agglomarative Hierarchical clustering using dendrogram produced a silhouette score of 0.316 similar to kmeans and davis-bound score of 1.33 with 8 clusters.

Based on the evaluation metrics and business objective, both kmeans and Agglomarative hierarchical clustering algorithms are doing good in job in clustering similar content with 8 clusters.


# Limitations

Certain features like user watch time, number of subscribers per month would have given us more insight into whether duration and regional content affecting subscribers.

# Future work

We can use Topic modeling techniques on text based features and then cluster the similar content. It would save computational time and also can build more precise clusters.


