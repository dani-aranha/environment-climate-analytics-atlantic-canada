# Environment & Climate Analytics — Atlantic Canada

**NSCC Capstone Project | 2026**

An applied Business Intelligence and Data Analytics project exploring environmental and climate patterns across Atlantic Canada, with a primary focus on **precipitation and extreme weather events**.

The project transformed publicly available Canadian environmental data into structured analytical datasets and interactive Power BI visualizations, following an end-to-end data analytics workflow.

---

## Project Overview

Climate and environmental datasets can reveal long-term patterns in precipitation, temperature, and extreme weather events. The objective of this project was to prepare, analyze, model, and visualize these datasets to support a clearer understanding of climate variability across Atlantic Canada.

The project was developed as part of the **Business Intelligence & Analytics program at Nova Scotia Community College (NSCC)**.

### My Contribution

**Data Lead & SQL/ETL Analyst**

**Primary focus: Precipitation & Extreme Weather Events**

As part of the project team, my work focused primarily on the preparation and analysis of precipitation and extreme weather data.

My contribution included:

* Cleaning and preparing precipitation datasets for analytical use
* Working with station-level monthly climate data
* Performing exploratory data analysis using **Python and Pandas**
* Analyzing patterns and trends in extreme weather events
* Preparing structured datasets for integration into the Power BI model
* Supporting ETL and data modeling activities
* Developing and refining Power BI analysis related to precipitation and extreme weather events
* Contributing to project documentation and data definitions

This was a collaborative capstone project, with team members responsible for different analytical areas.

---

## Analytical Workflow

```text
Environmental & Climate Data
            ↓
Data Cleaning & Preparation
            ↓
Python / Pandas
            ↓
Exploratory Data Analysis
            ↓
Precipitation & Extreme Event Analysis
            ↓
ETL & Data Modeling
            ↓
Power BI / DAX
            ↓
Interactive Dashboard
```

---

## Dashboard

The final Power BI deliverable focuses on **precipitation patterns and extreme weather events**.

### Dashboard Preview

![Precipitation Overview](dashboard/screenshots/precipitation-overview.png)

![Precipitation Trends](dashboard/screenshots/precipitation-trends.png)

![Extreme Weather Events](dashboard/screenshots/extreme-weather-events.png)

**[View the complete dashboard PDF](dashboard/Precipitation_ExtremeEvents_v3.pdf)**

The final Power BI file is also included in the repository:

`power-bi/Precipitation_ExtremeEvents_v3.pbix`

---

## Data & Analysis

The project used cleaned and prepared datasets designed to support integration into a **Power BI star schema**.

### Core Datasets

| Dataset                              | Description                                                                       |
| ------------------------------------ | --------------------------------------------------------------------------------- |
| `fact_precipitation.csv`             | Cleaned precipitation fact data used for precipitation analysis                   |
| `Fact_Extreme_Events_All.csv`        | Event-level extreme weather data used to analyze event frequency and patterns     |
| `ExtremeEvents_Per_Year.csv`         | Annual aggregation of observed extreme events with fitted historical trend values |
| `monthly_temperature_by_station.csv` | Monthly mean temperature by weather station, providing climate context            |

The datasets support analysis across **time and geographic location**, using calendar and station dimensions within the Power BI model.

### Extreme Event Trend Analysis

`ExtremeEvents_Per_Year.csv` contains:

* Observed annual event counts
* Fitted trend values generated in Python

The fitted trend is **descriptive rather than predictive**. It represents historical patterns and was used to support visualization and interpretation of long-term behavior.

---

## Python Analysis

Python was used for data preparation and exploratory analysis.

The repository includes notebooks covering:

* **Extreme Event Analysis** — investigation of extreme weather event data and patterns
* **Pandas EDA — Extreme Events** — exploratory data analysis and dataset investigation
* **Monthly Temperature Analysis** — analysis of monthly climate data

These notebooks demonstrate practical experience applying **Python, Pandas, data preparation, exploratory analysis, and trend analysis** to environmental datasets.

---

## Data Modeling

The project incorporated a structured analytical data model to support consistent reporting and Power BI analysis.

![Climate & Environmental Star Schema](data-model/Conceptual_Climate_Star_Schema.png)

The model uses dimensions such as:

* `Dim_Calendar` — time alignment
* `Dim_Station` — geographic/station alignment

This structure supports:

* Time-series analysis
* Regional aggregation
* Cross-variable comparison
* Power BI analytical measures and visualizations

Additional data-model documentation is available in:

`data-model/Data Dictionary – Climate & Environmental Star Schema.pdf`

---

## Tools & Technologies

* **Power BI**
* **DAX**
* **Python**
* **Pandas**
* **SQL / ETL**
* **Data Modeling**
* **Exploratory Data Analysis**
* **GitHub**

### Data Sources

The project used publicly available Canadian environmental and climate datasets, including data from **Environment and Climate Change Canada (ECCC)** and other federal data sources.

---

## Project Structure

```text
environment-climate-analytics-atlantic-canada/
│
├── dashboard/
│   ├── Precipitation_ExtremeEvents_v3.pdf
│   └── screenshots/
│       ├── precipitation-overview.png
│       ├── precipitation-trends.png
│       └── extreme-weather-events.png
│
├── data/
│   ├── fact_precipitation.csv
│   ├── Fact_Extreme_Events_All.csv
│   ├── ExtremeEvents_Per_Year.csv
│   └── monthly_temperature_by_station.csv
│
├── data-model/
│   ├── Conceptual_Climate_Star_Schema.png
│   └── Data Dictionary – Climate & Environmental Star Schema.pdf
│
├── power-bi/
│   └── Precipitation_ExtremeEvents_v3.pbix
│
├── python/
│   ├── Extreme Event.ipynb
│   ├── Pandas EDA_Extreme_Events.ipynb
│   └── Monthly_Temperature.ipynb
│
└── README.md
```

---

## Key Takeaways

This project provided hands-on experience applying Business Intelligence and Data Analytics concepts to real-world environmental datasets.

It demonstrates my ability to:

* Prepare and structure data for analytical use
* Work with station-level and event-level datasets
* Use Python and Pandas for exploratory analysis
* Investigate trends and patterns in environmental data
* Contribute to ETL and data modeling workflows
* Develop analytical dashboards using Power BI
* Apply DAX-based analysis and reporting concepts
* Document data structures and analytical processes
* Collaborate effectively within a multidisciplinary capstone team

---

**Project completed as part of the Business Intelligence & Analytics program at Nova Scotia Community College (NSCC), 2026.**
