# 📊 Guangzhou Air Quality Analysis (2015–2024)

> A data-driven analysis of air pollution trends in Guangzhou, revealing seasonal patterns, policy impacts, and public health implications through Power BI visualization.

## 🧠 Project Background

Air quality has become a growing public concern in rapidly urbanizing cities like Guangzhou.  
This project aims to answer:

- How has air quality changed over time?
- Are there clear seasonal or yearly patterns?
- Which pollutants contribute most to AQI deterioration?
## 📂 Data Source

- Dataset Source (URL):Kaggle – China Air Quality Historical Data.csv
- Dataset Name:Air Pollution China
- Key Variables:
  
  <img width="298" height="286" alt="image" src="https://github.com/user-attachments/assets/af2a71de-5382-4dc2-9dfe-cedda7b71c87" />

## 🎯 Business Objective

This project leverages Power BI to analyze historical air quality data in Guangzhou (2015–2024) in order to:

- Track long-term AQI (Air Quality Index) trends

- Identify key pollutants contributing to poor air quality

- Explore relationships between AQI and meteorological factors (temperature, humidity)

- Deliver data-driven insights to support policymakers, environmental agencies, and urban planners

## 🔧 Data Preparation & Methodology

### 1️⃣ Data Cleaning (Power Query)

- Filtered dataset to retain **Guangzhou-only** records
- Standardized data types across pollutants, weather, and time fields
- Removed empty rows, duplicates, and inconsistent values
- Created a conditional **AQI Category** column:
  - Good / Moderate / Unhealthy / Very Unhealthy / Hazardous
- Built key measures:
  - Average AQI
  - Unhealthy Days
  - Average PM2.5
  - AQI Standard Deviation
  - Total Precipitation

### 2️⃣ Data Modeling & Visualization (Power BI)

- Constructed a **Date Table** to enable time-series analysis
- Designed an interactive dashboard with:
  - KPI cards (Average AQI, Unhealthy Days, Average PM2.5)
  - AQI trend line (2015–2024)
  - Pollutant comparison bar chart (PM2.5, PM10, NO₂, SO₂)
  - Scatter plot: AQI vs Temperature  
    - Bubble size = Humidity  
    - Color = AQI Category
  - Year × Month seasonal AQI heatmap
  - AQI category distribution pie chart
  - Slicers for Year, Month, and Season

  ## 🔍 Key Insights

### 🌫️ Insight 1: Strong Seasonal Patterns — Q1 Is the Peak Pollution Period

- AQI consistently peaks in **January–March (Q1)** across multiple years
- Driven by lower temperatures, weaker atmospheric dispersion, and increased regional emissions
- **June–August (Q3)** shows the cleanest air due to heavy rainfall and strong circulation

**Implication**: Pollution monitoring and targeted controls should be intensified during Q1.

### 🚗 Insight 2: PM2.5 and PM10 Are the Primary AQI Drivers

- PM2.5 and PM10 concentrations significantly exceed gaseous pollutants (NO₂, SO₂)
- Unhealthy and very unhealthy days align with particulate matter spikes
- High AQI variability suggests episodic severe pollution events

**Implication**: Reducing particulate matter should be the top policy priority.

---

### 🌡️ Insight 3: Meteorological Factors Shape AQI Dynamics

- Weak negative correlation between temperature and AQI
- High humidity increases AQI variability, potentially due to secondary aerosol formation

**Implication**: Meteorological variables should be integrated into AQI forecasting models.

### 📉 Insight 4: Overall Improvement, but Pollution Spikes Persist

- Most days fall under **Good** or **Moderate** AQI categories
- A meaningful share of days remains **Unhealthy** or worse

**Implication**: Targeted interventions are needed to address episodic pollution events.

## 📈 Dashboard Preview

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8d53a160-f313-49cb-9db4-dd0f22fcf81f" />


## 🛠️ Tools & Skills Demonstrated

- Data Cleaning & Transformation: Power Query

- Visualization & Dashboarding: Power BI

Analysis Techniques:

- Time-series analysis

- Seasonal trend analysis

- Correlation exploration

- Data Storytelling & Insight Communication

## ▶️ How to Use

- Download the CSV file 

- Open the air_bi.pbix file using Power BI Desktop

- Refresh the data source if required

- Use slicers to explore trends by year, month, or season

## 🎯 Why This Project Matters

This project demonstrates my ability to:

- Translate real-world environmental problems into analytical questions

- Clean, model, and analyze raw datasets

- Extract actionable insights from time-series and multivariate data

- Communicate findings through professional, interactive dashboards

## 🚀 Future Work

Future extensions of this project could incorporate predictive modeling to forecast AQI trends using historical pollution and meteorological data. The analysis may also be expanded to include multi-city comparisons across the Greater Bay Area, enabling cross-regional benchmarking of air quality performance. Additionally, integrating policy timelines and external socioeconomic indicators could help evaluate the effectiveness of environmental regulations and support more evidence-based urban sustainability planning.

