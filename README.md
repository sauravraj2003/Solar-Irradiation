## Solar Irradiance Prediction Project
ML project for predicting solar radiation using meteorological data and time-based features.

## Overview
This project implements multiple machine learning approaches to predict solar irradiance based on weather conditions and temporal patterns. The model uses features like temperature, humidity, pressure, wind conditions, and time-based variables to forecast solar radiation levels.

## Dataset
The project uses the SolarPrediction.csv dataset containing:

Weather data: Temperature, pressure, humidity, wind direction and speed

Temporal features: Date, time, sunrise/sunset times

Target variable: Solar radiation measurements

##Features
Data preprocessing and feature engineering:

Time-based feature extraction (month, day, hour, minute, second)

Sunrise/sunset time parsing

Data scaling and normalization

##Machine learning models:

XGBoost Regressor with hyperparameter tuning

Neural networks using TensorFlow/Keras

Feature selection using ExtraTrees and SelectKBest

Model evaluation:

Cross-validation with GridSearchCV

Performance metrics: MSE, MAE, R² score
