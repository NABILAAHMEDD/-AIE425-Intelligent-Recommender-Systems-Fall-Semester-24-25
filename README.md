# -AIE425-Intelligent-Recommender-Systems-Fall-Semester-24-25
Neighborhood CF models (user, item-based CF)

This repository contains the code and report for Assignment #1: Neighborhood Collaborative Filtering Models for the AIE425 Intelligent Recommender Systems course. The project explores the implementation and evaluation of User-Based and Item-Based Collaborative Filtering (CF) models, focusing on two similarity measures: Cosine Similarity and Pearson Correlation.

Overview
The project aims to predict user preferences based on the similarities between users and items. Using data sourced from the TMDb API, this project illustrates how Neighborhood Collaborative Filtering enhances personalization by analyzing patterns in user behaviors.

Key Sections
Data Collection: Data is gathered from TMDb API, filtered by user vote count, and preprocessed to form a robust dataset.
Data Preprocessing: Handling of missing values, normalization, and structuring into a User-Item Matrix.
User-Item Matrix Creation: Building a 10x10 matrix to quantify user-item interactions, crucial for calculating similarities.
Similarity Measures:
Cosine Similarity: Captures general user or item preferences without scaling adjustments.
Pearson Correlation: Adjusts for individual user biases, providing a personalized approach.
Rating Predictions: Predicted ratings for unrated items based on CF techniques.
Top-N Recommendations: Generated by both User-Based and Item-Based CF models using the similarity measures.
Requirements
Python 3.x
Libraries:
pandas
numpy
scikit-learn
scipy
matplotlib
Files
Code Notebook: Contains all functions for data loading, preprocessing, matrix creation, similarity calculations, and predictions.
Data CSV Files:
average_item_ratings.csv: Average ratings per item.
User-Item Matrix CSV.
Usage
Setup: Clone the repository and install required libraries.
Data Loading and Preprocessing: Run the code cells to load and preprocess the data.
Similarity Computation: Execute cells to calculate Cosine and Pearson similarity matrices.
Prediction and Recommendation Generation: Run cells to compute predicted ratings and generate Top-N recommendations.
Visualization: Review similarity matrices and recommendations through provided charts.
Results and Analysis
The model generates meaningful insights through CF, with Pearson Correlation proving to be more accurate in capturing user-specific preferences than Cosine Similarity.

Evaluation Metrics
Mean Absolute Error (MAE)
Root Mean Square Error (RMSE)
Future Work
Potential enhancements include integrating mood-based, social graph-based, and context-aware recommendations for further personalization.

License
This project is for educational purposes and is subject to course regulations.

