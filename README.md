## 📌 Project Overview
Customer churn is a major challenge in the banking industry, as acquiring new customers is significantly more expensive than retaining existing ones.

This project develops a **machine learning classification model** to predict customers at risk of churn. In addition, exploratory analysis was conducted to examine churn patterns across customer demographics such as age and geography, helping identify high-risk groups and inform targeted retention strategies.

The insights generated from this analysis support data-driven decision-making to improve customer lifetime value and reduce attrition.

## 📂 Dataset
The dataset contains customer-level information including:

- **Demographics:** Age, gender, geography  
- **Account Details:** Credit score, balance, tenure, number of products  
- **Behavioral Indicators:** Activity status, credit card ownership  
- **Target Variable:** `Exited` (1 = churned, 0 = retained)

## **1. Approach**
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Selection
- Model Training & Evaluation  

## **2. Models Used**
- Random Forest Classifier  
- Logistic Regression 
- Support Vector Machine (SVM)
- KNN  
- Gradient Boosting Classifier

## **3. Evaluation Metrics**
- Confusion Matrix
- Accuracy  
- Precision  
- Recall  
- F1-score

## **4. Model Optimization**
- Feature Engineering
- Hyperparameter tuning  
- Handling class imbalance  
- Tuned Gradient Boosting Classifier

**Key Insight:**  
Despite a slight decrease in overall accuracy, the tuned model identified **27 additional churners**, significantly improving churn detection.

### ⚖️ Model Trade-Off Summary

| Metric | Before | After |
|------|--------|-------|
| Accuracy | 87% | 86% |
| Churn Recall | 49% | **56%** |
| Churners Identified | 192 | **219** |

### ✅ Final Conclusion
The tuned Gradient Boosting model provides a **more business-effective solution**, prioritizing churn detection over marginal accuracy gains. This approach is better suited for real-world deployment where **missing churners is more costly than false positives**.

# 📉 Customer Churn Prediction (Banking) Project Documentation
## **1. What problem does this solve?**
This analysis develops a predictive model to identify bank customers who are likely to churn, enabling proactive intervention by the retention team.

## **2. What’s the business impact?**
Catching **56% of churning customers** before they leave could save the bank an estimated **$1.2M annually**, based on an average customer lifetime value of **$2,500**.

## **3. What did you do?**
I analyzed **10,000 customer records**, built a **Gradient Boosting** model with engineered features and **SMOTE** to predict customer churn probability, and identified the **top 5 features** driving churn.  
The final model achieved:
- **85.8% accuracy**
- **56% recall** for churners
- **67% precision** for churners

## **4. What are the key findings?**
- Customers aged **35-55** are significantly more likely to churn.
- Certain geographical regions (e.g., **Germany**) exhibit higher churn rates.
- Customers with **zero account balance** or **lower estimated salaries** show increased churn risk.
- **Less active members** are considerably more prone to churn, emphasizing the importance of customer engagement.

## **5. What should someone do about it?**
- **Targeted Retention Campaigns:**  
  Reach out to customers with a churn probability **greater than 60%** using personalized retention offers such as exclusive financial products, reduced fees, or enhanced customer support.
- **Customer Engagement Programs:**  
  Create engagement initiatives for less active members and customers with zero balances, including financial literacy workshops or personalized financial planning.
- **Regional Strategy Review:**  
  Conduct deeper analysis of churn drivers in high-risk regions (e.g., Germany) and implement **localized retention strategies**.
