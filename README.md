# Predicting_Customar_Churn_for_Subscription_Service
A machine learning model to predict which customers are likely to churn in the near future, so the company can take preventive actions (like offering discounts or support). .

Project Overview

This project focuses on predicting customer churn for a telecommunications company. By leveraging machine learning, the goal is to identify customers at high risk of churning, enabling proactive interventions to improve customer retention and minimize revenue loss.

Business Problem

Customer churn, the rate at which customers discontinue their service, is a major concern for telecommunications companies. High churn rates can significantly impact revenue and profitability. This project aims to address this problem by developing a predictive model that identifies customers who are likely to churn. By understanding the factors driving churn and identifying high-risk customers, the company can implement targeted strategies to improve customer satisfaction and retention.

Dataset

The project utilizes a publicly available dataset of customer information and churn behavior. The dataset includes features such as demographics, service usage, contract details, and billing information. It contains information about customers who have churned and those who have remained loyal, providing valuable insights into the patterns and characteristics associated with churn.

Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was performed to gain insights into the dataset and identify key features influencing churn. Here are the key findings:

High Churn Rate: The dataset shows a significant customer churn rate, indicating a need for intervention.
Contract Type: Customers with month-to-month contracts have a considerably higher churn rate compared to those with longer-term contracts.
Internet Service: Customers using Fiber optic internet service exhibit a higher propensity to churn.
Tenure: Customers with shorter tenures are more prone to churn.
Monthly Charges: Higher monthly charges are associated with increased churn likelihood.
Total Charges: Customers with lower total charges tend to churn more frequently.
Feature Interactions: Churn is particularly high for Fiber optic customers with month-to-month contracts.

Model Development

Several machine learning models were trained and evaluated, including Logistic Regression, Decision Tree, and Random Forest. After hyperparameter tuning and addressing class imbalance, the models achieved the following performance:

Random Forest: This model demonstrated the best performance, with high accuracy, recall, and ROC AUC score, making it the most suitable for churn prediction.
Final Model Decision
The tuned Random Forest Classifier was selected as the final model due to its superior performance and ability to capture complex relationships within the data. This model accurately predicts churn with a high degree of confidence, allowing the company to focus on targeted interventions.

Key Insights

The project revealed several key insights that can inform customer retention strategies:

Fiber Optic Churners: Customers using Fiber optic internet service, especially those on month-to-month contracts, represent a high-risk segment for churn.
Tenure Relation: Customer tenure is strongly correlated with churn. Retaining new customers is crucial to reducing churn.
Financial Factors: Total charges, tenure, and monthly charges are the most predictive features for churn, highlighting the importance of financial considerations in customer retention strategies.

Problem Solved

This project successfully solved the problem of identifying customers at high risk of churning by developing a predictive model. By leveraging the model's insights and focusing on high-risk segments, the company can proactively implement targeted interventions to improve customer retention, reduce churn rates, and ultimately minimize revenue loss.

Conclusion

This project demonstrates the effectiveness of machine learning in addressing customer churn. By identifying high-risk customers and understanding the factors driving churn, the company can make informed decisions to improve customer satisfaction and retention. The insights gained from this project can guide the development of targeted strategies to mitigate churn and increase revenue.
