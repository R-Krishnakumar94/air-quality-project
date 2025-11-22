# 📊 Air Quality in the Baltic States (PM2.5 Analysis, 2018--2025)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)
![OpenAQ API](https://img.shields.io/badge/OpenAQ-API%20v3-orange.svg)

### A Data Analysis & Visualization Project using Python, OpenAQ API, and Geospatial Heatmaps

This project investigates **fine particulate matter (PM2.5)** levels
across **Estonia, Latvia, and Lithuania**, using real-world air quality
measurements from the OpenAQ API (2018--2025).

------------------------------------------------------------------------

# 🌫️ Why PM2.5?

PM2.5 refers to airborne particles with a diameter of **2.5 micrometers
or smaller**.

We track PM2.5 because:

-   It is **the most harmful** common air pollutant (deep lung
    penetration).
-   It is linked to **respiratory and cardiovascular disease**.
-   It shows **strong seasonal patterns** (winter heating, stagnant
    air).
-   It is the **most consistently monitored pollutant** in the Baltics
    via OpenAQ.

------------------------------------------------------------------------

# 🌍 LIVE 24-Hour Baltic PM2.5 Heatmap

👉 **Interactive heatmap:**
🔗
https://r-krishnakumar94.github.io/air-quality-project/baltics_pm25_heatmap_latest.html

------------------------------------------------------------------------

# 📂 Project Structure

    air-quality-project/
    │
    ├── data/
    │   ├── raw/
    │   └── processed/
    │
    ├── notebooks/
    │   ├── 01_data_download.ipynb
    │   ├── 02_pm25_cleaning_and_eda.ipynb
    │   └── 03_pm25_heatmap.ipynb
    │
    ├── screenshots/
    │
    ├── README.md
    └── requirements.txt

------------------------------------------------------------------------

# 📥 Data Source

Data is collected using the **OpenAQ v3 API**, pulling PM2.5 values from
sensors in EE, LV, and LT.

------------------------------------------------------------------------

# 🧹 Data Cleaning & Processing

-   Converted timestamps
-   Normalized columns
-   Removed duplicates
-   Removed invalid PM2.5 values
-   Created daily & monthly aggregates
-   Removed outliers (IQR method)

------------------------------------------------------------------------

# 📈 Exploratory Data Analysis

### Trend Charts

![Trend charts](screenshots/Trend%20charts.png)

### Seasonal Patterns

![Seasonal plot](screenshots/Seasonal%20plot.png)

### WHO Exceedances

![WHO exceedance chart](screenshots/WHO%20exceedance%20chart.png)

------------------------------------------------------------------------

# 🔮 Forecasting (SARIMA)

![SARIMA forecast](screenshots/SARIMA%20forecast.png)

------------------------------------------------------------------------

# 🗺️ Interactive Heatmap

![Heatmap screenshot](screenshots/Heatmap%20screenshot.png)

------------------------------------------------------------------------

# 🛠 How to Run Locally

``` bash
git clone https://github.com/r-krishnakumar94/air-quality-project.git
pip install -r requirements.txt
jupyter notebook
```

Add your API key:

``` python
API_KEY = "your-openaq-api-key"
```

------------------------------------------------------------------------

# 🚀 Key Findings

-   Winter pollution peaks are consistent
-   Lithuania shows the highest PM2.5 values overall
-   Most days fall within WHO guidelines
-   Strong seasonal trends
-   Heatmap reveals local pollution hotspots

------------------------------------------------------------------------

# ⚠️ Limitations

-   Sparse sensor coverage (especially in Latvia)
-   Not enough sensors for street-level detail
-   Forecasts are seasonal predictions, not exact future values

------------------------------------------------------------------------

# 🙌 Author

**R. Krishnakumar**
GitHub: https://github.com/r-krishnakumar94

