# SyriaTel_customer_churn_prediction

📌**Project Overview**:

SyriaTel, a telecommunications company, is experiencing customer churn, leading to revenue loss. This project aims to develop a classification model to predict customer churn based on user behavior and demographics. By identifying at-risk customers, SyriaTel can implement proactive retention strategies.

🏆**Objectives**:

1. Develop a classification model to predict customer churn.
2. Identify key factors influencing customer retention.
3. Provide actionable insights and recommendations to reduce churn.
   
📂**Dataset Overview**:

Total Records: 3,333 customer records were analyzed.

Features: 21 attributes (e.g., total call duration, charges, customer service interactions, international plan).

Target Variable: *Churn* (Yes/No)

**Class Imbalance**: Addressed using Synthetic Minority Oversampling Technique (SMOTE) to improve prediction accuracy.

🔍**Exploratory Data Analysis (EDA)**:

Key insights from the data analysis include:

1. Customers with high total charges are more likely to churn.
2. Frequent customer service calls indicate dissatisfaction.
3. Geographical location (Area Code/State) had minimal impact on churn.
   
📈**Model Development & Evaluation**:

Evaluated multiple classification models based on accuracy, precision, recall, and F1-score.

![Image](https://github.com/user-attachments/assets/0a019286-56cc-4a2d-8fdb-a749255bee46)

✅ **Random Forest** was the final prediction model used due to its superior accuracy and robustness to class imbalance.

🔬**Feature Analysis Conclusions**:

Insights from the feature analysis include:

1. Total Calls & Total Charges: Customers with higher total charges and frequent calls are more likely to churn.
2. Customer Service Calls: A high number of service interactions often indicates dissatisfaction, increasing churn probability.
3. Geographical Location: Has minimal influence on churn, meaning retention strategies should focus on behavioral patterns rather than location-based targeting.

 ![Image](https://github.com/user-attachments/assets/ef22383b-6b34-4a9d-8ad0-20629e3061db)

   
🎯 **Business Recommendations**:

1. Enhance Customer Support: Reduce churn by addressing frequent service complaints.
2. Loyalty Programs: Provide exclusive offers to high-value customers.
3. Targeted Retention Campaigns: Develop personalized strategies for at-risk customers.
4. AI-Driven Churn Monitoring: Implement real-time churn prediction models for proactive intervention.
