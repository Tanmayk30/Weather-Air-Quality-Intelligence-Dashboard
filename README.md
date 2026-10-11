# 🌦️ Real-Time Weather & Air Quality Intelligence Dashboard

## 📌 Overview

An interactive Power BI dashboard that combines current weather conditions, 7-day forecasts, sunrise and sunset timings, and air quality indicators across multiple cities. The project uses WeatherAPI, Power Query, and DAX to transform weather data into an interactive visual experience.

## 📸 Dashboard Preview

![Weather Dashboard](Images/dashboard.png)

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query (M)
- DAX
- WeatherAPI (REST API and JSON)

## ✨ Key Features

- **City Selection:** Explore weather conditions across multiple cities.
- **Current Weather:** View temperature, humidity, wind speed, visibility, atmospheric pressure, and UV index.
- **7-Day Forecast:** Compare forecast conditions and temperature trends.
- **Sunrise & Sunset:** View daily sunrise and sunset timings.
- **Rain Probability:** Analyze the forecast chance of precipitation.
- **Air Quality Monitoring:** Track PM2.5, PM10, CO, NO₂, O₃, and SO₂ using color-coded indicators and contextual health advisories.

## 🔄 Data Preparation & Modeling

WeatherAPI data is retrieved in JSON format and transformed using Power Query. The data is cleaned, data types are standardized, duplicate records are handled, and current weather and forecast information are organized into related tables.

A location-based data model connects the tables, while DAX supports dynamic metrics, formatting, and pollutant indicators.

## 📁 Project Files

- [**Download the Power BI Dashboard (.pbix)**](Files/Weather%20Dashboard.pbix)
- [View Dashboard Screenshot](Images/dashboard.png)

Download the Power BI file and open it using Power BI Desktop. Data freshness depends on the report's refresh configuration and API access.

## ⚠️ Air Quality Note

The dashboard uses custom PM10-based thresholds for its color indicators and health advisories. These are not an official EPA AQI calculation.

## 📚 Tutorial Acknowledgment

This project was developed by following and adapting concepts from The Developer BI's tutorial:

[Best Power BI Project End to End | Data Analyst Project (1 Hour)](https://www.youtube.com/watch?v=P8HB8dMfKNc)

The final dashboard reflects my implementation and design choices.

---

**Created by Tanmay Khandait**

[LinkedIn](https://www.linkedin.com/in/tanmay-khandait-45914b224) · [GitHub](https://github.com/Tanmayk30)
