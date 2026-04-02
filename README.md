# time-series-sales-forecast
Time series sales forecasting project using ARIMA and SARIMA with future prediction and sales pattern analysis.

##Steps Performed

1. Data Preprocessing
Converted Sale_Date to datetime format
Sorted data based on date
Aggregated sales on a daily level
Handled missing dates using forward fill

2. Time Series Modeling
🔹 ARIMA Model
Used ARIMA(1,1,1) as a baseline model
Captures trend and short-term dependencies
🔹 SARIMA Model
Added seasonal component (weekly pattern)
Compared performance with ARIMA

3.Model Evaluation
Used RMSE (Root Mean Squared Error)
Compared ARIMA and SARIMA predictions
Selected the better-performing model

4. Future Forecasting
Predicted sales for the next 30 days
Helps in planning and decision making
Feature Engineering & Insights
#Extracted:
Day of week
Month
Weekend indicator
#Analyzed:
Day-wise sales patterns
Monthly trends
Weekend vs weekday performance

5.Key Observations
Sales show a clear trend over time
Weekly patterns are visible in the data
Weekend sales tend to differ from weekdays
Seasonal models (SARIMA) often perform better

6.Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Statsmodels
Scikit-learn
