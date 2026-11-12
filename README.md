# Pairs-Trading-Algorithm
Time Series forecasting using a mean reversion strategy and normalised data analysis


Quantitative Pairs Trading Framework

This project develops a Python-based quantitative pairs trading framework designed to identify potential statistical arbitrage opportunities within equity markets. Using historical stock price data retrieved through Yahoo Finance, it systematically screens combinations of equities for statistically significant long-term relationships. The framework applies the Engle-Granger cointegration test and Augmented Dickey-Fuller (ADF) tests, using a 5% significance threshold to identify candidate pairs that may exhibit mean-reverting behaviour.

The framework performs statistical analysis by calculating cointegration p-values, normalised prices, relative price ratios and Z-scores to evaluate deviations from historical relationships. It also incorporates rolling Simple Moving Averages (SMA), Exponential Moving Averages (EMA) and standard deviations to examine changing market behaviour over time. Matplotlib and Seaborn visualisations provide insights into relative price movements, statistical deviations and potential mean-reversion patterns.

Built using Python, Pandas, NumPy, yfinance, Statsmodels, Matplotlib and Seaborn, this project combines financial data acquisition, statistical hypothesis testing, time-series analysis and data visualisation into a reusable quantitative research framework. It provides a foundation for further exploration of systematic trading strategies, with potential future extensions including backtesting, transaction-cost modelling, portfolio optimisation and machine learning applications. This project is intended for educational and quantitative research purposes.
