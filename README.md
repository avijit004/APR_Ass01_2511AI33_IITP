Customer Churn Prediction – Telco Dataset
Overview
This project predicts customer churn for a telecommunications company using supervised machine learning, specifically Logistic Regression. The analysis is based on the "WA_Fn-UseC_-Telco-Customer-Churn.csv" dataset, focusing on data preprocessing, exploratory analysis, and classification modeling to identify factors impacting customer retention.

Dataset
Source: WA_Fn-UseC_-Telco-Customer-Churn.csv

Rows: 7,043

Columns: 21

Target: Churn (Yes/No – indicates if a customer left)

Features: Demographics (gender, SeniorCitizen, Partner, Dependents), usage patterns (tenure, phone service, multiple lines, internet type, services), account info (MonthlyCharges, TotalCharges, contract type, payment method).

Project Structure
text
├── main.ipynb                  # Jupyter notebook with complete analysis & modeling
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
├── README.md                   # Project documentation (this file)
Key Steps
1. Data Exploration and Visualization
Summary statistics and info for null values and data types

Visualizations (pie charts, bar plots) to explore churn distribution and feature relationships

2. Data Preprocessing
Handling missing values (TotalCharges as numeric, fill NaN with median)

Label encoding of categorical variables (e.g., gender, payment method, services)

Feature scaling using StandardScaler

Conversion of target Churn to binary (0 = No, 1 = Yes)

3. Model Building
Data split: 75% train, 25% test using train_test_split

Model: Logistic Regression (sklearn.linear_model.LogisticRegression)

Model training on preprocessed features

4. Evaluation
Evaluation metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-score, ROC-AUC, classification report

Model interpretation with feature significance

Results
Provides baseline churn prediction performance using logistic regression

Demonstrates which customer/account attributes correlate strongly with churn

Visualizes key patterns and model performance

Requirements
Python 3.x

pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, missingno

Install them with:

bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly missingno
How to Run
Clone the repository or download the files.

Place WA_Fn-UseC_-Telco-Customer-Churn.csv in the project directory.

Open and run main.ipynb in Jupyter Notebook or JupyterLab.

Run all cells to view preprocessing, model training, evaluation, and visualizations.

References:
Original dataset: IBM Telco Customer Churn on Kaggle
scikit-learn documentation: https://scikit-learn.org/stable/
