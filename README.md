# Advanced Predictive Modelling in Healthcare Data Analytics for Early Disease Detection and Proactive Medical Intervention
## Overview
Cardiovascular diseases (CVDs) are a significant global health concern, and early detection plays a pivotal role in improving patient outcomes and reducing healthcare costs. This project aims to develop a predictive model for assessing disease risk by leveraging data mining techniques. The model integrates health metrics and lifestyle data to predict the likelihood of cardiovascular diseases. We utilized machine learning (ML) techniques to analyze a health care dataset aiming to forecast the risk of CAD. The aim is to understand the forecasting power of various Data mining techniques in assessing coronary artery disease risks based on lifestyle and health metrics data. Our approach involved rigorous data preprocessing, cleaning, exploratory data analysis, and implementation of classification models.

## Objectives
Early Detection: Enhance the ability to predict the risk of coronary artery disease using data-driven methodologies.
Model Development: Create a reliable prediction model by applying various data mining techniques.
Improving Patient Outcomes: Ultimately, contribute to improved patient outcomes through early intervention strategies.

## Dataset
The dataset used for this project consists of the following columns:

id: Unique identifier
age: Age of the individual
sex: Gender of the individual
cp:	Chest Pain
trestbps:	Blood pressure of during the admission to hospital
chol:	Cholestrol level
fbs: A blood sugar level after an overnight fast higher than 120 mg/dl
restecg:	Stands for resting electrodiagraphic (a test conducted to understand the rhythm of heart) 
thalch:	Maximum value of heart rate achieved
exang:	Pain in heart due to exercise
ca:	Number of colored major vessels after fluoroscopy
thal: Thallium heart scan
![image](https://github.com/anehra-15/-Predictive-Modelling-for-Early-Disease-Detection-/assets/139734050/63106f44-25bf-463e-b3c2-d626ccadf32a)
num: Target variable indicating the presence of cardiovascular disease

## Challenges Addressed
Missing Data: Handled missing data using mean/mode imputation.
Outliers: Addressed outliers affecting the data quality.
Imbalance Check: Checked for imbalanced classes in the target variable.
Categorical Data Handling: Processed categorical variables for model compatibility using the One-Hot Encoding method.
Irrelevant Columns: Identified and removed columns irrelevant to the predictive model.

## Techniques Applied
Data Cleaning: Addressed missing values, outliers, and irrelevant data.
Data Pre-processing: Prepared the dataset for modeling by handling categorical values and feature engineering.
Exploratory Data Analysis (EDA): Conducted comprehensive EDA to understand data distributions, correlations, and patterns.
Mean/Mode Imputation: Filled missing values using appropriate imputation techniques.

## Models Trained
Random Forest
| RMSE Train | 0.1988771 | 
|------------|-----------|
| RMSE Test  | 0.3472706 |
|------------|-----------|
|    RSQ     | 0.8384405 |
|------------|-----------|


Logistic Regression
Sensitivity: 0.76
Recall: 0.89
F1-Score: 0.82

Decision Tree
Training Accuracy: 76.08%
Testing Accuracy: 83.7%

## Results Summary
Random Forest: Demonstrated high performance with significant predictive capability.
Logistic Regression: Balanced sensitivity and recall scores, indicating its effectiveness.
Decision Tree: Achieved reasonable accuracy and stability.

## Future Improvements
Explore ensemble methods for model enhancement.
Conduct feature importance analysis for better insights.
Experiment with hyperparameter tuning for improved model performance.

## Conclusion
This project showcases the application of various data mining techniques to build predictive models for early detection of cardiovascular diseases. The results indicate promising predictive capabilities, laying the groundwork for further refinement and application in real-world healthcare scenarios.
