

# U.S. Telecommunication Data Using Machine Learning

## Introduction
This project focuses on analyzing customer churn for a U.S. telecommunications company. The primary objective is to identify the factors leading to service cancellations and develop machine learning models to predict future customer churn.

## Dataset
The dataset (`telecom_df`) contains information on over 1,000 customers, including demographic details, service usage, and billing information. Key questions addressed include:
- What factors are associated with customer churn?
- Can we accurately predict customer churn?
- What are the potential financial impacts of prediction errors?
- What actions can the company take to reduce churn?

## Methodology
We applied various classification models to predict customer churn, including Logistic Regression, K-Nearest Neighbors (KNN), and Decision Trees. Feature engineering and data preprocessing were crucial steps to enhance model performance.

## Results
- **Logistic Regression** achieved the best performance with an ROC AUC of 0.88.
- The model correctly predicted 88% of customer churn cases, enabling the company to proactively address churn risks.

## Recommendations
1. **Introduce More Bundled Services:** Customers with bundled services were less likely to churn.
2. **Encourage Longer Contracts:** Longer tenure with the company correlated with lower churn rates.
3. **Incentivize Automatic Payments:** Electronic check users had higher churn rates; incentives for automatic payments could help.
4. **Monitor and Reduce Monthly Charges:** High monthly charges were linked to higher churn rates; offering affordable plans may help retain customers.

## Conclusion
The project demonstrates that machine learning models can effectively predict customer churn, providing actionable insights to the company for reducing churn and improving customer retention.

