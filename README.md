Telco Customer Churn Analysis
Project Overview

This project analyzes the Telco Customer Churn dataset to explore patterns and factors influencing customer churn.
The goal is to both understand customer behavior (EDA) and predict churn using machine learning models.


<b> Dataset </b>

Source: Telco Customer Churn dataset

Includes customer information such as:

Demographics

Contract type

Payment method

Tenure

Monthly and total charges

Churn (Yes/No)


Exploratory Data Analysis (EDA)

The analysis focused on identifying patterns in customer churn using visualizations and summary statistics.


Key Findings

Customers on month-to-month contracts churn the most

Short-tenure customers are more likely to leave

Certain payment methods (e.g., Electronic Check) show higher churn

Higher monthly charges are associated with increased churn


Machine Learning

Two models were implemented to predict customer churn:

Logistic Regression – baseline, interpretable model

Random Forest – more advanced model capturing complex patterns


Results

Random Forest achieved better performance than Logistic Regression

Churn is influenced by multiple interacting factors, not just one variable


Feature Importance

The most important features identified:

Contract type

Tenure

Monthly charges

⚠️ CustomerID was removed before modeling as it is a unique identifier and does not carry predictive value.


Project Structure

telco_churn_analysis.ipynb – main notebook with EDA and ML

telco_churn.csv –  ([data set](https://www.kaggle.com/datasets/dhrubangtalukdar/telco-customer-churn-data))


How to Run

Clone the repository:

git clone https://github.com/USERNAME/customer-churn-analysis.git

Open the notebook in:

Google Colab

Jupyter Notebook

Run all cells to reproduce the analysis and models.


Technologies Used

Python

Pandas

Seaborn

Matplotlib

Scikit-learn


Conclusion

This project demonstrates how combining exploratory data analysis with machine learning can provide deeper insights into customer churn and improve predictive capabilities.
