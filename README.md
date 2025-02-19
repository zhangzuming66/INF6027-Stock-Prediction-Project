![image](https://github.com/user-attachments/assets/5deb0a7b-1dcc-46e1-8935-ec76e8e994f7)**Title: Stock Prediction using Financial Indicators**

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

## Dataset
This dataset contains over 200 financial indicators for U.S. publicly traded companies in 2014, including metrics like revenue, gross profit, operating income, and financial ratios (e.g., PE ratio, PB ratio). The dataset is used to predict stock performance, with a classification variable indicating whether a stock had positive or negative price variation. Only the 2014 data was used for this analysis.

Dataset source: [Kaggle - 200 Financial Indicators of US Stocks (2014-2018)](https://www.kaggle.com/datasets/cnic92/200-financial-indicators-of-us-stocks-20142018)
