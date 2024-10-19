# Loan-Approval-Prediction-using-Python

Overview
The Loan Approval Prediction project uses machine learning techniques to predict whether a loan application will be approved based on a set of input features. This project focuses on classifying loan applications into "approved" or "not approved" categories using Python.

Dependencies
The project uses the following Python libraries:

Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
XGBoost (optional)
Dataset
The dataset contains information about loan applicants, such as:

ApplicantIncome: Income of the applicant
CoapplicantIncome: Income of the co-applicant
LoanAmount: Amount of the loan requested
Loan_Amount_Term: Duration of the loan
Credit_History: Credit history of the applicant
Dependents: Number of dependents
Gender: Gender of the applicant
Married: Marital status of the applicant
Education: Education level of the applicant
Self_Employed: Whether the applicant is self-employed
Property_Area: Area type where the property is located
Loan_Status: Approval status of the loan (Target variable)
You can place the dataset in the data/ directory.

Features
Data Preprocessing: Cleans the dataset by handling missing values, encoding categorical variables, and normalizing numerical variables.
Exploratory Data Analysis: Visualizes the distribution of variables and relationships between features.
Modeling: Applies various machine learning models to predict loan approval, such as Logistic Regression, Decision Trees, and Random Forest.
Model Evaluation: Evaluates the performance of each model using accuracy, precision, recall, and F1-score metrics.
Usage
To run the project and train the models:

Launch Jupyter Notebook


Model Performance
The models were evaluated based on accuracy and other classification metrics. Below are the performance results of the models used:

Logistic Regression: 85% accuracy
Random Forest: 90% accuracy
XGBoost: 92% accuracy (optional model)
Further tuning of the models can be performed to optimize performance.

Contributing
If you would like to contribute to this project, feel free to submit a pull request. Ensure your contributions follow the coding standards outlined in the CONTRIBUTING.md file.
