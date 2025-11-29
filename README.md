# Application of Machine Learning Techniques For the Prediction of Wine Quality (Good vs Bad)

##  Project Overview
This project applies the use of machine learning techniques through a pipeline to predict wine quality using the UCI Wine Quality Dataset (Red & White wine).
The goal was to classify wines as Good (1) or Bad (0) based on their chemical attributes.The workflow covers:
✔️ Dataset introduction & preparation
✔️ Data wrangling & cleaning
✔️ Feature engineering
✔️ Handling categorical variables (e.g., wine type)
✔️ Stratified train/test split
✔️ Data scaling
✔️ Model training (Logistic Regression, KNN, Decision Tree)
✔️ Hyperparameter tuning
✔️ Predictions & demonstration
✔️ Model evaluation (Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix)
✔️ Feature importance analysis

This repository contains all scripts, notebooks, and results used to analyze the study.

## Data Preparation & Wrangling
The key preprocessing steps include:
✔️ Checking for missing values
✔️ Merging red & white datasets
✔️ Creating a wine_type column (0 = red, 1 = white)
✔️ Converting quality to binary quality_label
✔️ Handling class imbalance via stratified sampling

The project utilizes two CSV files located in the root directory:
* `winequality-white.csv`: which cantains 4898 instances and 11 features
* `winequality-red.csv`: which contains 1599 instances and 11 features
The pipeline merges these files to create a comprehensive dataset for training.

##  Codes
To achieve this study,I used jupyter to run my python codes. 

## Machine Learning Models Implemented
The following classifiers were trained and evaluated:
✔️Logistic Regression
Balanced class weights
Scaled numeric features
Good baseline model

✔️K-Nearest Neighbors (KNN)
Tested with multiple values of k
Model performance evaluated after scaling

✔️Decision Tree Classifier
Tuned using GridSearchCV
Feature importance extracted and visualizedLogistic Regression
Balanced class weights
Scaled numeric features
Good baseline model

## Model Training & Testing
A 70/30 train-test split was applied using:
Ensuring the minority and majority classes remain proportionally represented.

## Model Evaluation
Each model was evaluated using: Accuracy, Precision, Recall, F1-score, ROC Curves, AUC Scores, Confusion Matrix
