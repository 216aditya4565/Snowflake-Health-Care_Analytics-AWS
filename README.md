# Snowflake-Health-Care_Analytics-AWS

# Project Description

## Business Overview

Healthcare analytics is the process of using data and analytical methods to improve the delivery of healthcare services and patient outcomes. One important area of healthcare analytics is the analysis of patient length of stay (LOS), which refers to the amount of time a patient spends in a healthcare facility.
Length of stay is a critical metric in healthcare, as it can impact patient outcomes, healthcare costs, and hospital capacity. By analyzing patient LOS data, healthcare providers can identify opportunities to improve the delivery of care and reduce costs.
In addition to improving patient outcomes, the analysis of patient LOS can also help healthcare providers to reduce costs. For example, by identifying patients who are at risk of extended LOS, providers can take proactive steps to ensure they receive the care they need in a timely manner.
Overall, the analysis of patient length of stay is a valuable area of healthcare analytics that can help providers to improve patient outcomes and reduce costs. By leveraging data and advanced analytical techniques, healthcare providers can gain a deeper understanding of patient needs and identify opportunities to improve the delivery of care.

## Architecture
![image](https://user-images.githubusercontent.com/31154710/231046153-7796205c-393c-4b41-b475-6874c40e3fce.png)

## Approach

1. Introduction to Snowflake and Snowflake Worksheet
2. EDA in Snowflake
3. Feature Engineering in Snowflake
4. AWS Sagemaker Setup
5. Fetching the data from Snowflake using snowflake-connector-python, and snowflake-sqlalchemy
6. Data Preprocessing
7. Feature Selection
8. Model Building
9. Linear Regression
Random Forest Regression
XGBoost Regression
Model Predictions
Inserting model predictions in Snowflake
Scoring function deployment and scheduling
Sending Status mail

## Aim

1. Data Analysis in Snowflake
2. Build a Machine Learning model to predict the length of stay for patients
3. To schedule the AWS Sagemaker Notebook
4. To perform live data scoring and inserting predictions to Snowflake
5. send status mail

## Data

The training data is present in snowflake for about 230k patients across various regions and hospitals. There are total 19 features available in the data.
The simulation data is available for 71K patients for prediction purpose. 

## Tech Stack

1. Tools: AWS Sagemaker, Snowflake
2. Language: Python
3. Libraries: snowflake-connector-python, snowflake-sqlalchemy, xgboost, pandas, numpy, scikit-learn
