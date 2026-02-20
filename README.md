# Sales Forecasting Using SARIMA and Prophet

## Problem
Organizations rely on accurate sales forecasts to plan inventory, logistics, and marketing strategies. Time-series data contains trends and seasonal behavior that must be modeled carefully.

## Approach
This project compares two different forecasting techniques:
- SARIMA, a statistical time-series model.
- Prophet, a forecasting library designed to handle seasonality and trend changes.

The goal was to understand how both approaches behave on the same dataset and when each method is more suitable.

## Tools and Technologies
- Python  
- Pandas for time-series preparation  
- Statsmodels for SARIMA implementation  
- Prophet for forecasting  
- Matplotlib for visualization  

## Workflow
1. Prepared historical supermarket sales data and aggregated it monthly.
2. Analyzed trend and seasonal patterns in the dataset.
3. Split the data into training and testing periods.
4. Trained the SARIMA model using identified parameters.
5. Built a Prophet model for comparison.
6. Generated forecasts and evaluated how each model captured patterns.

## Observations
SARIMA performed well for structured seasonal behavior, while Prophet was more flexible in capturing overall trends and shifts.

## What I Learned
This project strengthened my understanding of time-series analysis, model selection, and how statistical and machine learning approaches differ in forecasting tasks.

## Future Improvements
- Introduce cross-validation for more robust evaluation.
- Extend forecasting to finer time intervals.
- Build an interactive dashboard for visualization.
	•	Practical advantages of Prophet for real-world forecasting
	•	How forecasting can directly support business decision-making
