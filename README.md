# Customer_Churn_Analysis

## Overview
This project explores customer churn using the Telco Customer Churn dataset, with the goal of identifying risk factors and building a predictive model to support retention strategies.

## Key Insights
- Customers with **shorter tenure** and **higher monthly charges** were significantly more likely to churn.
- **Month-to-month** contracts correlated with the highest churn rates, while long-term contracts improved retention.
- Discounts and incentives for contract renewals showed a measurable impact on lowering attrition risk.

## Files Included
- `CustomerSuccessAnalytics.Rmd`: The R Markdown file containing the analysis.
- `CustomerSuccessAnalytics.html`: Knitted output of the R Markdown file.
- `visualizations/`: Directory containing visualizations like:
  - Churn distribution
  - Tenure by churn
  - Correlation heatmap
- `data/telco_clean.csv`: The cleaned dataset used for analysis.

## Tools and Libraries
- **R Packages**:
  - `tidyverse` for data cleaning and visualization.
  - `caret` for data partitioning.
  - `ggplot2` for visualizations.
  - `corrplot` for correlation analysis.
**Techniques:** Data cleaning, EDA, logistic regression, correlation analysis, visualization

## How to Run the Analysis
1. Clone this repository:
https://github.com/jenniferzag/Customer_Churn_Analysis.git

2. Open `CustomerSuccessAnalytics.Rmd` in RStudio.
3. Run the R Markdown file or knit it into a PDF/HTML.

## Results
- Built a logistic regression model with 85% accuracy.
- Identified short tenure and high monthly charges as top churn predictors.
- Delivered insights that could help businesses design targeted retention campaigns and reduce attrition risk.

The logistic regression model predicts churn based on:
- `Tenure in Months`
- `Monthly Charges`
- `Total Charges`

Model summary:
- **Accuracy**: 85%
- **Key Predictors**: Short tenure and high monthly charges are strong churn indicators.

## Contact
For questions or feedback, reach out via GitHub issues or email at [jennifer_zammyr@hotmail.com].
