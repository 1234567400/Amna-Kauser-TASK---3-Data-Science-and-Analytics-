# Amna-Kauser-TASK---3-Data-Science-and-Analytics-
Data Science and Analytics Internship Tasks
## Task 3: Customer Churn Prediction (Bank Customers)

### Objective
Identify customers who are likely to leave the bank
based on their personal and account information.

### Approach
- Loaded the Churn Modelling dataset
- Cleaned the data — checked missing values, duplicates,
  dropped unnecessary columns (RowNumber, CustomerId, Surname)
- Encoded categorical features:
  - Label Encoding for Gender
  - One Hot Encoding for Geography
- Trained a Decision Tree classifier (max_depth=5)
- Analyzed feature importance to identify key churn factors

### Results and Insights
- Model Accuracy: 85.7%
- Age (0.41) and NumOfProducts (0.36) are the strongest 
  predictors of churn
- Older customers with more products are most likely to leave
- Tenure, CreditScore, HasCrCard, and Geography_Spain have 
  almost zero impact on churn
