# 📊 Air Quality in the Baltic States (PM2.5 Analysis, 2018--2024)

### A Data Analysis & Visualization Project using Python, OpenAQ API, and Geospatial Heatmaps

This project investigates **fine particulate matter (PM2.5)** levels
across the **Baltic countries** --- Estonia, Latvia, and Lithuania ---
using **real-world air quality measurements** from the OpenAQ API
(2018--2024).

The analysis includes:

-   Automated data retrieval (OpenAQ API v3)\
-   Data cleaning, merging & outlier handling\
-   Trend analysis and country comparison\
-   WHO guideline exceedance analysis\
-   Seasonal analysis\
-   SARIMA forecasting\
-   **LIVE interactive PM2.5 heatmap** for the Baltic region\
-   Project structured for real-world, reproducible data science
    workflows

------------------------------------------------------------------------

# 🌍 LIVE 24-Hour Baltic PM2.5 Heatmap

👉 **Open the interactive air pollution map:**\
\### 🔗
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

Data is collected from the **OpenAQ v3 API**, a global open air-quality
platform.

------------------------------------------------------------------------

# 🧹 Data Cleaning & Processing

-   Converted timestamps\
-   Normalized columns\
-   Removed duplicates\
-   Removed invalid PM2.5 values\
-   Created aggregates\
-   Removed outliers

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

# 🛠 Running Locally

    git clone https://github.com/r-krishnakumar94/air-quality-project.git
    pip install -r requirements.txt
    jupyter notebook

Add your OpenAQ API key inside the notebooks:

    API_KEY = "b654dc40b92bdd512956b2478836f207278e54d27dca9cdf1f20ab728bd7bd16"

------------------------------------------------------------------------

# 🚀 Key Findings

-   Winter pollution is higher\
-   Lithuania highest PM2.5\
-   Many days meet WHO standard\
-   Seasonal pattern consistent\
-   Heatmap shows local hotspots

------------------------------------------------------------------------

# ⚠️ Limitations

-   Sparse sensor coverage\
-   No street-level detail\
-   Forecasts illustrative only

------------------------------------------------------------------------

# 🙌 Author

**R. Krishnakumar**\
GitHub: https://github.com/r-krishnakumar94
