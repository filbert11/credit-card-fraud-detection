# Credit Card Fraud Detection

## Objectives
The aim of this project is to predict the credit card fradulant transactions

## Dataset
The dataset used in this project is taken from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud.

## Executive Summary
Exploratory Data Analysis (EDA) and Data Pre-processing
Training of Machine learning models
Error Analysis of Machine learning models
Feature Importance

## Conclusion
Based on the three machine learning models trained, neural network is the best model with AUROC score of 0.950 and f1_score macro of 0.90. It means the machine learning model can predict accurately each class with average accuracy of 0.90 (harmonic mean of precision and recall) and the model did descent job with different predicting threshold (based on AUROC score).

By analysing the dataset at which the model failed to predict the fraudulant transactions, we learned that the model failed to predict accurately for data with value between -1 to 1 for V1-3, V5, V7, V9, V10-V13 and V16-V19. Getting more dataset with feature with this range of data may assist the model to learn better as the current dataset is highly imbalance.

The feature importance to determine the output are V19, V27, V17, V7 and V8 for model explainability.
