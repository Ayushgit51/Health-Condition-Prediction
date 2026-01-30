# Health Condition Prediction

## Project Overview

This project focuses on predicting health conditions using supervised machine learning techniques. Multiple classification models were trained and evaluated to identify the most effective approach for accurate health condition prediction.

## Problem Statement

The objective of this project is to build a reliable machine learning model that can classify health conditions based on input features, supporting better analysis and early decision-making.

## Machine Learning Models Used

The following models were implemented and compared:

- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Random Forest Classifier  
- AdaBoost Classifier  

All models were trained and evaluated on the same dataset to ensure fair comparison.

## Evaluation Metrics

The models were evaluated using the following metrics:

- Accuracy  
- Recall  

These metrics measure overall correctness and the model’s ability to correctly identify positive health conditions.

## Best Performing Model

The **AdaBoost Classifier** achieved the highest performance among all evaluated models With:
Accuracy of Model: 95.07853403141361 %
Recall of Model: 94.85148514851485 %

### Model Configuration

AdaBoost was implemented using a Decision Tree as the base estimator with the following configuration:

base_model_dts = DecisionTreeClassifier(
    max_depth=12,
    min_samples_split=15
)

### Author
Ayush Kumar
Data Scientist and AI/ML aspirant 
