# Water Potability Analysis

## Overview
Predicted water safety using machine learning on 3,276 water samples with 9 chemical features.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SQLite, Tableau

## Project Steps
- Data Loading & Exploration (3276 rows, 10 columns)
- Data Cleaning (handled missing values in pH, Sulfate, Trihalomethanes using median)
- Exploratory Data Analysis with visualizations
- SQL queries using SQLite to analyze patterns
- Machine Learning using Random Forest Classifier
- Compared 3 models - best accuracy: 67.84%
- Interactive Tableau Dashboard

## Key Findings
- Sulfate and pH are the most important features
- Dataset is imbalanced (1998 unsafe vs 1278 safe samples)
- Similar chemical averages across classes confirmed need for ML

## Model Performance
| Model | Accuracy |
|-------|----------|
| Random Forest (basic) | 67.38% |
| Random Forest (tuned) | 67.84% |
| Gradient Boosting | 65.09% |
