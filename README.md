# Forecasting-the-price-electricity-in-Spain-using-Deep-Learning-
Different tasks involved in this project :

1) Data Exploration and Preparation:

• Conducted thorough data exploration and cleaning of energy and weather datasets.

• Filled missing values with Forward Linear Interpolation and merged energy and weather datasets for analysis.


2) Time Series Analysis:

•	Analyzed electricity price data using decomposition and stationarity tests. (ADF and KPSS tests)

•	Conducted autocorrelation, partial autocorrelation, and cross-correlation analyses.


3) Feature Engineering:

•	Generated and selected relevant features for the deep learning models.

•	Extracted features using PCA to optimize model performance.

4) Model Development and Evaluation:

•	Developed deep neural network models using LSTM, stacked LSTM, CNN, CNN-LSTM.

•	Compared the performance of these models for both univariate and multivariate forecasting.

•	Evaluated model performance using the Root Mean Squared Error performance metric:

RMSE of hour-ahead electricity price XGBoost forecast: 2.214

LSTM forecast: 2.265

multivariate Stacked LSTM forecast: 2.348

multivariate CNN forecast: 2.324

multivariate CNN-`LSTM forecast: 2.309


Overall, this project involved developing and testing different deep neural network models for electricity price forecasting using past electricity price data, energy generation data, and weather conditions. The project also included thorough data exploration, time series analysis, and feature engineering to optimize model performance.
