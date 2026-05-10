Overview

This project focuses on predicting customer churn in a subscription-based telecom service using Machine Learning techniques. The goal is to identify customers who are likely to leave the service and provide actionable business recommendations to improve customer retention.

The project includes:

Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Feature engineering
Churn analysis and visualization
Predictive modeling using Random Forest Classifier
Business insights and recommendations
Dataset Information
Dataset Size: 243,553 customer records
Features Included:
Demographics (Age, Gender)
Subscription details (Plan type, Tenure)
Usage metrics (Calls, SMS, Data usage)
Payment history
Churn status
Data Preprocessing
Removed missing values and duplicates
Corrected 6,050 anomalies in data_used
Verified data consistency across all features
Feature Engineering

Created additional features to improve model performance:

monthly_usage
tenure_months

Feature engineering improved model accuracy by 12%.

Exploratory Data Analysis

Key findings from the analysis:

Overall churn rate: 20%
Customers aged 30–45 showed the highest churn
Basic plan users churned at a much higher rate than premium users
Customers with low monthly usage were more likely to churn
Machine Learning Model
Model Used
Random Forest Classifier
Features Used
Monthly usage
Tenure months
Estimated salary
Number of dependents
Train-Test Split
70% Training
30% Testing
Model Performance
Metric	Score
Accuracy	85%
Precision	0.81
Recall	0.75
F1-Score	0.78
Feature Importance

Top factors influencing churn:

Monthly Usage
Customer Tenure
Estimated Salary
Business Recommendations
Offer targeted promotions for new customers
Introduce engagement reward programs
Improve subscription plans for basic users
Provide personalized offers for high-risk customers
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Results

The predictive model successfully identified churn-prone customers with high accuracy and provided actionable insights to help telecom companies improve customer retention and revenue generation.

Future Improvements
Hyperparameter tuning
Deployment using Flask/Streamlit
Real-time churn prediction dashboard
Advanced ensemble models
