<!-- PROJECT BANNER -->
<p align="center">
  <img src="images/flight_delay_banner.png" alt="Flight Delay Analysis Banner" width="800">
</p>

<h1 align="center">✈️ SKYTIME INSIGHTS – FLIGHT DELAY ANALYSIS</h1>
<p align="center">
  <em>Analyzing U.S. flight delays to reveal performance trends, seasonal patterns, and major causes.</em>
</p>

---

## 🌍 Overview
Every minute counts in aviation.  
This project explores U.S. flight data to uncover **when**, **where**, and **why** delays occur — transforming raw data into actionable insights.  

Through exploratory data analysis (EDA) and visualization, we identify delay patterns by **airline**, **airport**, **season**, and **delay cause**.

---

## 🎯 Objectives
- Uncover flight delay trends by **airline**, **airport**, and **time of day**.  
- Analyze the **root causes** of delays (weather, carrier, NAS, late aircraft, etc.).  
- Build **KPI metrics** and visualize performance across dimensions.  
- Identify **patterns and hotspots** to improve scheduling and efficiency.  

---

## 📊 KAGGLE NOTEBOOK
Explore the live notebook for detailed analysis, visualizations, and results:

👉 [**View Full Kaggle Notebook**](https://www.kaggle.com/code/digvijayrajput14/flight-delay-analysis)

**Notebook Includes:**
- Step-by-step EDA and visualization workflow  
- Data cleaning and transformation pipeline  
- KPI metrics and airline performance dashboard  
- Delay cause breakdown and seasonal analysis  

---

## 🗂️ DATASET SOURCE
The dataset used for this analysis is publicly available on Kaggle:

📦 [**U.S. Flight Delays Dataset**](https://www.kaggle.com/datasets/usdot/flight-delays)

**Dataset Overview:**
- Source: U.S. Department of Transportation  
- Time Period: One year of domestic flights  
- Key Columns:  
  - `AIRLINE`, `ORIGIN_AIRPORT`, `DEST_AIRPORT`  
  - `ARRIVAL_DELAY`, `DEPARTURE_DELAY`, `IS_DELAYED`  
  - `CARRIER_DELAY`, `WEATHER_DELAY`, `NAS_DELAY`, `LATE_AIRCRAFT_DELAY`  

---

## ⚙️ Tools & Libraries
🧠 **Python Stack:**  
`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

💻 **Environment:**  
Jupyter Notebook / Kaggle  

---

## 📊 Exploratory Insights

### 1️⃣ Delay Rate by Airline
![Delay Rate by Airline](images/delay_rate_by_airline.png)
> Visualizes which airlines face the highest percentage of delayed flights.

---

### 2️⃣ Average Arrival Delay by Hour
![Average Delay by Hour](images/avg_delay_by_hour.png)
> Reveals peak delay hours — typically late afternoon and evening flights.

---

### 3️⃣ Monthly Delay Trends
![Monthly Delay Trend](images/monthly_delay_rate.png)
> Shows seasonal patterns — summer months experience more delays.

---

### 4️⃣ Delay Causes Breakdown
![Delay Causes](images/delay_causes.png)
> Compares major delay types — carrier, weather, NAS, and late aircraft delays.

---

### 5️⃣ Airline vs. Cause Heatmap
![Airline vs Cause](images/airline_vs_cause_heatmap.png)
> Identifies which airlines are most affected by specific delay causes.

---

## 📈 KPI Dashboard
| Metric | Insight |
|---------|----------|
| **Total Flights** | Number of flights analyzed |
| **Delay Rate (%)** | Overall percentage of delayed flights |
| **Avg. Arrival Delay (min)** | Mean delay duration |
| **Worst Airline** | Airline with highest average delay |
| **Peak Delay Month** | Month with highest delay rate |

---

## 💡 Key Insights
- ✈️ Evening flights experience **higher average delays**.  
- 🌦️ **Summer months** show the most delay frequency.  
- 🔁 **Late aircraft** and **carrier issues** are the top delay causes.  
- 🚨 Certain airlines consistently perform below average in punctuality.  

---

## 🧹 Data Cleaning Summary
- Removed duplicates and irrelevant columns  
- Handled missing values in delay columns  
- Converted date/time columns to standard formats  
- Created derived features like `IS_DELAYED`, `CRS_DEP_HOUR`, and `MONTH_NAME`  
- Standardized column names and validated clean data  

---

## 🚀 Future Enhancements
- Predict flight delays using **machine learning models**.  
- Create an **interactive dashboard** (Power BI / Plotly Dash).  
- Automate monthly **KPI reporting** and alert generation.  

---

## 🏁 Conclusion
This analysis highlights critical delay patterns in U.S. flight operations.  
By leveraging data, airlines can **anticipate delays**, **optimize scheduling**, and enhance **passenger satisfaction**.

---

## 👨‍💻 Author
**D. [Your Full Name]**  
Data Analyst | Python | Visualization | SQL  
📧 [Your Email]  
🌐 [LinkedIn / Portfolio Link]

