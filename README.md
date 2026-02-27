# Heart-Disease-Classification-project
An end-to-end machine learning solution for heart disease prediction using supervised classification techniques, including data preprocessing, exploratory data analysis, model building, and performance evaluation.
❤️ Heart Disease Prediction using Decision Tree
📌 Project Overview

This project focuses on building a machine learning classification model to predict the presence of heart disease based on clinical and medical attributes. The model uses a Decision Tree Classifier with hyperparameter tuning to improve prediction performance.

The objective is to assist in early detection of cardiovascular disease using data-driven insights.

🎯 Problem Statement

Heart disease remains one of the leading causes of death globally. Early prediction based on patient health metrics can significantly improve diagnosis and treatment planning.

This project aims to classify patients into:

0 → No Heart Disease

1 → Heart Disease

📊 Dataset Information

303 patient records

14 attributes including:

Age

Sex

Chest pain type (cp)

Resting blood pressure (trestbps)

Cholesterol (chol)

Fasting blood sugar (fbs)

Resting ECG (restecg)

Maximum heart rate (thalach)

Exercise induced angina (exang)

ST depression (oldpeak)

Slope of peak exercise ST segment

Number of major vessels (ca)

Thalassemia (thal)

Target variable (0/1)

🔍 Exploratory Data Analysis (EDA)

Checked dataset structure and summary statistics

Verified missing values

Removed duplicate records

Visualized outliers using boxplots

Analyzed feature distributions

🤖 Model Development
Algorithm Used:

Decision Tree Classifier

Hyperparameter Tuning:

Performed using GridSearchCV

Applied cross-validation to identify optimal parameters

Selected best model based on cross-validation performance

📈 Model Evaluation

The model was evaluated using:

Accuracy Score

Confusion Matrix

Precision

Recall

F1-Score

ROC-AUC Score

Performance metrics were calculated on the test dataset to ensure generalization.

📊 Feature Importance

Feature importance was extracted from the trained Decision Tree model to understand which medical attributes contribute most to heart disease prediction.

This improves model interpretability and transparency.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

🚀 Project Workflow

Data Loading

Data Cleaning

Exploratory Data Analysis

Train-Test Split

Model Training

Hyperparameter Tuning

Model Evaluation

Feature Importance Analysis
