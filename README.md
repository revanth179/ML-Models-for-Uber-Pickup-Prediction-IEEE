**An Ensemble Machine Learning Model for Predictive Analysis of Uber Pickups**

**Published in IEEE APCIT 2024 | Machine Learning | Urban Mobility Analytics**

**Paper Link** : https://ieeexplore.ieee.org/document/10673705

This repository contains the research work and IEEE publication focused on predicting Uber pickup demand using advanced machine learning and ensemble learning techniques.
The study evaluates multiple ML models to identify the most accurate predictor for forecasting Uber ride counts based on historical pickup data.

**1. Overview**

Accurately predicting Uber ride demand helps improve fleet distribution, reduce waiting times, and optimize taxi availability.
This research applies predictive analytics on Uber's dataset and compares different machine learning models.

The results proved that XGBoost outperformed all other algorithms with the highest accuracy and lowest error.

**2. Key Features of the Study**

✔ Preprocessing and cleaning of Uber pickup dataset

✔ Feature engineering (PCA-based feature extraction)

✔ Comparison of ML models:

XGBoost

Gradient Boosting

AdaBoost

Bagging (Extra Trees)

KNN

✔ Evaluation metrics used:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

✔ Visualization of data trends using histograms, heatmaps, and time-series graphs

**3. Dataset**

Dataset used: Uber pickups dataset from Kaggle
Contains:

10,000 instances

Date, Month, Day, Hour, Weekday

Ride count (target variable)

**4. Best Performing Model**

After evaluating multiple models:

**XGBoost — Best Accuracy**

R² Score: 0.99

MAE: 6.629

MSE: 0.53

This makes XGBoost the most suitable model for predicting Uber ride demand.

**6. Experimental Results**

| Model                     | R² Score |       MAE |      MSE |      RMSE |
| ------------------------- | -------: | --------: | -------: | --------: |
| **XGBoost**               | **0.99** | **6.629** | **0.53** | **0.728** |
| Gradient Boosting         |     0.96 |     12.45 |     1.89 |     1.374 |
| AdaBoost                  |     0.95 |     13.02 |     2.11 |     1.452 |
| Bagging (Extra Trees)     |     0.92 |     15.78 |     3.02 |     1.737 |
| K-Nearest Neighbors (KNN) |     0.89 |     18.11 |     4.21 |     2.052 |


**5. Technologies Used**

Python

Pandas

NumPy

Scikit-Learn

XGBoost

PCA (Dimensionality reduction)

Matplotlib & Seaborn
