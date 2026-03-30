# Analysis of Time Series

This repository contains a series of projects focused on identifying, modeling, and forecasting time-dependent data. The analyses use both simulated processes and real-world economic indicators, such as the `euretail` dataset.

# Report 1
This project focuses on distinguishing between random white noise and structured data. It covers both visual diagnostics (ACF plots) and formal statistical tests, such as Box-Pierce and Ljung-Box. Through Monte Carlo simulations, the study evaluates how sample size ($n$) and lag selection ($h_{max}$) affect the reliability of these tests in detecting non-random structures like Random Walk or MA(1) processes.

# Report 2
This report presents a complete forecasting workflow using the `euretail` dataset (Eurozone retail trade index). The process includes data stabilization through Box-Cox transformations and seasonal differencing. It compares three major forecasting approaches: (S)ARIMA, Exponential Smoothing (ETS), and Decomposition methods. The models are evaluated based on residual diagnostics and accuracy metrics, including RMSE, MAE, and MAPE.
