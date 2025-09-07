# Energy Consumption Analysis and Forecasting  

Hourly energy consumption analysis of multiple companies using Power BI.  
Data of multiple companies were combined, processed, and transformed to extract key insights, create visualizations, and forecast energy usage for future years.  

---

## Motivation / Problem Statement  
The project aims to analyze hourly energy consumption data across multiple companies. The primary objectives are:  
- Identify consumption patterns and trends over time (**time series analysis**)  
- Compare electricity demand across companies to see which areas have higher/lower customer load  
- Forecast future demand using historical data to anticipate next year’s energy requirements  

---

## Data Sources  
The datasets used in this project were obtained from publicly available sources:  
- [Hourly Energy Consumption (Kaggle)](https://www.kaggle.com/code/arezoodahesh/hourly-energy-consumption-with-prophet/input)  

**Key Columns:**  
- **Datetime** → Hourly timestamps of energy consumption  
- **Load (MW)** → Electricity demand/load in megawatts  
- **Company** → Utility provider

---

## Data Processing & Preparation  
- Used **Power Query** transformations to create new columns for analysis (e.g., Company name)  
- Stacked datasets from multiple companies into a single table  
- Extracted information from the Datetime column: **Hour, Day, IsWeekend, Season, Quarter**  

---

## Analysis & Visualization  
Created **interactive Power BI dashboards** to explore energy consumption trends over time and across companies.  

**Visualizations include:**  
- Total electricity load analyzed at **yearly, quarterly, monthly, weekly, daily, and seasonal** levels for each company  
- Company-wise comparison of electricity load  
- Hourly demand patterns of electricity usage  

---

## Insights  
- Electricity demand varies significantly by **hour of day, day of week, and season**  
- Demand shows clear **weekday vs weekend differences**  
- Some companies/regions exhibit **higher overall demand** compared to others  
- Long-term trend analysis reveals whether demand is **growing, declining, or stable**  
- Forecasting highlights **expected energy demand for the upcoming year**  

---

## Forecasting  
- Used **Power BI built-in forecasting** to project next year’s energy consumption  

---

## Future Work  
- Incorporate **predictive modeling in Python/R** using time-series models (e.g., ARIMA, LSTM, Prophet) to enhance accuracy  
- Use **external data sources** (calendar events, temperature, weather, renewable energy production, etc.) for more reliable forecasting  
- Expand the dataset to include **additional companies or regions**
  
<p align="center">
  <img src="Energy%20consumption%20by%20companies.png" alt="Energy Consumption by Companies" width="300"/>
  <img src="Energy%20consumption%20over%20time.png" alt="Energy Consumption Over Time" width="300"/>
  <img src="Load%20Forecasting.png" alt="Load Forecasting" width="300"/>
</p>
