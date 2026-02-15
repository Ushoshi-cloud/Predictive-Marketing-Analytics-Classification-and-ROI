# Predictive-Marketing-Analytics-Classification-and-ROI
Built a customer response prediction model achieving AUC 0.69 and simulated targeted campaign ROI to optimize marketing spend.
Customer Marketing Response Prediction & Profit Optimization
Business Problem

Marketing campaigns are expensive, and sending promotions to all customers leads to high costs and low efficiency.

Only a small percentage of customers respond to campaigns, resulting in wasted marketing spend and missed profit opportunities.

The objective of this project is to:

Predict which customers are likely to respond

Reduce campaign costs through targeted marketing

Simulate financial impact and profit optimization

Data Overview

400+ customer records

Features include age, balance, job type, contact history, and campaign details

Target variable:

1 → Customer responded

0 → Customer did not respond

Response Rate: ~26%

The dataset is imbalanced, making prediction more challenging and realistic.

Exploratory Data Analysis (EDA)

Key Insights:

Only 1 in 4 customers responded to the campaign

Customers with higher account balances were more likely to respond

Majority of customers fall between 30–60 years of age

This indicates that financial strength and demographic factors influence campaign success.

Data Cleaning & Preparation

Removed missing values

Removed duplicate records

Detected and removed outliers using IQR method

Encoded categorical variables using one-hot encoding

Converted target variable into binary format

This ensures high data quality before modeling.

Classification Model – Logistic Regression

The model predicts whether a customer will respond to a marketing campaign.

Model Performance

Accuracy: ~78%

ROC-AUC Score: 0.69

True Positives: 9

True Negatives: 81

The model performs better than random guessing and demonstrates moderate predictive power.

Confusion Matrix Insight

Correctly identified most non-responders

Missed some real responders (opportunity loss)

Business implication:
Improving recall can increase revenue capture.

Regression Model – Revenue Prediction

Assumption:

Revenue per responder = $200

A linear regression model was used to simulate expected revenue impact.

Evaluation Metrics:

R² Score

MAE

RMSE

This adds financial interpretation beyond classification.

Profit Simulation

Assumptions:

Campaign cost per customer = $5

Revenue per responder = $200

Using predicted responders:

Estimated profit was calculated as:

Profit = Revenue − Campaign Cost

This demonstrates how predictive targeting improves marketing ROI compared to mass outreach.

Business Impact

This project shows how predictive analytics can:

Reduce unnecessary campaign spending

Improve targeting accuracy

Increase marketing ROI

Quantify financial benefits before execution

Even with moderate model performance (AUC = 0.69), targeted marketing significantly improves cost efficiency.

Tools & Technologies

Python

Pandas

NumPy

Seaborn

Matplotlib



Key Takeaway

Instead of sending campaigns to all customers, predictive modeling enables data-driven targeting, improving profitability and reducing marketing waste.

This project connects machine learning with real business decision-making.
