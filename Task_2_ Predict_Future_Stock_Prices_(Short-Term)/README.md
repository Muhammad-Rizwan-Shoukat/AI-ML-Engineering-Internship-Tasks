# Apple Stock Price Prediction (Short-Term)

## Project Overview
This project focuses on **short-term stock price prediction** using historical market data of **Apple Inc. (AAPL)**.  
The goal is to predict the **next day’s closing price** based on previous trading information.  
Machine learning regression techniques are applied to understand price movement patterns and evaluate prediction accuracy using standard error metrics.

---

## Objective
The main objectives of this project are:

- Analyze historical stock price data of Apple Inc.
- Use features such as **Open, High, Low, and Volume** for prediction
- Build a regression model for next-day closing price prediction
- Evaluate model performance using error-based metrics

---

## Dataset Description
The dataset is retrieved directly from **Yahoo Finance** using the `yfinance` Python library.  
It contains historical daily stock data for Apple Inc. with the following features:

| Feature | Description |
|------|------------|
| Open | Opening stock price of the day |
| High | Highest stock price of the day |
| Low | Lowest stock price of the day |
| Close | Closing stock price of the day |
| Volume | Number of shares traded |

---

## Tools and Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- yfinance  
- Jupyter Notebook  

---

## Methodology
The project follows these steps:

1. Selection of Apple Inc. (AAPL) stock  
2. Data retrieval using the `yfinance` library  
3. Data preprocessing and feature selection  
4. Model training using Linear Regression 
5. Prediction of next-day closing prices  
6. Model evaluation using error metrics  
7. Visualization of actual vs predicted prices  

---

## Evaluation Metrics
The model performance is evaluated using the following metrics:

- **Mean Absolute Error (MAE)**  
  Measures the average absolute difference between actual and predicted prices.

- **Root Mean Squared Error (RMSE)**  
  Penalizes larger errors and highlights prediction deviations.

These metrics help assess how accurately the model predicts stock prices in real monetary terms.

---

## Key Findings
- The regression model captures short-term trends in Apple’s stock prices.
- Predictions closely follow actual closing prices for most trading days.
- Larger errors may occur during periods of high market volatility.
- The model demonstrates that machine learning can be effectively used for short-term stock price prediction.

---

## Conclusion
This project highlights the effectiveness of machine learning regression models for short-term stock price forecasting.  
While market volatility remains a challenge, the results show promising predictive capability using historical price data.

---

## Author
**Rizwan**
