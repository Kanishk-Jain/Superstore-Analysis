# Superstore-Analysis
Project Overview
We analyzed transactional sales data across three branches that are A, B, and C, to identify future performance patterns and business potential. After conducting exploratory data analysis and time-based aggregations, we implemented and compared multiple forecasting models, including:

1. Linear Regression

2. ARIMA

3. SARIMA

4. Facebook Prophet

Following comparative performance evaluation using metrics like MAE, RMSE, and R² Score, Facebook Prophet demonstrated superior accuracy and trend detection capabilities. Thus, it was selected as the final model for generating forecasts up to 2026.

Key Tasks Performed
1. Preprocessed and transformed raw sales data into a time-series format.

2. Built forecasting pipelines for each branch individually.

3. Evaluated multiple models and selected Prophet based on validation performance.

4. Generated rolling-mean smoothed predictions to highlight seasonal quarterly trends.

5. Visualized results in Matplotlib and built an interactive Tableau Dashboard to present business insights.

Technologies & Tools Used
-> Languages: Python

-> Libraries: Pandas, Matplotlib, Prophet

-> Evaluation Metrics: MAE, RMSE, R²

Outcome
-> Branch C emerged as the strongest future performer based on forecasted trends. These insights can guide inventory planning, resource allocation, and marketing efforts across branches.
