# GEOG5415M Final Project: Spatial Analysis of Nitrogen Dioxide ($NO_2$) Inequality in Leeds

**Student ID:** 201971405  
**Module:** GEOG5415M Programming for Spatial Data Science  
**Date:** January 2026

---

## 📖 Project Overview

This repository contains the source code and data for the final assessment of the GEOG5415M module. The project investigates the spatial disparity of air quality in Leeds, UK.

Using a reproducible Python workflow, the study analyses Nitrogen Dioxide ($NO_2$) concentrations from 2018 across three distinct urban environments:
1.  **City Centre** (Corn Exchange)
2.  **Transport Corridor** (Kirkstall Road)
3.  **Suburban Park** (Temple Newsam)

The analysis highlights the "Centre-Periphery" pollution gradient and evaluates compliance with UK legal air quality limits ($40 \mu g/m^3$).

## 📂 Repository Structure
### 1. Main Analysis
* **`GEOG5415M_project.ipynb`**: The main Jupyter Notebook containing the full Python code, spatial analysis, and discussion.

### 2. Case Study Data (Used in Notebook)
* **`CornExchange.csv`**: Time-series air quality data for the City Centre site.
* **`KirkstallRoad.csv`**: Time-series air quality data for the Transport Corridor site.
* **`TempleNewsam.csv`**: Time-series air quality data for the Suburban Park site.

### 3. Additional Data Resources
* **`Leeds.geojson`**: Geospatial boundary data for the Leeds administrative district.
* **`air_quality_no2.csv`**: A broader dataset containing site metadata for monitoring stations across the region.
* **`imd_2019_england.csv`**: Index of Multiple Deprivation (IMD) 2019 data, included for potential socio-economic context analysis.
*(Note: The Leeds boundary map is fetched programmatically from the module's external repository within the notebook).*
