# Monitoring of Vegetation Conditions on Wadjuk Noongar Country

## Overview

This project develops machine learning models to classify vegetation condition across land parcels on Wadjuk Noongar Country in Western Australia. The objective is to predict whether an area is:

* Healthy
* Degraded
* At Risk

The project follows a complete data mining workflow including data preparation, feature engineering, model training, hyperparameter tuning, evaluation, and prediction.

## Technologies Used

### Programming Language

* Python 3

### Data Management

* SQLite3 (Database Storage)
* Pandas (Data Manipulation)
* NumPy (Numerical Computing)

### Data Visualisation

* Matplotlib
* Seaborn

### Data Preprocessing

* SimpleImputer (Missing Value Handling)
* OneHotEncoder (Categorical Encoding)
* StandardScaler (Feature Scaling)
* ColumnTransformer
* Scikit-learn Pipelines

### Machine Learning

* k-Nearest Neighbors (k-NN)
* Gaussian Naive Bayes
* Decision Tree Classifier
* Random Forest Classifier

### Model Evaluation & Tuning

* Stratified K-Fold Cross Validation
* Grid Search Cross Validation
* Accuracy Score
* Balanced Accuracy Score
* F1 Score
* Classification Reports
* Confusion Matrices

### Model Persistence

* Joblib

## Key Results

* Random Forest achieved the best validation performance with an accuracy of approximately 90.6%.
* k-NN achieved an accuracy of approximately 86.3%.
* Random Forest and k-NN were selected as the final models for test data prediction.

## Repository Contents

```text
├── Answers_23107667.csv             # Final predictions for test samples
├── Assignment(2).pdf                # Instructions for the assignment
├── Assignment2025S2.sqlite          # Training and test datasets
├── Notebook_23107667.py             # Data preparation and modelling
├── Report_23107667.pdf              # Assignment report
└── README.md                        # Project documentation
```

## Author

Abu Fatah Mohammed Faisal

Curtin University

Master of Precitive Analytics

## Disclaimer

This project was completed for academic purposes as part of a data mining assignment. The dataset is simulated but inspired by real-world environmental monitoring scenarios.
