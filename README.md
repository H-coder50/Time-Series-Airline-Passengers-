# **📈 Airline Passengers Time Series Forecasting**
### **🗂 Project Overview:**

This project demonstrates a complete time series forecasting workflow using the classic AirPassengers dataset. The dataset contains monthly totals of international airline passengers from January 1949 to December 1960. It is ideal for exploring trend, seasonality, and time series modeling techniques.

### **📦 Dataset Description:**
- Source: AirPassengers dataset
- Time Range: 1949–1960
- Frequency: Monthly
- Target Variable: Number of airline passengers
- Format: Time-indexed numerical series

### **🔍 Step-by-Step Workflow:**
- **Load & Understand Data:**
  - Load the dataset and inspect its structure
  - Confirm time-indexed format and check for missing values
- **Visualize Time Series:**
  - Plot the raw data
- **Observations:**
  - Upward trend over time
  - TimeSeries Decomposition
  - Trend, Seasonal, Residual
### **Stationarity Check:**
- Apply ADF Test to assess stationarity
### **Make Data Stationary:**
- Log transformation (stabilize variance)
- Differencing (remove trend)
### **Model Selection & Training:**
- SARIMA Model
### **Forecasting & Evaluation:**
- Plot Forecast vs Original Data
### **Conclusion:**
The air passenger data and forecast together indicate a clear long-term growth trend in air travel, with consistent seasonal cycles continuing into the future. 
This suggests rising demand for air transportation, driven by both steady expansion and predictable seasonal peak.
