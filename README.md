# Ecommerce-Recommendation-system using Amazon Dataset

## Overview

This project implements a hybrid recommendation system for e-commerce products, combining collaborative filtering, content-based filtering, and popularity-based recommendations. It provides personalized product suggestions for both new and existing users.

## Architecture

## Description:

- Data Preprocessing: Clean and filter the review dataset for active users and products.
- Popularity Model: Ranks products based on average rating and review count.
- Collaborative Filtering (SVD): Learns user-item latent factors from ratings.
- Content-Based Filtering: Extracts textual features from product reviews using TF-IDF.
- Hybrid Model: Combines SVD and content-based scores for final recommendations.
- Smart Recommender: Chooses the appropriate method for new or existing users.

## Features

- Popularity-Based Recommendations: For cold-start users.
- Collaborative Filtering (SVD): Captures user behavior patterns.
- Content-Based Filtering: Recommends products with similar reviews/text.
- Hybrid Model: Weighted combination of SVD and content similarity.
- Evaluation Metrics: Precision@K, Recall@K, NDCG@K.
- Smart Recommendation Function: Automatically selects best strategy per user.

## Dependencies:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn



