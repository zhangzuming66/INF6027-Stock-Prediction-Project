**Title: Stock Prediction using Financial Indicators**

# Stock Prediction using Financial Indicators (INF6027) 
This project explores whether financial indicators such as revenue growth and gross profit can be used to predict stock performance. By using machine learning models, we attempt to classify stocks as "buy-worthy" or "not buy-worthy" based on financial metrics from the 2014 financial dataset.

## Research Questions
1. Can financial indicators accurately predict stock performance and classify stocks as "buy-worthy" or "not buy-worthy"?
2. Which financial indicators most significantly impact stock performance prediction?
3. Are machine learning models effective in predicting stock movements using financial data from 10-K filings?

## Key Findings
- The **linear regression model** explained a large portion of the variance in revenue, with `Cost.of.Revenue` and `Gross.Profit` being highly significant predictors.
- The **logistic regression model** had an accuracy of 56%, suggesting that financial indicators alone are insufficient to classify stocks accurately as "buy-worthy" or "not buy-worthy".
- The **ANOVA test** showed no significant differences in `Revenue.Growth` across sectors, highlighting that other factors might influence revenue growth more than sector membership.
