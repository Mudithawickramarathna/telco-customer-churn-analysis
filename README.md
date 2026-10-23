# Telecom Customer Churn Analysis and Prediction

## Project Overview

This project analyzes customer churn in a telecommunications dataset using Python and machine learning. It explores customer characteristics associated with churn and develops a logistic regression model to identify customers who may be at risk of leaving.

## Objectives

- Clean and prepare customer data for analysis.
- Perform exploratory data analysis (EDA).
- Visualize churn patterns across customer segments.
- Build a logistic regression classification model.
- Evaluate model performance using classification metrics.
- Develop data-driven customer retention recommendations.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Key Findings

- Overall customer churn rate: 26.5%.
- Month-to-month contracts had a churn rate of approximately 42.7%.
- Customers with 12 months or less of tenure had a churn rate of approximately 47.4%.
- Fiber-optic customers had a churn rate of approximately 41.9%.
- Electronic-check customers had a churn rate of approximately 45.3%.

## Machine Learning Results

The logistic regression model was evaluated on a held-out test dataset.

| Metric | Threshold 0.5 |
|---|---:|
| Accuracy | 80.55% |
| Precision (churn class) | 65.72% |
| Recall (churn class) | 55.88% |
| F1-score (churn class) | 60.40% |
| ROC-AUC | 0.8421 |

Reducing the classification threshold to 0.3 increased churn recall to approximately 75.4%, with lower precision and accuracy. The threshold should be selected according to business requirements and validated appropriately.

## Business Recommendations

- Investigate retention strategies for month-to-month customers.
- Strengthen onboarding and early engagement for new customers.
- Investigate customer experience among fiber-optic users.
- Review billing and payment experiences for electronic-check users.

These findings describe associations in the dataset and do not establish causation.

## Limitations

Model performance may vary on new customer data. Threshold selection and further validation are necessary before operational deployment.

## Author

BSc (Hons) Statistics graduate, University of Jaffna.
