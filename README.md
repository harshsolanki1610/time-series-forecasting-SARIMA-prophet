Time Series Forecasting using SARIMA and Prophet

Overview

This project focuses on forecasting future sales using historical supermarket order data.
Time series forecasting is a technique used to predict future values by analyzing patterns such as trend, seasonality, and past behavior over time.

The goal of this project was to understand how classical statistical models and modern forecasting tools perform on real-world sales data.

⸻

Dataset

I used historical supermarket sales/order data containing timestamps and past sales values.
Since the data is time-dependent, maintaining chronological order was critical for accurate forecasting.

⸻

Models Used

1. SARIMA (Seasonal ARIMA)

SARIMA is a statistical model designed specifically for time series data with seasonality.
It captures:
	•	Trend over time
	•	Seasonal patterns (e.g., monthly demand cycles)
	•	Autocorrelation between past and future values

2. Prophet

Prophet is a forecasting library developed for handling real-world time series data with strong seasonal effects and missing values.
It automatically models:
	•	Trend changes
	•	Multiple seasonalities
	•	Holiday or event-based effects

⸻

Workflow
	1.	Data cleaning and datetime formatting
	2.	Visualizing trends and seasonal patterns
	3.	Making the series stationary (for SARIMA)
	4.	Training SARIMA model
	5.	Training Prophet model
	6.	Forecasting future sales
	7.	Comparing predictions and model behavior

⸻

Results & Comparison
	•	SARIMA performed well when the seasonal structure was clearly defined and consistent.
	•	Prophet was easier to implement and more flexible for capturing trend shifts and irregularities.
	•	Both models produced meaningful forecasts, showing how different approaches can solve the same forecasting problem.

This comparison helped me understand when to use statistical modeling vs. automated forecasting tools.

⸻

Real-Life Applications

Time series forecasting like this is widely used in:
	•	Predicting monthly or seasonal sales for retail businesses
	•	Estimating growth of YouTube/Instagram followers over time
	•	Forecasting stock prices and financial trends
	•	Planning inventory for fast-moving consumer goods (FMCG)
	•	Analyzing website traffic and user engagement
	•	Demand planning based on seasonal behavior

⸻

What I Learned
	•	How time series data differs from traditional ML datasets
	•	Importance of seasonality and trend analysis
	•	Stationarity concepts and parameter tuning in SARIMA

⸻
	•	Practical advantages of Prophet for real-world forecasting
	•	How forecasting can directly support business decision-making
