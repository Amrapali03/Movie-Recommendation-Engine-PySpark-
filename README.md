# Movie-Recommendation-Engine
Built a movie recommendation engine using Collaborative Filtering with Spark's Alternating Least Squares implementation on GroupLens MovieLens Dataset. Created RDD by loading and parsing dataset, leveraged historical user preferences to build recommender models with Spark MLlib to successfully provide tailored movie suggestions for a new user.
## Goal
Showcasing the business potential in the Ripe Pumpkins' new initiative movie recommendation, Pumpkinmeter score.

## Use Case Name
Ripe Pumpkins - a movie review-aggregation service

## Use Case URL (web site URL, aka the source project)
https://www.codementor.io/@jadianes/building-a-recommender-with-apache-spark-python-example-app-part1-du1083qbw

## Introduction 
Our start-up business ‘Ripe Pumpkins’ is building a collaborative recommendation measurement system called  ‘Pumpkinmeter’ for millions of fans. This use case focuses on building a movie recommendation system using collaborative filtering with Spark. The goal is to provide personalized movie recommendations to users based on their preferences and historical movie ratings. The system utilizes Spark's distributed computing capabilities to handle large-scale datasets and deliver real-time recommendations.


## Dataset 
Dataset used – name, source address, summary, (list of all fields of dataset, as appendix)
Name: GroupLens MovieLens Dataset
Small: 100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. Last updated 9/2018.
Full: 27,000,000 ratings and 1,100,000 tag applications applied to 58,000 movies by 280,000 users. Includes tag genome data with 14 million relevance scores across 1,100 tags. Last updated 9/2018.

Source address: 
Complete dataset URL
http://files.grouplens.org/datasets/movielens/ml-latest-small.zip

Small dataset URL
http://files.grouplens.org/datasets/movielens/ml-latest.zip

## Summary: 
The GroupLens MovieLens dataset contains movie ratings and user reviews collected from the MovieLens website.
It includes information such as user ratings, movie titles, genres, timestamps, and demographic data. 
This dataset serves as a valuable resource for training and evaluating recommendation systems.

