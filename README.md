# Analyzing-Customer-Response-to-Banking-Marketing-Dataset-Using-Logistic-Regression-Approach

This project leverages logistic regression to analyze and predict customer behavior related to subscription to term deposits in the banking sector. The dataset, "bank-full.csv," includes comprehensive customer demographic and transactional data from direct marketing campaigns of a Portuguese bank.

## Dataset Overview
The dataset comprises client details like age, job type, marital status, and financial metrics (e.g., credit default, average yearly balance). It records communication types and campaign metrics, providing a robust foundation for logistic regression.

## Data Preparation
- **Cleaning**: The dataset was confirmed to have no missing or null values.
- **Feature Encoding**: Categorical data was transformed using label encoding for model compatibility.
- **Correlation Analysis**: A correlation matrix was employed to identify influential features for term deposit subscriptions.

## Model Implementation
A logistic regression model was used for its binary classification capability. Data standardization and feature scaling were applied. The model was evaluated using metrics like ROC curve, AUC (achieving 0.816), accuracy, precision, recall, and F1-score.

## Results & Challenges
The model was highly precise for non-subscribers but showed limitations in detecting actual subscribers due to class imbalance. Although the overall accuracy was high, the recall for subscribers was low, indicating a bias towards the majority class.

## Conclusion
This analysis highlights the importance of class distribution and model selection. While logistic regression offered clear insights, future improvements could include class balancing and non-linear models to better capture complex relationships and enhance predictions.
