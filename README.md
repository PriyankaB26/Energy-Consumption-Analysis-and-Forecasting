# Energy-Consumption-Analysis-and-Forecasting
Hourly energy consumption analysis of multiple companies using Power BI. Data of multiple companies were combined, processed, and transformed to extract key insights, create visualizations, and forecast energy usage for next years.
**Motivation / Problem Statement:**
The project aims to analyze hourly energy consumption data across multiple companies. The primary objectives are:
Identify consumption patterns and trends over time (time series analysis).
Compare electricity demand across companies to see which areas have higher/lower customer load.
Forecast future demand using historical data to anticipate next year’s energy requirements.
**Data Sources**
The datasets used in this project were obtained from publicly available sources:
https://www.kaggle.com/code/arezoodahesh/hourly-energy-consumption-with-prophet/input
Key Columns: 
Datetime → Hourly timestamps of energy consumption
Load (MW) → Electricity demand/load in megawatts,Company 
**Data Processing & Preparation:**
Used Power Query transformations to create new columns for analysis including company name.
Stacked datasets from multiple companies into a single table.
Extracted information from the Datetime column (Hour, Day, IsWeekend, Seasons, Quarter).
**Analysis & Visualization**
Created interactive Power BI dashboards to explore energy consumption trends over time and different companies.
Visualized:
Total electricity load analyzed at yearly, quarterly, monthly, weekly, daily, and seasonal levels for each company.
Analyzed total electricity load across companies and explored hourly demand patterns.
Insights:
Understanding when electricity demand is highest/lowest (hour of day, day of week, month, season).
How demand changes across years (trends: growing, declining, stable).
Which companies/regions have higher or lower electricity demand.
Forecasting → project future demand based on past usage patterns.
**Forecasting:**
Used Power BI built-in forecasting to predict next year’s energy consumption.
**Future Work**:
Could incorporate predictive modeling in Python with time series models like ARIMA,LSTM to improve forecasting beyond Power BI’s built-in models.
Use external data sources (calendar events, temperature, weather, renewable energy production, etc.) to make demand predictions more accurate.



