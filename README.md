**Customer Churn Prediction for PowerCo - Project Description:**


This project develops a machine learning solution to predict customer churn for PowerCo, a major gas and electricity utility company serving SMEs. The analysis addresses a critical business challenge where PowerCo has been experiencing significant customer churn, prompting an investigation into whether price sensitivity is the primary driver of customer attrition.

The project follows a comprehensive data science workflow beginning with exploratory data analysis (EDA) of client and pricing data. The EDA reveals key insights including a 10% churn rate, highly skewed consumption patterns, and varying churn rates across different sales channels. Visualizations uncover important patterns in customer behavior, consumption trends, and contract characteristics.

The feature engineering phase transforms raw data into predictive features, building upon a colleague's initial price difference feature (December vs. January off-peak prices). Additional engineered features include average price changes across time periods, maximum price variations, customer tenure calculations, and date-based transformations. Statistical transformations address data skewness through logarithmic scaling, while categorical variables are converted using one-hot encoding.

The predictive model employs a Random Forest classifier with 1,000 decision trees, chosen for its ability to handle non-linear relationships and provide feature importance insights. Model evaluation reveals high accuracy (89.9%) but highlights a critical weakness in recall (4.9%), indicating poor performance in identifying actual churners.

Feature importance analysis reveals that net margin and 12-month consumption are the strongest predictors of churn, while price sensitivity features show moderate but not dominant influence. This finding suggests that while price sensitivity contributes to churn, it is not the primary driver - contradicting the initial hypothesis.

The project concludes with actionable insights for PowerCo, demonstrating that customer retention strategies should focus on margin optimization and consumption patterns rather than solely on pricing adjustments. Future improvements would require enhanced feature engineering to better identify churning customers.
