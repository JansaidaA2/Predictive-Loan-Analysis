# Predictive-Loan-Analysis


# 📊 Predictive Analysis for Loan Defaults  

## 🔍 Project Overview  
This project aims to analyze loan applicants' data to identify patterns indicating the likelihood of default. By leveraging *Exploratory Data Analysis (EDA) and Predictive Modeling, we can help financial institutions make **data-driven loan approval decisions*.  

## 🎯 Business Objective  
Financial institutions face challenges in approving loans, as *denying creditworthy applicants leads to lost revenue, while **approving risky applicants leads to financial loss*.  
This project helps *classify loan applicants* into *defaulters vs. repayers*, reducing risks associated with loan disbursement.  

## 🏗 Workflow  
1. *Data Collection*: Used datasets like application_data.csv and previous_application.csv.  
2. *Data Cleaning*: Handled missing values, outliers, and irrelevant columns.  
3. *Exploratory Data Analysis (EDA)*:
   - Distribution of *income, credit amount, age, employment history*  
   - Identifying correlations between variables  
   - Detecting missing values and trends  
4. *Feature Engineering*:
   - Created *income ranges, credit bins, age groups, employment years*  
   - Converted categorical features for modeling  
5. *Predictive Modeling* (Optional Future Step):  
   - Train machine learning models like *Logistic Regression, Random Forest, XGBoost*  

## Dataset Description  
- **Application Data (application_data.csv): Contains *loan applicants’ profiles, including **income, loan amount, employment history, family details, and previous defaults*.  
- **Previous Application Data (previous_application.csv): Historical *loan application records*, including previous loan status, contract type, and repayment history.  

## 📊 Key Insights from EDA  
- *More than 50% of applicants earn between $100K-$200K annually*  
- *31% of loan applicants are above 50 years old*  
- *16% of applicants request loans above $1M*  
- *Most defaults occur among younger applicants and those with lower incomes*  

## 🔧 Technologies Used  
- *Python*  
- *Pandas, NumPy* (Data Cleaning & Processing)  
- *Matplotlib, Seaborn* (Data Visualization)  
- *Scikit-learn* (Feature Engineering & Future Model Training)  
