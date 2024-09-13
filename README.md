# Student Performance Prediction

## Overview
This project focuses on predicting student performance based on various features related to their background and school environment. The model aims to identify the factors that significantly impact academic achievements and provide insights that could guide educational strategies.

## Contents
- [1. Dataset Import](#1-dataset-import)
- [2. Data Exploration](#2-data-exploration)
- [3. Data Cleaning](#3-data-cleaning)
- [4. Data Preparation](#4-data-preparation)
- [5. Benchmark Model](#5-benchmark-model)
- [6. Model Training](#6-model-training)
- [7. Model Tuning](#7-model-tuning)
- [8. Performance Results](#8-performance-results)
- [9. Conclusions and Next Steps](#9-conclusions-and-next-steps)

## 1. Dataset Import
Data is sourced from a comprehensive dataset on student performance, focusing on demographic, parental, and school-related features.

## 2. Data Exploration
Initial data exploration is conducted to understand distributions and relationships within the data, utilizing histograms and value counts to summarize key attributes.

## 3. Data Cleaning
Data cleaning steps include handling missing values and outliers to ensure data quality and reliability for the modeling process.

## 4. Data Preparation
Data is prepared for modeling through encoding categorical variables and scaling/normalizing where necessary.

## 5. Benchmark Model
The benchmark model involves simple regression techniques to set a baseline for comparison.

### 5.1. Train-Test Split
Data is split into training and testing sets to validate the model's performance effectively.

### 5.2. Fitting a Model to Data
A simple linear regression model is first applied to establish a baseline for performance metrics.

## 6. Model Training
Advanced models including Random Forest and Gradient Boosting are trained to compare against the benchmark.

### 6.1. Random Forest
Random Forest regressor is applied with default parameters to assess its base performance.

### 6.2. Gradient Boost
Gradient Boosting techniques are employed, focusing on boosting weak learners through iterative corrections of errors.

## 7. Tuning
Model parameters are finely tuned to optimize performance, utilizing grid search techniques.

### 7.1. Best Parameters
Best parameters are identified based on grid search results, focusing on minimizing errors and maximizing the R-squared value.

## 8. Performance Results
The final models are evaluated based on several metrics including MAE, RMSE, and R2. A detailed comparison table is provided:

| Algorithm               | MAE   | RMSE  | R2    |
|-------------------------|-------|-------|-------|
| Benchmark Model         | 1.504 | 2.206 | 0.573 |
| Random Forest           | 1.139 | 1.579 | 0.781 |
| Gradient Boosting       | 0.995 | 1.400 | 0.828 |
| Tuned Gradient Boosting | 1.014 | 1.407 | 0.826 |

## 9. Conclusions and Next Steps
The analysis provides insights into the key factors influencing student performance and suggests further areas of research, such as deeper dives into individual feature impacts and exploring ensemble techniques.

## Contributions
Contributions to this project are welcome, especially in the areas of feature engineering and advanced modeling techniques.
