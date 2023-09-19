                                           ## AlmaBetter Verfied Project - [AlmaBetter School](https://www.almabetter.com/)
# Netflix Movies and TV Shows Clustering

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Execution](#execution)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Data Preprocessing](#data-preprocessing)
6. [Clustering](#clustering)
7. [Recommendation System](#recommendation-system)
8. [Conclusion and Future Considerations](#conclusion-and-future-considerations)

## Introduction

The goal of this project was to perform exploratory data analysis (EDA) on Netflix data, with a focus on understanding the types of content available in different countries, the balance between TV shows and movies, and clustering similar content. The project aimed to provide insights into Netflix's content distribution strategy and recommendations for content creators and viewers.

## Dataset

The dataset used in this project contains information related to Netflix movies and TV shows, including title, cast, director, genre, censor rating, description, type, and country. It serves as the foundation for exploring Netflix's content landscape and clustering similar content. [Dataset Source](https://drive.google.com/file/d/1xJGllnE12mAggLuRo8b0oNSshUlG8GvF/view?usp=drive_link)

## Execution

To execute this project and explore Netflix's content landscape, follow these steps:

1.Open the Jupyter Notebook file named Netflix_Movies_and_Tv_Shows_Clustering.ipynb.

2.Execute the notebook cell by cell to load and preprocess the data, perform exploratory data analysis, apply clustering algorithms, and visualize the results.

The notebook provides detailed insights into Netflix's content, including the balance between TV shows and movies, genre distributions, and clustered content analysis.

## Exploratory Data Analysis (EDA)

During the EDA phase, several interesting findings were uncovered:
- Netflix has a larger collection of movies compared to TV shows.
- Content additions to Netflix have been increasing since 2017.
- Months of October and January witnessed the highest number of content releases.
- A significant proportion of content falls under the TV-MA rating category.
- The United States and the United Kingdom were top contributors of adult content.
- India showed a higher percentage of teen-rated content.
- Top genres on Netflix included international content, drama, and comedy.

## Data Preprocessing

For data preprocessing, text-based features were considered and underwent the following transformations:
- Categorical features were encoded using one-hot encoding.
- Textual preprocessing techniques were applied, including lowercasing, punctuation removal, stopword removal, text normalization (stemming and lemmatization), and text vectorization (using TF-IDF).
- The dataset was reduced using PCA to 1500 components, explaining 90% of the variance.

## Clustering

Two clustering algorithms, KMeans and Agglomerative Hierarchical clustering, were applied to cluster similar content based on the reduced dataset. Silhouette analysis and the Elbow method were used to select the best model, resulting in 8 clusters. 

## Recommendation System

A recommendation system was developed using cosine similarity on the TF-IDF matrix to suggest similar content to users.

## Conclusion and Future Considerations

In conclusion, this project successfully explored Netflix's content distribution strategy, analyzed the balance between TV shows and movies, and employed clustering algorithms to group similar content. The insights gained can be valuable for content creators, viewers, and Netflix itself in enhancing content recommendations and optimizing content acquisition strategies.

Future considerations include incorporating additional features such as subscriber count and number of views to deepen the analysis and understand the relationship between content duration, viewership, and subscriptions.

I hope this project contributes to a better understanding of Netflix's content landscape and improves the viewing experience for users.

I hope this comprehensive README provides you with all the necessary information to get started with your "Netflix Movies and TV Shows Clustering" project. Should you require any further assistance or have questions, please feel free to reach out to [me](www.linkedin.com/in/subhash-somarouthu).

Happy clustering and exploration of Netflix's content landscape! 🍿📺😀

