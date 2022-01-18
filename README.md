# Problem Statement
The objective is to predict the attrition of credit card customers using the dataset provided to help the manager at the bank to formula policies to reduce the churn rate of credit card customers. 

# Dataset Description

The dataset contains the bank records of credit card customers at the bank. 
There are 10000 rows of data provided. 

Data is obtained from https://www.kaggle.com/sakshigoyal7/credit-card-customers

# Models used
- Logistic Regression
- Gradient Boosting Classifier 
- Random Forest Classifier

# Data Exploration
1. There is a higher proportion of doctorate customers that churn as compared to customers of other education levels
2. There is a higher proportion of platinum customers that churn as compared to customers of other card categories
3. Customers with higher Total_Revolving_Bal tend to churn more as compared to customers with lower Total_Revolving_Bal
4. Customers with higher Total_Trans_Amt tend to churn less as compared to customers with lower Total_Trans_Amt
5. Customers with lower Avg_Utilization_Ratio tend to churn more as compared to customers with higher Avg_Utilization_Ratio
6. Customers with higher Total_Trans_Ct tend to churn less as compared to customers with lower Total_Trans_Ct

# Choice of model and Key findings
Random Forest Classifier

Top important features are Total_Trans_Am and Total_Trans_Ct

Obtained 98.5098% Accuracy
