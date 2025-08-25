# Diabetes-Prediction-using-Machine-learning

This project is a Diabetes Prediction Model developed using Machine Learning techniques. The goal is to predict whether a person is diabetic based on various health-related features.

# Dataset:

Sourced from Kaggle (link: https://www.kaggle.com/datasets/simaanjali/diabetes-classification-dataset/data )

Contains over 5000 rows and 10 columns

Features include health indicators relevant to diabetes prediction

# Modeling Approach:

1) Tested Random Forest Classifier (RFC) and XGBoost algorithms

2) XGBoost was chosen as the final model due to its higher recall value, making it more effective at identifying diabetic cases

# XGBoost Model Performance:

Accuracy: 80.82%

Precision: 72.42%

Recall: 86.29%

F1 Score: 78.75%

# Technologies & Libraries Used:

Python

Pandas & NumPy for data manipulation

Scikit-learn & XGBoost for machine learning

Matplotlib for visualization

# Key Features:

1) Handles structured medical data efficiently

2) Focus on maximizing recall to minimize false negatives

3) Provides a clear pipeline for training, testing, and evaluating models

# Outcome:

Accurate prediction of diabetes cases with a strong emphasis on recall

Easy to extend for additional features or alternative models
