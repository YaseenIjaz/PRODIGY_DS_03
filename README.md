# PRODIGY_DS_03

## Project Overview
This project aims to predict whether a customer will churn (i.e., leave the service) based on their demographic and behavioral data. We use the Bank Marketing dataset from the UCI Machine Learning Repository and perform exploratory data analysis (EDA), data preprocessing, feature selection, and model building using a Decision Tree classifier.

## Dataset
The dataset contains information about customers, including their demographic details, banking behaviors, and whether they churned or not.

## Features
customer_id: Unique ID for each customer
credit_score: Credit score of the customer
country: Country of the customer (France, Spain, Germany)
gender: Gender of the customer (Male, Female)
age: Age of the customer
tenure: Number of years the customer has been with the bank
balance: Account balance of the customer
products_number: Number of products the customer has
credit_card: Whether the customer has a credit card (1: Yes, 0: No)
active_member: Whether the customer is an active member (1: Yes, 0: No)
estimated_salary: Estimated salary of the customer
churn: Whether the customer churned (1: Yes, 0: No)
## Exploratory Data Analysis (EDA)
We conducted EDA to understand the distribution of features and their relationships with the target variable (churn). Key insights include:

France has the highest number of customers (~5000), followed by Spain and Germany (~2500 each).
There are more male customers (~5500) than female customers (~4500).
Visualizations were created using the Plotly library for interactive plots.
## Data Preprocessing
Encoding Categorical Variables: The country and gender features were encoded using LabelEncoder.
Handling Missing Values: There were no missing values in the dataset.
Splitting Data: The data was split into training and testing sets (70% training, 30% testing).
## Model Building
A Decision Tree classifier was used to predict customer churn.

## Model Training and Evaluation
The model was trained on the training set.
Performance was evaluated using accuracy, confusion matrix, and classification report.
Accuracy achieved: 0.78 

## Dependencies
1. pandas
2. plotly
3. scikit-learn


## Conclusion
This project demonstrates how to predict customer churn using machine learning.
