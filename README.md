# Customer-Bank-Churn-Prediction
Table of Contents  1. Modeling Objective¶   2. Data Overview   3. Exploratory Data Analysis   4. Featuring Enginnering   Model Design   Split the data   Model 1: CatBoost
The data will be used to predict whether a customer of the bank will churn. If a customer churns, it means they left the bank and took their business elsewhere. If you can predict which customers are likely to churn, you can take measures to retain them before they do. These measures could be promotions, discounts, or other incentives to boost customer satisfaction and, therefore, retention.

The dataset contains:

10,000 rows – each row is a unique customer of the bank

14 columns:

RowNumber: Row numbers from 1 to 10,000

CustomerId: Customer’s unique ID assigned by bank

Surname: Customer’s last name

CreditScore: Customer’s credit score. This number can range from 300 to 850.

Geography: Customer’s country of residence

Gender: Categorical indicator

Age: Customer’s age (years)

Tenure: Number of years customer has been with bank

Balance: Customer’s bank balance (Euros)

NumOfProducts: Number of products the customer has with the bank

HasCrCard: Indicates whether the customer has a credit card with the bank

IsActiveMember: Indicates whether the customer is considered active

EstimatedSalary: Customer’s estimated annual salary (Euros)

Exited: Indicates whether the customer churned (left the bank)
