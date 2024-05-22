# Movies_RecSys

######################################
## A Recommender System of Movies
######################################

# Movies_RecSys

## A Recommender System for Movies

This repository contains a movie recommender system based on user ratings from the MovieLens dataset.

## Dataset

The dataset used is the "MovieLens 25M Dataset," published in 2019, and retrieved from Kaggle. It contains 25 million movie ratings and one million tag applications applied to 62,000 movies by 162,000 users. You can access the dataset [here](https://www.kaggle.com/datasets/patriciabrezeanu/movielens-full-25-million-recommendation-data).

### Files Used
- `movies.csv`: Contains movie metadata including movie ID, title, and genres.
- `ratings.csv`: Contains user ratings of movies, including user ID, movie ID, rating, and timestamp.

## Type of Recommender System

This project employs Collaborative Filtering, which leverages the large dataset to make movie recommendations based on the preferences of similar users.

## Project Scope

### Goal

The goal of this recommender system is to suggest movies to users that they are likely to enjoy based on the preferences of other users with similar profiles. Given the extensive dataset with 25 million ratings, a collaborative filtering approach is well-suited to provide accurate and personalized recommendations.

### Data

We use the following datasets from Kaggle's "MovieLens 25M Dataset":
- `movies.csv`
- `ratings.csv`

These datasets provide the necessary information to implement and evaluate the recommendation system.

## Installation

To run this project, you need Python and the following libraries:
- pandas
- scikit-surprise


## Conclusion:

This project provides a robust foundation for building a movie recommendation system. Key steps included data loading, preprocessing, training an SVD model, and generating personalized recommendations. Future enhancements could include hybrid models, real-time recommendations, and a user-friendly interface to make the system more robust and practical for real-world applications.


## References:

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872 

Nguyen LV, Vo Q-T, Nguyen T-H. Adaptive KNN-Based Extended Collaborative Filtering Recommendation Services. Big Data and Cognitive Computing. 2023; 7(2):106. https://doi.org/10.3390/bdcc7020106

Widiyaningtyas T, Ardiansyah MI, Adji TB. Recommendation Algorithm Using SVD and Weight Point Rank (SVD-WPR). Big Data and Cognitive Computing. 2022; 6(4):121. https://doi.org/10.3390/bdcc6040121
