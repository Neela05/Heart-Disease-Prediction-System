# Heart-Disease-Prediction-System

This project uses machine learning techniques to predict the likelihood of heart disease based on patient health information. The goal is to help identify individuals at risk and support early diagnosis.

**Dataset**

Source: Kaggle Heart Failure Prediction Dataset
Records: 918, 
Features: 11, 
Target Variable: Heart Disease

The dataset contains information such as age, sex, chest pain type, cholesterol level, blood pressure, heart rate, and other health-related attributes.

**Objectives**

Predict whether a patient is likely to have heart disease.

Identify the most important factors affecting heart disease risk.

Compare the performance of different machine learning models.

Perform data analysis and visualization to understand the dataset.

Project Workflow

**1. Data Preprocessing**

Checked for missing and duplicate values.
Removed outliers using the IQR method.
Converted categorical data into numerical format using One-Hot Encoding.
Scaled features for better model performance.

**2. Exploratory Data Analysis (EDA)**

Created various visualizations to understand the data, including:

Age distribution, 
Cholesterol analysis, 
Chest pain type distribution, 
Relationship between age and heart rate, 
Gender-based comparisons, 

**3. Machine Learning Models,** 

The following classifiers were implemented:

Support Vector Machine (SVM), 
Gradient Boosting Classifier, 
Random Forest Classifier, 
K-Nearest Neighbors (KNN), 
Logistic Regression, 
Results, 
Model	Cross-Validation Accuracy, 
Logistic Regression	86.70%, 
KNN	86.45%, 
SVM	85.72%, 
Gradient Boosting	85.48%, 
Random Forest	83.75%, 

Best Performing Model: **Logistic Regression**

Technologies Used :
Python,
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-Learn,
Jupyter Notebook
