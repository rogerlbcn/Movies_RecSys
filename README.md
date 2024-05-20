# Movies_RecSys

######################################
## A Recommender System of Movies
######################################

This repository includes a recommender system for movies, based on user ratings.

The dataset used is: "MovieLens full 25-million recommendation data" (ml-25m), retrieved from Kaggle. 

The dataset was published in 2019. 


Type of RecSys used:

Collaborative Filtering. This will allow us to laverage the large amount of data from the 25M data points present in this dataset, in order to make movie recommendations based on other similar profiles, similar to the user. 


## Project Scoping:

Goal:

The goal with this RecSys is to create a recommendation engine, which recommends users movies that they are most likely to like bsed on other similar user profiles. Since there is enough data (25 milion data points), a collective filtering RecSys approach can be taken.

Data:

We will be using the following datasets from Kaggle's "MovieLens full 25-million recommendation data" (ml-25m), which can be accessed here: https://www.kaggle.com/datasets/patriciabrezeanu/movielens-full-25-million-recommendation-data?resource=download.

We will mainly use the following CSV files:
- `movies`: 
- `ratings`: 


## References:

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872 
