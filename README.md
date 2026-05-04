# Evaluating the Incremental Impact of Feature Engineering on LSTM-Based Stock Price Prediction: A NIFTY 50 Study

📊 Evaluating the Incremental Impact of Feature Engineering on LSTM-Based Stock Price Prediction: A NIFTY 50 Study

This project presents a comprehensive analysis of stock market prediction using machine learning techniques, leveraging historical financial data obtained from Yahoo Finance. The study focuses on preprocessing, exploratory data analysis (EDA), and preparing datasets for advanced predictive models such as LSTM.

🚀 Project Overview:

Stock market prediction is a challenging task due to the highly volatile and non-linear nature of financial data. This project aims to explore how machine learning models can be applied to forecast stock price movements using historical OHLCV (Open, High, Low, Close, Volume) data.

The dataset is fetched programmatically using the Yahoo Finance API via the yfinance library, ensuring reproducibility and up-to-date financial data.

📥 Data Collection

Data Source: Yahoo Finance (yfinance)

Index Used: NIFTY 500 (or specified ticker)

Time Period: Last 10 years

Frequency: Daily stock data



🧹 Data Preprocessing

The notebook includes a detailed preprocessing pipeline:

Cleaning raw CSV data

Handling missing and duplicate values

Converting data types to numeric formats

Parsing and indexing datetime values

Sorting time-series data

Feature preparation for modeling



📊 Exploratory Data Analysis (EDA)

Extensive EDA is performed to understand trends and relationships:

Yearly resampling and aggregation

Visualization of Open, High, Low, Close prices

Trading volume analysis

Correlation heatmaps between features

Volatility analysis (High–Low range)

Percentage change trends

Pairwise feature relationships



🤖 Machine Learning Models (Planned / Implemented):

The project explores deep learning approaches for time-series forecasting:

LSTM with OHLCV features

LSTM with Moving Averages

LSTM with Technical Indicators

RSI (Relative Strength Index)

MACD (Moving Average Convergence Divergence)

Bollinger Bands

These models aim to capture temporal dependencies and improve prediction accuracy.



📈 Key Features:

End-to-end pipeline from data collection to model-ready dataset

Financial time-series visualization

Feature engineering using technical indicators

Scalable framework for experimenting with multiple ML models



🛠️ Tech Stack:

Python

Pandas & NumPy

Matplotlib & Seaborn

yFinance API

TensorFlow / Keras (for LSTM models)



📌 Future Improvements:

Implementation of additional ML models (e.g., Random Forest, XGBoost)

Model performance comparison and evaluation metrics

Hyperparameter tuning

Deployment as a web app or API


📎 Conclusion:

This project serves as a foundational framework for stock market prediction using machine learning. It highlights the importance of data preprocessing, feature engineering, and time-series modeling in financial forecasting.
