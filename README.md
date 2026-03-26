# Hong Kong Air Pollution & Temperature Analytics

A Python data analytics project that analyzes **temperature variation across 18 Hong Kong districts** and **air quality conditions across 18 AQHI monitoring stations** in 2024.

The project combines:
- weather data from the **Open-Meteo Archive API**
- monthly AQHI CSV files stored in the `aqi/` folder
- district and station reference data from `district.csv` and `station.csv`

The full workflow is implemented in a single **Jupyter Notebook**, covering data collection, preprocessing, analysis, visualization, and interactive mapping.

---

## Project Overview

This project explores spatial patterns in Hong Kong’s environmental conditions by comparing:

- **Monthly average daily maximum temperature** across 18 districts
- **Annual average daily maximum AQHI** across 18 monitoring stations

Using Python, the project automates data retrieval and cleaning, then presents the results through comparative charts and a Folium-based interactive map.

---

## Main Findings

- Inland districts such as **North, Yuen Long, and Tai Po** were generally warmer than coastal areas such as **Islands and Eastern**
- AQHI levels were relatively higher in dense urban areas such as **Mong Kok, Central, and Kwun Tong**
- The results suggest that both **geographical location** and **urban density** contribute to environmental differences across Hong Kong

---

## Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **Requests**
- **Matplotlib**
- **Folium**
- **CSV / JSON**

---

## Project Structure

```text
.
├── hong-kong-air-quality-temperature-analysis.ipynb
├── README.md
├── district.csv
├── station.csv
├── aqi/
│   ├── ...
│   └── monthly AQHI CSV files
└── images/
    ├── result1.png
    └── result2.png
