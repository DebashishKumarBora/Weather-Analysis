# Weather Analysis Project

## Introduction

This project involves analyzing historical weather data from 1980 to 2024 to identify patterns, trends, and anomalies. The analysis includes data cleaning, exploratory data analysis (EDA), and time series forecasting using various statistical methods.

## Data Overview

The project utilizes two datasets: hourly and daily weather data recorded between 1980 and 2024. These datasets encompass critical variables such as temperature, relative humidity, and other pertinent features, serving as essential resources for comprehensive weather analysis and forecasting.

## Research Objective

The objective of this project is to:
1. Clean and preprocess the weather datasets.
2. Perform exploratory data analysis to understand the data.
3. Conduct time series analysis and forecasting.
4. Derive insights and provide actionable suggestions based on the analysis.

## Data Cleaning

Both the hourly and daily datasets were cleaned by:
- Dropping rows with missing values.
- Removing duplicate rows.
- Converting the time column to datetime format for accurate time series analysis.

## Exploratory Data Analysis (EDA)

### Summary Statistics

Summary statistics were calculated for both the hourly and daily datasets to understand the distribution and key characteristics of the data.

### Temperature Over Time (Hourly)

![temperature_over_time_hourly](https://github.com/user-attachments/assets/97e3dc80-7231-4c3e-9d6a-fcf276d220ef)

*Description:* This line chart shows the variation in temperature over time for the hourly dataset.

### Distribution of Temperatures (Hourly)

![Distribution of Temperatures Hourly](https://github.com/user-attachments/assets/4db963e6-915d-4f1c-a04d-7f641628683f)

*Description:* This histogram shows the distribution of temperatures in the hourly dataset.

## Time Series Analysis


### Seasonal Decomposition

![seasonal decomposition](https://github.com/user-attachments/assets/f31b096d-0c83-4537-8de1-1a253cf7bf5d)

*Description:* This plot shows the decomposition of the temperature time series into trend, seasonal, and residual components.

### Exponential Smoothing Forecast

![Screenshot 2024-07-10 235529](https://github.com/user-attachments/assets/ecd5a120-321a-4067-8459-b75d2a211173)

*Description:* This plot shows the observed temperatures and the forecasted values using exponential smoothing.

### SARIMA Forecast (Recent 5 Days)

![Screenshot 2024-07-10 235757](https://github.com/user-attachments/assets/3be18f78-59bc-4be6-a695-187da5b2ac8a)

*Description:* This plot shows the observed temperatures and the forecasted values using the SARIMA model.

### Moving Average

![Screenshot 2024-07-11 000028](https://github.com/user-attachments/assets/a5f08ba4-0376-4b82-9503-63fa7d221fa5)

![Screenshot 2024-07-11 000159](https://github.com/user-attachments/assets/0fcb8c80-f5af-4888-893c-ecdbb41df521)

*Description:* This plot shows the temperature time series along with its moving average.

### Average Temperature by Hour of the Day

![Screenshot 2024-07-11 000258](https://github.com/user-attachments/assets/34050977-71b2-4f52-af58-95b8d5f845e0)

*Description:* This bar chart shows the average temperature for each hour of the day.

### Temperature vs. Relative Humidity

![Screenshot 2024-07-11 000521](https://github.com/user-attachments/assets/8fc05090-a4ff-4c77-9851-ab3145a38d64)

*Description:* This scatter plot shows the relationship between temperature and relative humidity.

## Observations

- **Temperature Trends:** The data shows clear seasonal trends and periodic fluctuations in temperature.
- **Temperature Distribution:** The temperature distribution is approximately normal with some skewness.
- **Forecast Accuracy:** Both exponential smoothing and SARIMA models provide accurate short-term forecasts.
- **Daily Patterns:** Average temperatures vary significantly throughout the day, with the highest values in the afternoon.
- **Humidity Relationship:** Temperature and relative humidity have an inverse relationship.

## Implications

- **Seasonal Patterns:** Understanding seasonal patterns can help in better planning and preparedness for weather-related events.
- **Forecasting:** Accurate short-term forecasts can aid in decision-making for agriculture, energy consumption, and event planning.
- **Daily Temperature Variations:** Knowing daily temperature patterns can be useful for activities such as irrigation scheduling and optimizing HVAC systems.

## Suggestions

- **Enhanced Data Collection:** Collect more granular data for improved analysis and forecasting.
- **Advanced Models:** Explore more advanced machine learning models for better long-term forecasts.
- **Integration:** Integrate weather forecasts with other data sources (e.g., crop yields, energy usage) for more comprehensive insights.

## Conclusion

This project demonstrates the process of cleaning, analyzing, and forecasting weather data. The findings provide valuable insights into temperature trends, daily patterns, and the relationship between temperature and humidity. The suggested improvements and implications highlight the potential for further research and practical applications of the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Debashish Kumar Bora](github.com/DebashishKumarBora) - Author
