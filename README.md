Customer Churn Prediction Project Documentation
1. What problem does this solve?
This analysis develops a predictive model to identify bank customers who are likely to churn, enabling proactive intervention by the retention team.

2. What’s the business impact?
Catching 56% of churning customers before they leave could save the bank an estimated $1.2M annually based on an average customer lifetime value of $2,500.

3. What did you do?
I analyzed 10K customer records, built a Gradient Boosting model with engineered features and SMOTE to predict customer churn probability, and identified the top 5 features driving churn. The final model achieved 85.8% accuracy, with 56% recall and 67% precision for churners.

4. What are the key findings?
Customers in the 40-60 age bracket are significantly more likely to churn.
Specific geographical regions (e.g., Germany) exhibit a higher churn rate compared to others.
Customers with zero account balance or lower estimated salaries show an increased propensity to churn.
Less active members are considerably more prone to churn, highlighting the importance of customer engagement.
5. What should someone do about it?
Targeted Retention Campaigns: The retention team should reach out to customers with a churn probability >60% (as predicted by the model) with personalized retention offers, such as exclusive financial products, reduced fees, or enhanced customer service support.
Customer Engagement Programs: Develop specific engagement programs for less active members and those with zero account balances, as they show a higher propensity to churn. This could include financial literacy workshops or personalized financial planning advice.
Regional Strategy Review: Conduct a deeper dive into churn drivers in high-churn regions (e.g., Germany) to develop localized retention strategies.

