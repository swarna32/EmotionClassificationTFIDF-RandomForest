# Emotion Classification Using TF-IDF 

## Overview
This project focuses on classifying emotions into six categories: sadness, anger, love, surprise, fear, and happy. The dataset is preprocessed, and TF-IDF (Term Frequency-Inverse Document Frequency) is used for feature extraction. Several machine learning models, including Gaussian Naive Bayes, Decision Tree, K-Nearest Neighbors (KNN), Logistic Regression (LR), and Random Forest, are trained and their performances evaluated.

## Dataset
- **Emotion Classes**: 6 (sadness, anger, love, surprise, fear, happy)
- **Data Preprocessing**: Text data is cleaned and preprocessed to remove noise and irrelevant information.

## Feature Extraction
- **TF-IDF**: Used to convert the text data into numerical features. TF-IDF helps in transforming the textual data into a matrix of term features, where each term's weight reflects its importance within a document relative to the entire corpus.

## Model Training and Evaluation
The following machine learning models were trained and evaluated:
- **Gaussian Naive Bayes**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression (LR)**

Each model's performance was assessed using standard metrics such as accuracy, precision, recall, and F1-score.
