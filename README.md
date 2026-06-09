Loan Default Prediction and Risk Analysis
Project Overview

The Loan Default Prediction and Risk Analysis project focuses on analyzing loan applicant data to identify potential loan defaulters and assess borrower risk levels. The project uses data analysis, visualization, and machine learning techniques to understand factors influencing loan repayment behavior and predict loan-related trends.

Objective

The main objectives of this project are:

Analyze loan applicant information.
Identify factors contributing to loan defaults.
Classify borrowers into risk categories.
Perform exploratory data analysis (EDA).
Build a machine learning model for prediction.
Generate insights for financial decision-making.
Dataset Description

The dataset contains information about loan applicants, including:

Feature	Description
loan_amnt	Loan amount requested by the borrower
term	Loan repayment period (36 or 60 months)
int_rate	Interest rate applied to the loan
annual_inc	Annual income of the borrower
emp_length	Employment experience in years
home_ownership	Housing status (Rent, Own, Mortgage)
purpose	Purpose of the loan
grade	Credit grade assigned to the borrower
loan_status	Loan repayment status
Risk	Risk category assigned based on income
Project Workflow
1. Data Generation

A synthetic loan dataset is generated using NumPy to simulate real-world loan application records.

2. Data Exploration

The project examines:

Dataset structure
Missing values
Statistical summaries
Data distributions
3. Loan Default Analysis

Loan applicants are classified as:

Fully Paid
Default

The analysis helps identify patterns among defaulters and non-defaulters.

4. Risk Classification

Borrowers are categorized into:

High Risk
Annual income below ₹40,000
Medium Risk
Annual income between ₹40,000 and ₹80,000
Low Risk
Annual income above ₹80,000

This classification helps financial institutions assess lending risk.

5. Group-Based Analysis

The project analyzes:

Income vs Loan Status
Loan Purpose vs Default Rate
Risk Category Distribution

These analyses help identify borrower behavior and default trends.

6. Data Preprocessing

Categorical variables are converted into numerical format to prepare the data for machine learning algorithms.

7. Machine Learning Model

A Linear Regression model is implemented using Scikit-Learn.

Input Features
Annual Income
Interest Rate
Loan Term
Target Variable
Loan Amount

The model is trained and evaluated using the R² Score metric.

Visualizations Included
Loan Status Distribution

Displays the number of fully paid and defaulted loans.

Annual Income Distribution

Shows income patterns among borrowers.

Loan Amount Distribution

Illustrates the spread of loan amounts.

Income vs Loan Amount

Analyzes the relationship between borrower income and loan amount.

Interest Rate vs Loan Amount

Examines how interest rates vary with loan amounts.

Loan Amount Box Plot

Detects outliers in loan amounts.

Correlation Heatmap

Shows relationships between numerical variables.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook / Google Colab
Machine Learning Techniques
Linear Regression

Used to predict loan amounts based on:

Income
Interest Rate
Loan Term
Model Evaluation

The model performance is measured using:

R² Score
Key Insights
Borrowers with lower annual income have a higher probability of default.
Higher interest rates are associated with increased default risk.
Income level significantly influences loan-related decisions.
Risk categorization helps identify potential defaulters.
Loan purpose can affect repayment behavior.
Expected Outcomes

After completing this project, users can:

Understand factors affecting loan defaults.
Evaluate borrower risk levels.
Analyze financial data effectively.
Build predictive models using machine learning.
Support lending decisions with data-driven insights.
Output

The project generates:

Statistical summaries
Risk classifications
Data visualizations
Loan default analysis reports
Machine learning performance metrics
CSV dataset file (loan_default_prediction.csv)
Conclusion

This project demonstrates how data analytics and machine learning can be applied in the banking and finance sector to assess borrower risk and analyze loan repayment behavior. The insights generated can help financial institutions make better lending decisions, reduce default risk, and improve overall loan management strategies.
<img width="529" height="445" alt="image" src="https://github.com/user-attachments/assets/3ef29fd3-dd6d-4faa-a1a4-c19cb279deae" />
<img width="545" height="393" alt="image" src="https://github.com/user-attachments/assets/b18f4ef6-a726-45e1-946b-1077c56a67ed" />
<img width="521" height="393" alt="image" src="https://github.com/user-attachments/assets/693a183a-5c0c-49cf-b75b-db0d13a5bdd1" />
<img width="563" height="393" alt="image" src="https://github.com/user-attachments/assets/53e0e59a-6844-4a39-b93f-c2dd5c904e72" />
<img width="558" height="393" alt="image" src="https://github.com/user-attachments/assets/f7b06d96-dd63-43c4-9075-5a379c49eedc" />
<img width="558" height="355" alt="image" src="https://github.com/user-attachments/assets/7f1c56be-3beb-41de-8dce-3b6b77c5923b" />
<img width="729" height="631" alt="image" src="https://github.com/user-attachments/assets/3aa753aa-2283-4a18-8634-fd6b455a5505" />







