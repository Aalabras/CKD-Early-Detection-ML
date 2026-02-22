Early Detection of Chronic Kidney Disease Using Machine Learning

📌 Project Overview

This project applies machine learning algorithms to predict Chronic Kidney Disease (CKD) using clinical and laboratory features.

CKD is often asymptomatic in early stages, making predictive modeling a valuable tool for early detection and clinical decision support.

📊 Dataset

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

⚙️ Methodology

Data cleaning and preprocessing

Handling missing values (median & most frequent imputation)

Encoding categorical variables

Exploratory Data Analysis (EDA)

Correlation analysis

Model training and evaluation

Hyperparameter tuning using GridSearchCV

10-fold Cross-validation

🤖 Models Implemented

Logistic Regression

Logistic Regression (Balanced)

Decision Tree

Random Forest

📈 Results
Model	Accuracy
Logistic Regression	1.0000
Logistic Regression Balanced	1.0000
Decision Tree	0.9625
Random Forest	1.0000

10-Fold Cross-Validation:

Mean Accuracy: 0.9906

Standard Deviation: 0.0200

📊 Visualizations
Feature Correlation Matrix

Model Comparison

Confusion Matrix

🔍 Key Predictors

The most correlated features with CKD:

Hypertension

Diabetes Mellitus

Albumin Level

Blood Glucose

Pedal Edema

⚠ Limitations

Dataset size is relatively small

Results are based on a single public dataset

No external validation dataset

👨‍💻 Author

Abdullah Alabras
