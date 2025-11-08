# 🌦️ Weather Data Analysis with Pandas

This project demonstrates how to use the pandas library to load, explore, and analyze weather data from 122 Weather Forecast Offices across the United States. The dataset is provided by the [CORGIS Project](https://corgis-edu.github.io/corgis/csv/weather/).

## 📁 Dataset

- **Source:** [weather.csv](https://corgis-edu.github.io/corgis/csv/weather/)
- **Description:** Weekly weather reports including temperature, precipitation, wind speed, and location metadata.

## 🧪 Tasks

### 1. Data Loading and Exploration

- Load the dataset using pandas
- Display the first 5 rows
- Show dataset dimensions and column data types

### 2. Data Analysis and Aggregation

Focus on the Philadelphia, PA weather station:

- Calculate average temperature
- Identify hottest and coldest days
- Compute total precipitation
- Count rainy days (precipitation > 0)

### 3. Bonus Challenge

Create a reusable function:

```python
summarize_weather_by_station(station_code, df)
