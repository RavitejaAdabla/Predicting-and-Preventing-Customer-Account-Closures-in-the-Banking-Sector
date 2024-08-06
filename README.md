# Project Aim
The banking sector plays a crucial role in the financial ecosystem, contributing significantly to economic growth and our daily lives. A key concern for banks is the attrition of clients who close their credit accounts, impacting business and profitability. This project aims to identify the primary factors leading to account closures, predict future occurrences, and provide actionable recommendations to mitigate this issue.

# Dataset
The dataset contains information on U.S. customers holding credit cards, encompassing various social, economic, and financial factors for a national credit card provider. Each row represents a customer who either canceled or retained their service. The response variable, customer_status, indicates whether the account is 'Closed' or 'Active'. The predictor variables include details about the customers’ socioeconomic factors and credit card activity.

# Key Insights
We analyzed customer behavior, noting that clients who spent more and had higher transaction volumes in Q1 compared to Q4 were more likely to close their accounts. Additional insights include a higher propensity for account closures among customers with blue cards, part-time employees, and those with doctoral degrees. Interestingly, the average duration before account closure is approximately 36 months, with customers in their forties and fifties being more prone to account closure.

# Predictive Modelling
Using models such as Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest, we forecasted the likelihood of account closures. The Random Forest model emerged as the most effective, demonstrating near-perfect classification capabilities. The model's ROC curve is positioned in the top-left corner of the graph, indicating excellent performance. On new data, the model achieved an AUC of 0.9903, underscoring its ability to accurately distinguish between customers who will close their accounts and those who will not. This high accuracy suggests that future classification errors are highly unlikely.

# Recommendations
Based on the findings of my research, I recommend the following steps for bank executives to reduce the number of clients closing their credit card accounts:

## Monitor Spending and Transaction Data: 
Bank executives should closely monitor customers' spending and transaction patterns to predict potential account closures.
## Focus on At-Risk Age Groups: 
Customers aged 35 to 55 are more likely to close their accounts. Bank employees should prioritize this demographic, understanding their challenges through continuous feedback.
## Engage Full-Time and Part-Time Employees: 
Since full-time and part-time employees account for 90% of account closures, it is likely they face dissatisfaction with banking services such as payroll processing and check deposits. Regular contact through telephonic surveys with well-structured questionnaires can help address their concerns.
## Address Blue Card User Concerns: 
Given that blue card users represent the majority of account closures, banks should focus on improving services related to these credit cards.
## Retain Specific Demographics: 
Customers with doctoral degrees, part-time employment, low credit utilization, and lower incomes are more likely to close their accounts. Bank management should develop strategies to retain these customers, such as creating questionnaires to gather credit history and demographic information. The insights gained should be used to tailor retention strategies.

By implementing these recommendations, banks can better identify at-risk customers and take proactive measures to retain them.
