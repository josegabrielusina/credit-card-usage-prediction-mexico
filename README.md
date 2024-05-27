# Linear Regression Analysis for Credit Card Usage Prediction in Mexico - Summary

**Author:** José Gabriel Usiña Mogro  
**Date:** September 2022

## Introduction
Linear regression is employed to predict the usage of credit cards in Mexico, aiming to understand the factors influencing its use.

## Background
The recovery of the economy post-COVID-19 and increased technological penetration into financial services are key drivers of credit card usage growth.

## Problem Situation
Financiera Ma, a Mexican financial company, faces lower-than-expected credit card usage. Comparisons with other countries highlight significant disparities.

## Data and Methodology
- **Importing Data:** Data on credit card usage in Mexico is imported for analysis.
- **Descriptive Statistics:** An overview of the dataset reveals outliers and missing values.
- **Data Transformation:** Necessary transformations, such as converting variables to factors and handling missing data, are performed.

## Descriptive Statistics and Data Visualization
- Descriptive statistics and visualizations, including box plots and histograms, offer insights into the distribution of variables and potential outliers.
- Normality checks and data visualization provide further understanding of the dataset's characteristics.

## Linear Regression Analysis
Three regression models are constructed to predict credit card usage:
1. Model 1: Includes age, region, income, education, and phone ownership.
2. Model 2: Expands on Model 1 by adding age squared.
3. Model 3: Incorporates age, age squared, income, and credit card ownership.

## Model Evaluation
- **Accuracy Assessment:** Models are evaluated based on AIC and RMSE metrics.
- **Diagnostic Tests:** Multicollinearity and heteroscedasticity tests are conducted to ensure model validity.

## Selection of the Best Model
Model 1 emerges as the optimal choice due to its superior AIC, RMSE, and absence of multicollinearity issues.

## Interpretation of Results
Income and education level significantly influence credit card usage. Region 4 also exhibits a notable impact on card usage.

## Predictive Insights
- The positive relationship between income and credit card usage suggests targeting high-income individuals.
- Marketing efforts should focus on Region 4 to capitalize on its potential for increased credit card usage.

## Recommendations
- Financiera Ma should devise marketing and financial strategies targeting high-income individuals and Region 4 residents to boost credit card usage and revenue.

## References
- Swaminathan, S. (2019, January 18). Linear Regression - Detailed View. Towards Data Science.
- Euromonitor. (n.d.). Euromonitor Login.
