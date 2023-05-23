# Kaggle_Customer_Churn_Record_Project

## Introduction
Every bank wants to hold there customers for sustaining their business and thus this Anonymous Multinational bank. As we know, it is much more expensive to sign in a new client than keeping an existing one. Thus, it is advantageous for banks to know what leads a client towards the decision to leave the company. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible. Below is the customer data of account holders at Anonymous Multinational Bank and the aim of the data will be predicting the Customer Churn.
Link to the dataset: https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn

## About DataSet
1. RowNumber — Corresponds to the record (row) number and has no effect on the output.
2. CustomerId — Contains random values and has no effect on customer leaving the bank.
3. Surname — The surname of a customer has no impact on their decision to leave the bank.
4. CreditScore — Can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
5. Geography — A customer’s location can affect their decision to leave the bank.
6. Gender — It’s interesting to explore whether gender plays a role in a customer leaving the bank.
7. Age — This is certainly relevant, since older customers are less likely to leave their bank than younger ones.
8. Tenure — Refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
9. Balance — A very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
10. NumOfProducts — Refers to the number of products that a customer has purchased through the bank.
11. HasCrCard — Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
12. IsActiveMember — Active customers are less likely to leave the bank.
13. EstimatedSalary — As with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
14. Exited — Whether or not the customer left the bank.
15. Complain — Customer has complaint or not.
16. Satisfaction Score — Score provided by the customer for their complaint resolution.
17. Card Type — Type of card hold by the customer. 
18. Points Earned — The points earned by the customer for using credit card.

## Working on DataSet
- I used Pandas, NumPy, Seaborn, and Matplotlib to manipulate and analyze this dataset.
- I trained models using multiple algorithms and identified the best one. The algorithms I used were Random Forest Classifier, Support Vector Classifier (SVC), K-Nearest Neighbors Classifier (KNeighborsClassifier), Gaussian Naive Bayes (GaussianNB), DecisionTreeClassifier, and Linear Regression.
