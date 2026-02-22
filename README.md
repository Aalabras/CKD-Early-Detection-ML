Early Detection of Chronic Kidney Disease Using Machine Learning


1- Project Overview

This project applies machine learning algorithms to predict Chronic Kidney Disease (CKD) using clinical and laboratory features.

CKD is often asymptomatic in early stages, making predictive modeling a valuable tool for early detection and clinical decision support.

2- Dataset

Source: Chronic Kidney Disease dataset from Kaggle

400 patient records

25 features + binary classification target

Features include demographic, clinical, and laboratory variables such as:

Age

Blood Pressure

Albumin

Serum Creatinine

Hemoglobin

Hypertension

Diabetes Mellitus

3- Methodology

Data cleaning and preprocessing

Handling missing values (median & most frequent imputation)

Encoding categorical variables

Exploratory Data Analysis (EDA)

Correlation analysis

Model training and evaluation

Hyperparameter tuning using GridSearchCV

10-fold Cross-validation

4- Models Implemented

Logistic Regression

Logistic Regression (Balanced)

Decision Tree

Random Forest

5- Results
Model	Accuracy
Logistic Regression	1.0000
Logistic Regression Balanced	1.0000
Decision Tree	0.9625
Random Forest	1.0000

10-Fold Cross-Validation:

Mean Accuracy: 0.9906

Standard Deviation: 0.0200

6- Visualizations
Feature Correlation Matrix

Model Comparison

Confusion Matrix

7- Key Predictors

The most correlated features with CKD:

Hypertension

Diabetes Mellitus

Albumin Level

Blood Glucose

Pedal Edema

8- Limitations

Dataset size is relatively small

Results are based on a single public dataset

No external validation dataset

9- Author

Abdullah Alabras
