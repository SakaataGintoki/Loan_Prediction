# Loan_Prediction

# Overview
Loan prediction involves using historical data to build a model that predicts whether a loan application will be approved or denied. This process typically includes collecting and preprocessing data, selecting or engineering features, choosing and training a predictive model, evaluating its performance, and maintaining its accuracy over time. The goal is to assist financial institutions in making informed decisions about extending credit while managing the risk of loan default.

# Problem
The Problem is to predict whether the person should be given loan or not based on his salary,credit score,gender,age,and many more

# Dataset
loan_id 
no_of_dependents- Number of Dependents of the Applicant
education- Education of the Applicant
self_employed- Employment Status of the Applicant
income_annum- Annual Income of the Applicant
loan_amount-Loan Amount which is taken by applicant
loan_term- Loan Term in Years
cibil_score- Credit Score of applicant
residential_assets_value- represents the value of residential assets owned by the applicant
commercial_assets_value- it indicates the value of commercial assets owned by the applicant
luxury_assets_value- Luxury assets can include high-end items such as luxury cars, yachts, jewelry, or other expensive possessions.
bank_asset_value- It may include savings accounts, investment portfolios, or other financial assets.	
loan_status- it indicates the status of the loan application. It typically has two possible values: "approved" or "denied,"

# Libraries
- Pandas: To Process the data as the data was in CSV format.
- Matplotlib and Seaborn : It is commonly used for data visualization and creating various types of charts and plots.
- Scikit-learn: Scikit-Learn, also known as Sklearn is a python library to implement machine learning models and statistical modelling.

# EDA Pre-Processing
To perform EDA is one of the most important thing to do before applying any Machine Learning Model .It make sures that data is been validate and no outliers are present
Eda and pre procession steps -
- handling the missing value
- converting categorial to numeric
- feature scaling(Standard scaling)
- Handling outliers (value more than IQR is outliers)
- Train test split

# Machine Learning Model
Based on Independent Variables the problem is Multi Classification the best 3 Algorithm will be (i.e)
- Logistic Regression
- Support Vector Machine
- Random Forest

# Logistic Regression
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/634d9f02-e154-4a30-9756-040a244d5c8c)

# Evaluation
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/0b462a70-ce75-48b8-81b5-76a7fe854c70)


# Support Vector Machine with Standard scalar
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/b73d3ff6-1142-44c8-8cb9-32b3588b841c)
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/b142a007-9b5b-46ed-8778-3e483263342b)

# Evaluation
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/7e57cc53-b511-43ed-81eb-cd751a6fcb17)

# Random Forest Algorithm
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/40557ffd-3c9b-454e-b99e-9ad6010d8059)
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/811f43df-96f4-47fa-a020-97c6a6d1289a)

# Evaluation
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/24a3fbdf-6f82-49b7-baa9-d9b14cb1ab8a)

# Results and Conclusion
![image](https://github.com/SakaataGintoki/Loan_Prediction/assets/107795560/38cebd7a-d7b7-4647-a82e-b17cc939a457)



