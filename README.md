# BitPredict
Time Series Forecasting in TensorFlow
:

📈 BitPredict: Time Series Forecasting in TensorFlow
BitPredict is a project focused on building deep learning models to forecast Bitcoin prices using time series data and TensorFlow.

⚠️ Disclaimer: This project is for educational purposes only and does not constitute financial advice.

🧠 Overview
This project explores the challenges of time series forecasting through real-world data.
We build, evaluate, and compare a series of deep learning models, highlighting both the possibilities and limitations of predicting market prices.

📚 What’s Covered
Understanding time series problems

Correct methods for splitting time series data into training and test sets

Visualizing time series trends

Transforming time series into supervised learning problems (windowing)

Working with univariate and multivariate time series

Evaluating forecasting models

Building and experimenting with deep learning models:

Dense Neural Networks (DNNs)

LSTM networks

1D Convolutional Networks

Ensemble models

Multivariate models

Replicating the N-BEATS architecture

Setting up model checkpointing

Making and evaluating forecasts

Creating prediction intervals

Understanding uncertainty in machine learning

Discussing challenges of forecasting in open systems (the "turkey problem")

🏗 Models Built
Baseline (naive) models

Fully connected (dense) models

LSTM sequence models

1D CNNs for time series

Ensemble models

Multivariate time series models

Custom N-BEATS model (TensorFlow layer subclassing)

📂 Project Files
10_time_series_forecasting_in_tensorflow.ipynb — Main notebook with code, experiments, and results.

🚀 Setup
Requirements:

Python 3.8+

TensorFlow 2.x

NumPy, Pandas, Matplotlib

Jupyter Notebook or Google Colab

🎯 Key Takeaways
Forecasting time series, especially financial markets, is complex and filled with uncertainty.

Deep learning models can model trends, but they have limitations in chaotic, real-world environments.

Understanding uncertainty and model limitations is crucial when building forecasting systems.

