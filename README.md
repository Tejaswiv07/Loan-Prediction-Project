# Loan Prediction Project

## Problem Statement

Dream Housing Finance wants to automate the loan eligibility process based on customer details such as gender, marital status, education, income, loan amount, credit history, and property area.

---

## Objective

The objective of this project is to analyze loan application data, perform data preprocessing, and build a machine learning model to predict loan approval status.

The project includes:

- Data Ingestion
- Data Understanding
- Data Exploration
- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Encoding
- Feature Scaling
- Model Building
- Model Evaluation

---

## Dataset Features

The dataset contains applicant details including:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib
- Seaborn

---

## Project Workflow

1. Data Ingestion
2. Data Understanding
3. Data Exploration
4. Missing Value Treatment
5. Data Cleaning
6. Feature Engineering
7. Encoding Categorical Features
8. Feature Scaling
9. Train-Test Split
10. Model Building
11. Model Evaluation

---

## Data Preprocessing

The following preprocessing steps were performed:

- Identified and treated missing values.
- Handled categorical variables using encoding techniques.
- Removed unnecessary features that do not contribute to model learning.
- Applied feature scaling to numerical variables.

---

## Feature Engineering

Created new features to improve model performance:

### Total Income

Combined applicant income and co-applicant income:

- Total_Income = ApplicantIncome + CoapplicantIncome

### Loan-to-Income Ratio

Created a feature to understand the applicant's loan burden:

- Loan_to_Income = LoanAmount / Total_Income

---

## Machine Learning Model

### Logistic Regression

A Logistic Regression classification model was implemented to predict whether a loan application will be approved or rejected.

### Model Performance

Accuracy:

- 86%

### Model Evaluation Metrics

The model was evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1-score

---

## Key Insights

- Credit History is one of the most important factors influencing loan approval decisions.

- Applicant and co-applicant income together provide better information about the applicant's financial strength.

- Loan-to-Income ratio helps understand the repayment burden and financial capability of applicants.

- Missing values were handled appropriately based on the data type of each feature.

- Feature scaling improved model performance by standardizing numerical features.

- Removing irrelevant features helped reduce noise and improved model learning.

---

## Future Improvements

- Compare Logistic Regression performance with other classification algorithms such as Decision Tree, Random Forest, and XGBoost.

- Perform hyperparameter tuning to improve model performance.

- Deploy the trained model using a web application framework such as Streamlit or Flask.

---

## Author

Tejaswi
