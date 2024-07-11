# Finance Loan approval Prediction Data

Larissa Fierle, Maria Villacreces, Tomas Echeverria, Milena Cuao

![alt text](https://miro.medium.com/v2/resize:fit:1012/1*tF1iKXHs9qypE_E2fQqytQ.png)

## Overview

This project aims to predict the approval of finance loan applications using various machine learning models. We explore a dataset, apply different models, and evaluate their performance to determine the best approach for accurate predictions.

## Purpose

The purpose of this project is to provide a comprehensive analysis and implementation of machine learning techniques for predicting loan approvals. By understanding the factors that influence loan approval, we can assist financial institutions in making more informed decisions, potentially reducing default rates and improving customer satisfaction.

### Project Structure

•	Imported essential libraries: matplotlib, pandas, numpy, scipy, hvplot.pandas, and sklearn.metrics.

•	Loaded the finance loan dataset from a CSV file into a Pandas DataFrame.

•	Obtained a summary of the DataFrame using info() to understand data types and null values.

•	Combined ApplicantIncome and CoapplicantIncome into a new column, Total_Income.

•	Created income categories by binning ApplicantIncome into 'Very_Low', 'Low', 'Average', 'High', and 'Very_High'.
•	Converted Income_Category to string type for easier manipulation.

•	Renamed columns for better clarity.

•	Checked for and identified missing values using isna().any().

•	Removed duplicate rows using the duplicated() method.

•	Dropped rows with missing values using dropna().

•	Defined feature set X and target variable y for machine learning models.

•	Split the data into training and testing sets.

•	Trained the Logistic Regression model on the training data.

•	Made predictions using the Logistic Regression model on the testing data.

•	Evaluated the Logistic Regression model using a confusion matrix and classification report.

•	Standardized features using StandardScaler.

•	Trained the Decision Tree model on the scaled training data.

•	Made predictions using the Decision Tree model on the scaled testing data.

•	Evaluated the Decision Tree model using a confusion matrix and classification report.

•	Compared the performance of Logistic Regression and Decision Tree models using evaluation metrics.

•	Visualization: tableau.


## Results

 ## -Decision Tree
 
 ![alt text](https://github.com/larissarmourap/Project4-Group1/blob/Larissa_data_analytics/Images/Decision-Tree.png)

 ## -Logistic Regression with dummies
 
  ![alt text](https://github.com/larissarmourap/Project4-Group1/blob/Larissa_data_analytics/Images/Logistic-Regression-model(with%20dummies).png)

## -Logistic Regression without dummies

 ![alt text](https://github.com/larissarmourap/Project4-Group1/blob/Larissa_data_analytics/Images/Logistic-Regression-model(without%20dummies).png)

## -Tableau dashboard
![alt text](https://github.com/larissarmourap/Project4-Group1/blob/Larissa_data_analytics/Images/Loan%20Approval%20Prediction%20dashboard.png)

 tableau link: https://public.tableau.com/app/profile/larissa.fierle/viz/finance_loan/Dashboard1