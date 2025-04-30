# AQI-Prediction-
A machine learning project to predict Air Quality Index (AQI) using pollutant concentration data.
This project focuses on predicting the Air Quality Index (AQI) using various air pollutant concentrations through machine learning models. It includes steps like data preprocessing, analysis, model building, and evaluation.

Table of Contents:

Introduction

Data Overview

Data Preprocessing

Exploratory Data Analysis (EDA)

Model Implementation

Model Evaluation

Prediction

Conclusion

Future Work

Introduction
The goal of this project is to predict AQI values using data on pollutant levels. Two models—K-Nearest Neighbors (KNN) and Linear Regression—were used to find patterns and make predictions.

Data Overview
The dataset contains daily air quality data for various cities. It includes:

Pollutant levels: PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3

Volatile Organic Compounds (VOCs): Benzene, Toluene, Xylene

Target variables: AQI and AQI category

Initial exploration included checking the first few rows, verifying data types, and identifying missing values.

Data Preprocessing
Missing values were filled using the mean of each column. Data cleaning involved correcting data types, handling outliers, standardizing date formats, and removing duplicates.

Exploratory Data Analysis (EDA)
Visualizations included time series plots, distribution graphs, and correlation heatmaps. These helped identify key pollutants contributing to high AQI and relationships between variables.

Model Implementation
Two models were implemented:

KNN: Used to capture non-linear relationships by averaging AQI values of similar data points.

Linear Regression: Used to model linear relationships between pollutants and AQI.

Model Evaluation
The models were evaluated using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The performance of both models was compared to determine which one gave better predictions.

Prediction
The data was split into training and testing sets. Feature scaling was applied. Each model was trained on the training set and tested on the unseen data. K was chosen for KNN using cross-validation, and coefficients for Linear Regression were calculated using Ordinary Least Squares.

Conclusion
Both models provided useful insights. KNN generally performed better due to its ability to capture non-linear patterns, while Linear Regression was useful for understanding direct relationships.

Future Work
Future improvements could include testing more advanced models, adding more features (e.g., weather data), and applying deep learning for more accurate predictions.
