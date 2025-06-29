# MovieLens25m-Recommender

## Overview
This project evaluates several commonly used recommendation system models on the MovieLens 25M dataset using offline evaluation metrics. Offline evaluation lacks real-time user feedback such as click-through rate or retention time. Therefore, this study aims to understand how different models—used in platforms like Netflix and Letterboxd—perform when evaluated purely from existing user-item interactions.

We implement and compare popularity-based, weighted popularity-based, cosine similarity, and matrix factorization (ALS) models.

## Dataset
The dataset can be found here: [Kaggle - MovieLens 25M](https://www.kaggle.com/datasets/garymk/movielens-25m-dataset/data). The ratings.csv was the main dataset used to train and evaluate the models, and has 25,000,090 training examples.

## Running the notebooks
The notebooks were created within the Google Colab environment and all dependencies are installed by the notebooks themselves, but a requirements.txt is provided.
