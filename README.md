# Introduction:
# Objective: 
Bank GoodCredit wants to predict cred score for current credit card customers. The cred score will denote a customer’s credit worthiness and help the bank in reducing credit default risk.

Target variable → Bad_label
- 0 – Customer has Good credit history
- 1 – Customer has Bad credit history

# DataSet:
Dataset is available in SQL database and explanation for each table is as below:
- Customer Account Data (Table : Cust_Account):
  This table contains customer’s historical accounts data and payments history
- Customer Enquiry Data (Table : Cust_Enquiry):
  This table contains customer’s historical enquiry data such as enquiry amount and enquiry purpose.
- Demographics Data (Table : Cust_Demographics):
  Current customer applications with demographic data

## Note that demographics features are renamed as features and obscured in accordance with privacy policies.

# Accuracy Score Comparison:
![image](https://github.com/user-attachments/assets/5ababdb0-be2c-488d-a2a2-1f3199617e5b)

# Comparitive Analysis of different models

# Logisitic Regression:
Logistic regression is a straight forward and efficient algorithm mainly used for classification tasks. In this project, logistic regression achieved an accuracy of 81.78%. Though it captures some of the linear relationship within the data but it falls short of a high performance model.

# Decision Tree:
Decision trees are intuitive and easy-to-interpret models that split data based on feature values to make predictions. With an highest accuracy of 99.72% outperforming Random forest & XGBoost models with minor difference, decision tree will be strong candidate for credit score prediction.
Random Forest:

# Random forest:
Random Forest an ensemble learning method combines multiple decision trees to improve accuracy and reduce overfitting. With an accuracy of 99.70%, random forest significantly overperformed Logistic regression, XGBoost & ANN. The high accuracy indicates that random forest is capable of capturing complex patterns and relationship in the dataset makes random forest will be one strong candidates for credit score prediction.
XGBoost:

# XGBoost:
XGBoost (or) eXtreme Gradient Boosting, is a powerful and efficient implementation of gradient boosting designed for speed and performance. With an accuracy of 99.05%, XGBoost proofs that it is one of the high performing models.

# ANN:
Though Artificial neural network is powerful algorithm, recorded an lowest accuracy of 53.77%. Thislower accuracy compared to other algorithms might reflect increased complexity and computational demands.

** The evaluation suggests that ensemble method Decision Tree is exceptionally well-suited for capturing complex patterns in the credit risk data, making it ideal for credit score prediction.
