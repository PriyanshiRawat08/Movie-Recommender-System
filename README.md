# AI-ML-Project
This repository contains all my AI/ML Projects
<hr/>
1. Movie Recommendation System:-

![Logo](https://github.com/user-attachments/assets/efc8ba56-8f50-45d9-af05-e6bbbf1c58e5)

Business Objectives :
All entertainment websites or online stores have millions/billions of items. It becomes challenging for the customer to select the right one. At this place, recommender systems come into the picture and help the user to find the right item by minimizing the options.

Recommendation Systems in the world of machine learning have become very popular and are a huge advantage to tech giants like Netflix, Amazon and many more to target their content to a specific audience. These recommendation engines are so strong in their predictions that they can dynamically alter the state of what the user sees on their page based on the user’s interaction with the app.

The business objective for us is:

1. To create a Collaborative Filtering based Movie Recommendation System
2. Predict the rating that a user would give to a movie that he has not yet rated
3. Minimize the difference between predicted and actual rating (RMSE and MAPE)
   
Data Collection :
The dataset has been obtained from Grouplens.

Link : https://grouplens.org/datasets/movielens/20m/

This dataset (ml-20m) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in the files genome-scores.csv, genome-tags.csv, links.csv, movies.csv, ratings.csv and tags.csv.

For our objective, we would be using "ratings.csv" and "movies.csv" data files.

Modelling :
The following modelling approach was used in the project:

1. Loading & exploring the Movie and User ratings data
2. Creating User-Item Matrix, User-User and Item-Item similarity matrices for Movie Recommendations
3. Creating feature and applying ML models to predict the ratings for unseen movies for a user

The detailed analysis and model creation can be found in the .ipynb file.

Result :
Some of the test images are given below.

The results from Movie-Movie Similarity is as below:

![M_1](https://github.com/user-attachments/assets/6941425b-f6c3-46d1-8a81-225d12a89ce9)


The results from User-User Similarity is as below:

![M_2](https://github.com/user-attachments/assets/9bcc6760-fcee-475b-a149-9a0a358992f0)



The Feature Importance for predicting ratings is as below:

![M_3](https://github.com/user-attachments/assets/0774da0a-52ad-443e-bf08-fcb8ac5b109d)



The results from different ML models are as follows:

![M_4](https://github.com/user-attachments/assets/a6acc448-60df-4858-8e82-9dafcc0281f3)



The sample movie recommendation based on Collaborative Filtering is as follows:

![M_5](https://github.com/user-attachments/assets/f6cd01e9-8bcf-4575-bec7-236632577a3b)



Conclusions :
In this project, we learned the importance of Recommendation Systems, the types of recommender systems being implemented, and how to use matrix factorization to enhance a system.

We then built a movie recommendation system that considers user-user similarity, movie-movie similarity, global averages and matrix factorization. These concepts can be applied to any other user-item interactions systems.

We tried generating recommendations based on similarity matrix and Collaborative Filtering techniques.

We tried to predict the ratings for movies that the user might give based on its past rating behaviours and measure the accuracy using RMSE and MAPE error metrics.

Surely, there is huge scope of improvement and tring out different techniques and ML/DL algorithms.
