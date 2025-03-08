# Syriatel_customer_churn_prediction

**Project Overview**:

SyriaTel, a telecommunications company, is experiencing customer churn, leading to revenue loss. This project aims to develop a classification model to predict customer churn based on user behavior and demographics. By identifying at-risk customers, SyriaTel can implement proactive retention strategies.

**Objectives**:

1. Develop a classification model to predict customer churn.
2. Identify key factors influencing customer retention.
3. Provide actionable insights and recommendations to reduce churn.
   
**Dataset Overview**:

Total Records: 3,333 customer records
Features: 21 attributes (e.g., total call duration, charges, customer service interactions, international plan)
Target Variable: *Churn* (Yes/No)
**Class Imbalance**: Addressed using SMOTE to improve prediction accuracy.

**Exploratory Data Analysis (EDA)**:

Key insights from the dataset

1. Customers with high total charges are more likely to churn.
2. Frequent customer service calls indicate dissatisfaction.
3. Geographical location has minimal impact on churn.
   
**Model Development & Evaluation**:

Evaluated multiple classification models based on accuracy, precision, recall, and F1-score.

![image](https://github.com/user-attachments/assets/d290ef28-f871-4134-ba23-fa3b07ad0a5e)

**Model	Accuracy**:

Logistic Regression	69.06%
Decision Tree	88.33%
Random Forest	91.97% (Best Model)
K-Nearest Neighbors	87.40%

✅ **Random Forest** was selected as the final model due to its superior accuracy and robustness to class imbalance.

**Model Performance**:

Accuracy: 91.97%
Recall: 53.61%
F1-Score: 32.50%

**Limitation**: Class imbalance affected the model's ability to correctly classify all churners.

**Feature Analysis Conclusions**:

1. Total Calls & Total Charges: Customers with higher total charges and frequent calls are more likely to churn.
2. Customer Service Calls: A high number of service interactions often indicates dissatisfaction, increasing churn probability.
3. Geographical Location: Has minimal influence on churn, meaning retention strategies should focus on behavioral patterns rather than location-based targeting.
   
🎯 **Business Recommendations**:

1. Enhance Customer Support: Reduce churn by addressing frequent service complaints.
2. Loyalty Programs: Provide exclusive offers to high-value customers.
3. Targeted Retention Campaigns: Develop personalized strategies for at-risk customers.
4. AI-Driven Churn Monitoring: Implement real-time churn prediction models for proactive intervention.
