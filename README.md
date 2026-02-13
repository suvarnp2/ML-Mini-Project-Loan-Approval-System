# ML-Mini-Project-Loan-Approval-System
This ML model helps predict the lending company whether a loan is likely to default or not.

This is a mini project as part of my course training. It uses data from Lending Club company available freely. 
Lending Club is a peer-to-peer lending company where individuals can borrow loans, and investors can fund those loans. 

# Technology 
Python, pandas , numpy, matplotlib, seaborn, imblearn, sklearn, xgboost 

# Problem Statement:
Now, whenever Lending Club approves a loan, there are two ways in which it is at risk:

* If LC approves a loan and the borrower fails to repay it on time
* If LC rejects a loan despite the borrower being capable of repaying the loan
Defaulting on loans can lead to significant financial losses for both the platform and investors. Similarly, not providing loans to credit-worthy customers can lead to missing out on potential revenue and profits. Therefore, a robust loan approval system is the need of the hour.

In the current loan approval process, underwriters evaluate loan applications by manually reviewing credit scores, income, debt, etc. and then, based on several parameters, either approve or reject a loan. This process is time-consuming and prone to errors.

Hence, Lending Club wants to build a loan approval system using Machine Learning models to automatically assess whether a given loan is likely to be repaid or whether the borrower is likely to default.

This is where this solution comes in! My goal is to help out Lending Club in creating this ML model that helps them predict whether a loan is likely to default or not.

# Process 
The problem of predicting loan defaults was addressed by first loading and cleaning the loan application data, handling missing values, and converting relevant columns to appropriate data types. 
Exploratory Data Analysis (EDA) was performed to understand variable distributions and their relationship with loan status. 
Class imbalance was handled using SMOTE. 
The data was then split into training and testing sets and scaled. 
Baseline Logistic Regression, Random Forest, and XGBoost models were built and evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC. 
Hyperparameter tuning was applied to XGBoost to optimize its performance. The models' training and test performance were compared to check for overfitting.

# Running the project 
Open the colab notebook and save it in your drive.
Run the colab project.

