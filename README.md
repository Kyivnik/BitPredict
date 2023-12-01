# BitPredict - Time Series Forecasting in TensorFlow

Welcome to BitPredict, the focus of Milestone Project 3! In this notebook, we delve into the fascinating realm of time series data, aiming to build models capable of predicting the price of Bitcoin.

## Project Overview

### Understanding Time Series Problems

Time series problems involve the analysis of data over time. This could encompass a variety of scenarios, such as tracking the number of staff members in a company over 10 years, monitoring computer sales over the past 5 years, or examining electricity usage patterns over the past 50 years. Timelines can range from short (seconds/minutes) to long (years/decades), with problems typically falling into two categories:

1. **Classification:** Examples include anomaly detection and time series identification (identifying the source of a time series). The output is discrete, represented by a label.

2. **Forecasting:** Involves predicting continuous values, such as stock market prices, future demand for a product, or inventory requirements.

### What We're Going to Cover

Buckle up, as we've got an exciting journey ahead! Here's a sneak peek into what we'll be covering:

1. Acquiring time series data (historical Bitcoin prices).
2. Loading time series data using pandas/Python's CSV module.
3. Formatting data for a time series problem.
4. Creating training and test sets (the right way).
5. Visualizing time series data.
6. Transforming time series data into a supervised learning problem (windowing).
7. Preparing univariate and multivariate data.
8. Evaluating a time series forecasting model.
9. Setting up a series of deep learning modeling experiments, including dense (fully-connected) networks, sequence models (LSTM and 1D CNN), ensembling, and multivariate models.
10. Replicating the N-BEATS algorithm using TensorFlow layer subclassing.
11. Implementing a modeling checkpoint to save the best-performing model during training.
12. Making predictions (forecasts) with a time series model.
13. Creating prediction intervals for time series model forecasts.
14. Discussing two types of uncertainty in machine learning (data uncertainty and model uncertainty).
15. Examining why forecasting in an open system can be challenging (the turkey problem).

