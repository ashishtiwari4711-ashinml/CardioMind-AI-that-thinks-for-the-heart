🫀 Predicting Heart Disease Risk Using Machine Learning
📖 Overview

Heart disease is one of the leading causes of death worldwide. Early detection can save lives and reduce healthcare costs.
This project builds an end-to-end machine learning pipeline to predict the risk of heart disease using clinical and demographic data such as age, blood pressure, cholesterol, and lifestyle factors.

🎯 Objective

To create an ML model that accurately predicts whether a person is at risk of heart disease.
The project demonstrates the full data-science workflow — from data preprocessing and feature engineering to model training, evaluation, and interpretation.

⚙️ Features

Complete data-science pipeline (from raw data to prediction)

Exploratory Data Analysis (EDA) and visualizations

Feature selection and correlation analysis

Comparison of multiple ML algorithms (Logistic Regression, Random Forest, K-Nearest Neighbours, etc.)

Evaluation metrics (Accuracy, Precision, Recall, F1, ROC-AUC)


🧠 Dataset

Source:  https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Attributes: Age, Sex, Blood Pressure, Cholesterol, Chest Pain Type, Heart Rate, etc.

Target Variable: target → 1 = heart disease present, 0 = no heart disease

🛠️ Tech Stack
Category	Tools / Libraries
Language	Python 3.x
Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Modeling	Scikit-learn,
Evaluation	Scikit-learn Metrics

🔍 Methodology

Data Collection — Load and inspect the dataset

Data Cleaning — Handle missing values, encode categories, normalize features

Exploratory Data Analysis (EDA) — Understand feature relationships and correlations

Feature Engineering — Select or create meaningful variables

Model Training — Train multiple classifiers

Model Evaluation — Use metrics and ROC curve to compare models



📊 Results

Best model achieved (K- Nearest Neighbours) 92% accuracy and 97% ROC-AUC

Most significant predictors: Age, Cholesterol, RestingBP, MaxHR, and ChestPainType

Insights suggest early lifestyle and medical interventions can greatly reduce heart disease risk
