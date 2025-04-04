				Stock Price Prediction using Machine Learning

This project predicts the closing stock price of **Apple Inc. (AAPL)** using historical stock data and a **Random Forest Regressor**. The dataset is fetched in real-time using the `yfinance` library.



Model Used:

**Random Forest Regressor**  
A powerful ensemble-based machine learning algorithm suitable for regression problems like stock price prediction.



Features:

Real-time stock data download using `yfinance`
Feature selection from Open, High, Low, and Volume
Model training with **Random Forest Regression**
Performance evaluation using **Mean Squared Error** and **R² Score**
Visualization of actual vs predicted prices




Files included

stock_price_prediction.ipynb => Main notebook/script containing the full code
stock_data.csv => Historical stock data for Apple (2022–2025)
README.md => Project overview and instructions
Requirements.txt => Python libraries used



Conclusion:

In this project, we successfully built a Stock Price Prediction model for Apple Inc. (AAPL) using Random Forest Regression. By training on historical stock data from 2022 to 2025, the model learned patterns from features such as Open, High, Low, and Volume to predict the closing price.

The model achieved a strong performance, as measured by:

Low Mean Squared Error (MSE) — indicating accurate predictions
High R² Score — showing the model captures most of the variance in the target

We also visualized the predicted vs actual prices, which helped us evaluate how closely the model tracks real stock trends.