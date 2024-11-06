# Time-Series-Forecasting-for-Revenue-Prediction

Time Series Forecasting for Revenue Prediction
This project demonstrates how to build and compare multiple machine learning models to predict Revenue based on features such as Sales_quantity, Average_cost, and The_average_annual_payroll_of_the_region. Several regression models, including Decision Tree, Support Vector Machine (SVM), Random Forest, and Bi-directional LSTM, are used for this prediction task. This repository also provides visualizations to help evaluate model performance.

**Table of Contents**
Project Overview
Data Description
Technologies Used
Installation
Usage
Models Implemented
Results
Visualizations
Contributing
License

Project Overview
In this project, the goal is to predict the Revenue of a region using a time-series dataset. The dataset includes various features like Sales_quantity, Average_cost, and The_average_annual_payroll_of_the_region over time. We apply multiple machine learning models, preprocess the data, and evaluate each model using R-squared accuracy.

Models used for prediction:

**Decision Tree Regressor
Support Vector Machine (SVM) Regressor
Random Forest Regressor
Bi-directional Long Short Term Memory (BiLSTM)**
The models are trained and evaluated using different sets of features, and their performances are compared.

**Data Description**
The dataset used for this project is a time-series dataset with the following columns:

Period: The time period (monthly).
Revenue: The revenue generated in the given month (target variable).
Sales_quantity: The quantity of items sold in the given month.
Average_cost: The average cost of the items sold.
The_average_annual_payroll_of_the_region: The annual payroll of the region.

Technologies Used
Python: Programming language used to build the models.
pandas: Data manipulation and analysis library.
NumPy: Package for numerical computing.
Scikit-learn: Library for machine learning algorithms (e.g., Decision Tree, SVM, Random Forest).
Keras: Deep learning library for building neural networks (BiLSTM model).
Matplotlib & Seaborn: Libraries for creating visualizations.

**Decision Tree Regressor R-squared: 0.87
SVM Regressor R-squared: 0.85
Random Forest Regressor R-squared: 0.92
BiLSTM R-squared: 0.88**

