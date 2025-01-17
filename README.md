# Walmart-Weekly-Sales-Prediction

## About the Dataset
One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. Some certain events and holidays impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock sometimes, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.

Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data. Historical sales data for 45 Walmart stores located in different regions are available.

We sourced the dataset from Kaggle.

## Our Approach

1. The project leveraged multiple machine learning algorithms, including ARIMA, Linear Regression, Isolation Forests, Random Forests, and XGBoost, along with a Voting Regressor ensemble, to predict weekly sales for Walmart stores using three-week lag variables.

2. Factors like temperature and CPI were initially hypothesized to impact sales; however, the analysis revealed that store size and department had a more significant influence.

3. Random Forest emerged as the best-performing model, achieving the lowest Mean Absolute Error (MAE) of 2514 and a high Coefficient of Determination (R²) of 0.94, demonstrating its superior accuracy.

4. Incorporating lag variables into the dataset notably enhanced model performance, highlighting their importance in capturing temporal sales patterns.
