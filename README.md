# Customer_Churn_Analysis

## Overview
This project analyzes customer churn trends using the Telco Customer Churn dataset. The analysis identifies key factors contributing to churn and builds a predictive logistic regression model.

## Key Insights
- **Higher churn rates** are observed among customers with shorter tenure and higher monthly charges.
- Customers on **month-to-month contracts** are more likely to churn compared to long-term contracts.
- Discounts and longer contracts significantly improve retention.

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

## How to Run the Analysis
1. Clone this repository:
https://github.com/your-username/Customer_Churn_Analysis.git

2. Open `CustomerSuccessAnalytics.Rmd` in RStudio.
3. Run the R Markdown file or knit it into a PDF/HTML.

## Results
The logistic regression model predicts churn based on:
- `Tenure in Months`
- `Monthly Charges`
- `Total Charges`

Model summary:
- **Accuracy**: 85%
- **Key Predictors**: Short tenure and high monthly charges are strong churn indicators.

## Contact
For questions or feedback, reach out via GitHub issues or email at [jennifer_zammyr@hotmail.com].
