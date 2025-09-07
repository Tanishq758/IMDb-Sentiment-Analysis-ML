# IMDb-Sentiment-Analysis-ML
Sentiment analysis of IMDb movie reviews using classical machine learning models: Logistic Regression, Naive Bayes, and SVM
This repository contains a sentiment analysis project on the IMDb Large Movie Review Dataset. It focuses on traditional machine learning approaches to classify movie reviews as positive or negative.

The project includes:

Data Loading & Cleaning – All reviews are preprocessed to remove HTML tags, URLs, numbers, punctuation, and extra spaces.

Feature Extraction – TF-IDF vectorization is applied to convert text reviews into numerical features.

Model Training & Evaluation – Three classical models are implemented:

Logistic Regression

Multinomial Naive Bayes

Support Vector Machine (LinearSVC)

For each model, the repository outputs Accuracy, F1 Score, and a detailed classification report.

Features:

Fully preprocessed IMDb reviews

TF-IDF feature extraction

Multiple ML models for comparison

Evaluation metrics included

Getting Started:

Download the IMDb dataset: IMDb Large Movie Review Dataset

Set the dataset path in the notebook/code (aclImdb/train and aclImdb/test).

Run the notebook/script sequentially to train models and view results.

Dependencies:

Python 3.x

pandas, numpy, scikit-learn
