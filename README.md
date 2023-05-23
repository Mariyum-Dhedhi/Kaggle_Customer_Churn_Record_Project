# Kaggle_Customer_Churn_Record_Project

## Introduction
Every bank wants to hold there customers for sustaining their business and thus this Anonymous Multinational bank. As we know, it is much more expensive to sign in a new client than keeping an existing one. Thus, it is advantageous for banks to know what leads a client towards the decision to leave the company. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible. Below is the customer data of account holders at Anonymous Multinational Bank and the aim of the data will be predicting the Customer Churn.
Link to the dataset: https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn

## Attribute Information
RowNumber—corresponds to the record (row) number and has no effect on the output.
CustomerId—contains random values and has no effect on customer leaving the bank.
Surname—the surname of a customer has no impact on their decision to leave the bank.
CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
Geography—a customer’s location can affect their decision to leave the bank.
Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
NumOfProducts—refers to the number of products that a customer has purchased through the bank.
HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
IsActiveMember—active customers are less likely to leave the bank.
EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
Exited—whether or not the customer left the bank.
Complain—customer has complaint or not.
Satisfaction Score—Score provided by the customer for their complaint resolution.
Card Type—type of card hold by the customer.
Points Earned—the points earned by the customer for using credit card.

## Working on DataSet
- I used Pandas, NumPy, Seaborn, and Matplotlib to manipulate and analyze this dataset.
- I trained models using multiple algorithms and identified the best one. The algorithms I used were Random Forest Classifier, Support Vector Classifier (SVC), K-Nearest Neighbors Classifier (KNeighborsClassifier), Gaussian Naive Bayes (GaussianNB), DecisionTreeClassifier, and Linear Regression.
- 
