# Customer Churn Prediction

This project is focused on predicting customer churn using a dataset from a telecommunications company. The prediction model is built using TensorFlow and artificial neural networks (ANN).

## Project Overview

The primary objective of this project is to build a predictive model that can classify whether a customer is likely to churn (leave the service) or not. The model is trained using a dataset that includes various customer attributes such as tenure, service usage, billing details, and more.

## Dataset

The dataset, `Customer-Churn.csv`, contains the following key columns:

- `customerID`: Unique identifier for each customer.
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`: Demographic information.
- `tenure`: Number of months the customer has stayed with the company.
- `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`: Service details.
- `Contract`, `PaperlessBilling`, `PaymentMethod`: Contract and payment information.
- `MonthlyCharges`, `TotalCharges`: Financial details.
- `Churn`: Target variable indicating if the customer has churned (Yes) or not (No).
