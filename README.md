CustomerChurn-ana
Built an end-to-end churn prediction model using Python on telecom data. Performed data manipulation, visualization, and trained linear, logistic, decision tree, and random forest models to predict customer churn. Improved insights to help reduce churn risk.


Customer Churn Prediction - Telecom Dataset

This project analyzes customer churn for a telecom company using machine learning. The goal is to identify patterns that lead to customer churn and help the business take actions to reduce it.

 Problem Statement
The telecom company "Neo" is losing customers to competitors. You are tasked with building an analytical pipeline that identifies key churn indicators.

 Dataset
- Name: `customer_churn.csv`
- Features: Customer demographics, account information, service usage, and churn status.

 Tasks Performed

 Data Manipulation
- Extracted specific columns and customer subsets using logical conditions.
- Filtered and created views based on seniority, gender, contract type, and payment method.

 Data Visualization
- Plotted:
  - Bar chart (Internet Service)
  - Histogram (Tenure)
  - Scatter plot (Tenure vs Monthly Charges)
 Linear Regression
- Built model: `MonthlyCharges ~ tenure`
- Calculated RMSE and prediction error

Logistic Regression
- Binary logistic: `Churn ~ MonthlyCharges`
- Multiple logistic: `Churn ~ MonthlyCharges + tenure`
 Decision Tree
- `Churn ~ tenure`

 Random Forest
- `Churn ~ MonthlyCharges + tenure`

Key Libraries
- pandas, matplotlib, seaborn
- scikit-learn

 Insights
- Churn is higher with electronic check payments and short tenure.
- MonthlyCharges and contract type are significant predictors.

 Model Performance
- Accuracy from various models calculated to evaluate predictive strength.

How to Run
1. Clone repo
2. Install dependencies:
