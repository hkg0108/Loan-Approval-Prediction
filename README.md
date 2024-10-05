# Loan-Approval-Prediction
EDA and Machine Learning

# Overview

This project aims to predict whether a loan will be approved based on various applicant-related features using machine learning techniques.

# Dataset

The dataset contains information about 614 loan applicants, with features such as:

**Loan_ID:** Unique identifier for the loan.

**Gender:** Gender of the applicant.

**Married:** Marital status.

**Dependents:** Number of dependents.

**Education:** Education level (Graduate/Not Graduate).

**Self_Employed:** Employment type.

**ApplicantIncome:** Applicant's income.

**CoapplicantIncome:** Co-applicant's income.

**LoanAmount:** Amount of loan applied for.

**Loan_Amount_Term:** Loan repayment term.

**Credit_History:** Credit history of the applicant (1 = good, 0 = bad).

**Property_Area:** Location of the property (Urban/Rural/Semi-urban).

**Loan_Status:** Loan approval status (Y = Approved, N = Not Approved).

# Steps Performed

**Data Loading:** The dataset is loaded and basic exploration is done using pandas to understand its structure and identify missing values.

**Data Cleaning:** Missing values are handled, and the dataset is prepared for modeling.

**Exploratory Data Analysis (EDA):** Visualizations (e.g., income distribution, loan amount) are created to find patterns and correlations. Analysis of the relationship between various features and loan approval status.

**Modeling:** Various machine learning models are trained, such as RandomForest, Naive Bayes, Decision Tree and KNeighbors. Model performance is evaluated using appropriate metrics like accuracy.

# Results

After training and evaluating the models, the accuracy scores are as follows:

**Random Forest:** 78%

**Naive Bayes:** 82%

**Decision Tree:** 70%

**K-Neighbors:** 79%

**Naive Bayes** achieved the highest accuracy and can be considered the best-performing model for this dataset.

# Conclusion

The Loan Approval Prediction System successfully demonstrates how various classification algorithms can be applied to predict loan approvals. Through data preprocessing, exploratory analysis, and model training, the system provides actionable insights with notable accuracy. This project serves as a foundational step towards more advanced predictive modeling in the financial sector.
