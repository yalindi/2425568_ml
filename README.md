# Telco Customer Churn ML Project
Machine Learning Coursework – 2024/2025: Binary Classification using Decision Tree & Neural Network Models

# Project Overview
This project addresses a binary classification task to predict customer churn using the publicly available Telco Customer Churn dataset.
The aim is to build, analyse, and evaluate two machine learning models:
* Decision Tree Classifier
* Neural Network Classifier

The project includes full Exploratory Data Analysis (EDA), data preprocessing, feature engineering, model development, hyperparameter tuning, and ethical considerations.

**All implementation is governed through Git version control.**

# Evaluation

Summary of Results

| Model |	Accuracy |	Precision |	Recall |	F1 | AUC |
| :------- | :------: | -------: | -------: | -------: | -------: |
| Decision Tree |	0.76 | 0.54	| 0.80 | 0.64 | 0.84 |
| Neural Network | 0.79	| 0.61 | 0.67	|0.64 | 0.85 |
| Neural Network (Optimised Threshold) | 0.74	| 0.51 | 0.84	|0.64	| 0.85 |

Insights:

* The Neural Network achieved the best overall performance.
* The Decision Tree provides greater interpretability.
* Tuned threshold improved recall for churners—useful for retaining customers.

# Dataset Source
Telco Customer Churn Dataset

Available publicly on Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
