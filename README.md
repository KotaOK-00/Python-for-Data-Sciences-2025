# Python-for-Data-Sciences-2025
Final project for Python for Data Sciences 2025 (APM_51658_EP) in IP Paris M1 Applied Mathematics and Statistics. 

## Authors
* Kota OKUDA
* Ryunosuke TANAKA

## Overview
In financial time series forecasting, accurate point prediction is often insufficient for risk management and quantifying the associated uncertainty is equally critical. This project provides a framework for Uncertainty Quantification (UQ) using Long Short-Term Memory (LSTM) combined with Monte Carlo dropout. We apply this to the daily closing prices of corn futures to analyse several types of predictive variances. Specifically, we decompose the total uncertainty into three components: model (epistemic), data (aleatoric), and temporal diffusion. Our experiments investigate the impact of look-back windows, look-ahead horizons, and data amount on these components. The results indicate that whilst temporal diffusion becomes the dominant source of uncertainty in multi-step forecasting, the choice of look-back window affects model performance; excessively long histories (e.g., 120 days) may introduce outdated noise, whereas moderate windows (e.g., 60 days) offer a better balance. Furthermore, the derived uncertainty intervals dynamically expand during high-volatility periods, such as the COVID-19 pandemic, demonstrating the method's efficacy in capturing market risks.
