# Customer Disengagement Forecaster

![alt text](https://www.touchpoint.com/wp-content/uploads/2023/02/5.-Customer-churn-article.png)

## Overview

This machine learning project focuses on predicting customer churn in a telecom company using a dataset obtained from IBM Sample Data Sets. The goal is to analyze customer attributes and behaviors to develop targeted customer retention programs. The project employs exploratory data analysis (EDA) to understand the dataset, visualize key patterns, and build predictive models.

## Dataset

The dataset consists of various customer attributes, including:

- Customer demographics (gender, age range, partners, dependents)
- Services subscribed (phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV and movies)
- Customer account information (tenure, contract type, payment method, paperless billing, monthly charges, total charges)
- Churn status (customers who left within the last month)

Link to the dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Code Structure

The project is divided into the following sections:

1. **Import Libraries and Data:** Load necessary libraries and the dataset.

2. **Exploratory Data Analysis (EDA):**
   - Display the first few rows of the dataset.
   - Check data types, non-null counts, and basic statistics.
   - Explore data distribution, identify outliers, and handle missing values.
   - Visualize the balance of data classes and correlation of features with the churn label.

3. **Analysing Churn:**
   - Explore contract types and create visualizations related to customer tenure.
   - Analyze the distribution of total charges and monthly charges.
   - Calculate the churn rate per cohort and create visualizations.
   - Create scatter plots and count plots to analyze customer behavior.

4. **Predictive Modeling:**
   - Employ predictive models like Single Decision Tree, Random Forest and, AdaBoost.
   - Train the models, make predictions, and evaluate their performance using confusion matrices and classification reports.
   - Assess feature importance in the decision-making process.

## Results

The project concludes with the evaluation of different models, highlighting that the Random Forest model performed the best in terms of accuracy. However, it's worth noting that this result was obtained without performing grid search or cross-validation.

## Inspiration

The project is designed to serve as a learning experience for exploring machine learning models and gaining insights into customer churn prediction in the telecommunications industry.

## Instructions for Use

1. Clone the repository from GitHub.
2. Ensure the required libraries are installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Run the provided Jupyter Notebook or Python script.
4. Analyze the exploratory data analysis and predictive modeling results.
5. Experiment with additional feature engineering, model tuning, and evaluation metrics for further improvements.

Feel free to contribute, report issues, or provide feedback for enhancing the project.
