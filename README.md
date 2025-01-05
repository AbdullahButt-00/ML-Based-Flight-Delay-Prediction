# ML-Based-Flight-Delay-Prediction
This repository contains the implementation of an advanced machine learning project focused on analyzing and predicting flight departure delays. The project uses regression, binary classification, and multi-class classification models to predict delay durations and categories based on flight and weather data. It includes data preprocessing, feature engineering, model training, evaluation, and submission for Kaggle competitions.


# Objectives
Data Analysis: Understand patterns and factors contributing to flight delays.
Model Development: Create regression and classification models for predicting delays.

# Kaggle Competitions:
Binary Classification: [Competition Link](https://www.kaggle.com/t/167561bcf3484f0fb0b69e791e3751bf )
Multi-Class Classification: [Competition Link](https://www.kaggle.com/t/840c5a9252f04361985d04cc65ce84b8 )
Regression Analysis: [Competition Link](https://www.kaggle.com/t/36f8c00f74da47c1a2a39613be8c96bb)

# Dataset
Train Data: Includes historical flight and weather data with delay information.
Test Data: Contains flight and weather data without delay values for prediction.
Weather Data: Supplemental data for feature extraction.
Features

#  Data Preprocessing: Handling missing values, formatting time fields, and merging datasets.
#  Feature Engineering: Creating temporal and weather-based features.
#  Visualization: Insights using histograms, line plots, and bar charts.

#  Models
## Binary Classification:
Predict if a flight is on-time or delayed.
Labels: on-time and delayed.

## Multi-Class Classification:
Predict delay categories:
No Delay
Short Delay
Moderate Delay
Long Delay

##  Regression:
Predict exact delay durations in minutes.

##  Submission Format
For all Kaggle competitions, the submission file must be a CSV with the following structure:

## Columns:
#### ID: A unique identifier starting from 1.
#### Delay: Predicted delay values:
#### Binary: on-time or delayed
#### Multi-Class: No Delay, Short Delay, Moderate Delay, Long Delay
#### Regression: Numerical delay values in minutes.
