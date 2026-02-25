# Gold-Price-Time-Series-Forecasting-2016-2026-
Time series analysis and gold price forecasting using Prophet and ML models (2016–2026).

📌 Project Overview

This project presents a comprehensive time series analysis and forecasting study of global gold prices using 10 years of historical daily data. Gold plays a critical role as a safe-haven asset, inflation hedge, and economic stability indicator. Understanding its historical behavior and predicting future trends is essential for investors and financial analysts.

The primary objective of this project is to analyze price patterns, identify structural shifts, and generate reliable forecasts through March 2026 using statistical modeling and Facebook Prophet.

📊 Dataset Information

Time Period: 2016 – 2026

Frequency: Daily

Observations: ~2500 trading days

Features:

Open, High, Low, Close

Volume

Daily Returns

🔎 Exploratory Data Analysis (EDA)

Key insights from EDA:

Gold prices exhibit a strong long-term upward trend.

Significant structural surge (~86%) observed during 2025–2026.

Volatility increased during surge periods.

Price movements are highly autocorrelated and trend-dominant.

Statistical tests performed:

Augmented Dickey-Fuller (ADF) test for stationarity

Time series decomposition (trend, seasonality, residuals)

Correlation analysis

Seasonality analysis (monthly & weekly patterns)

🤖 Machine Learning Models Tested

To compare forecasting performance, multiple ML models were trained:

Linear Regression

Ridge Regression

Random Forest

Gradient Boosting

Feature engineering included:

Lag features

Rolling statistics

RSI

MACD

Bollinger Bands

Finding:
Linear models significantly outperformed tree-based ensemble models, highlighting the strong linear trend component in gold prices.

🔮 Facebook Prophet Model

Facebook Prophet was used for advanced time series forecasting due to its ability to:

Automatically detect trend changepoints

Model yearly, weekly, monthly, and quarterly seasonality

Provide interpretable forecast components

Generate confidence intervals

Custom seasonalities were added for improved modeling accuracy.

📈 Forecast Through March 2026

The Prophet model generated forecasts including:

Predicted price trajectory

95% confidence intervals

Monthly forecast summaries

The forecast suggests continued elevated price levels with increasing uncertainty bands toward 2026, reflecting potential macroeconomic instability.

📊 Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Mean Absolute Percentage Error (MAPE)

Key Insight:

Model complexity does not guarantee better performance. Understanding data structure and trend dynamics is more important than using complex algorithms.

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Plotly

Scikit-learn

Statsmodels

Facebook Prophet

🎯 Key Takeaways

Gold prices are strongly trend-driven and non-stationary.

The 2025–2026 surge represents a structural market shift.

Linear time-dependent models outperform ensemble ML models.

Prophet effectively captures trend changes and seasonality.

Forecasting uncertainty increases with longer time horizons.

🚀 Business Impact

This project demonstrates how time series modeling can support:

Investment strategy development

Risk assessment

Financial forecasting

Macro trend analysis

Moving Averages (20, 50, 200)

Rolling Volatility
