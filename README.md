# Mapping the Protection Desert: Infrastructure Neglect Across NYC

[![Live Map](https://img.shields.io/badge/Live%20Map-Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://neglectindex.netlify.app/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![GeoPandas](https://img.shields.io/badge/GeoPandas-Spatial%20Analysis-green?style=for-the-badge)](https://geopandas.org/)

An empirical investigation into spatial equity and climate resilience across New York City's critical infrastructure networks, using the **Hunts Point Food Distribution Center** in the South Bronx as a core case study.

🔗 **Explore the interactive project map:** [neglectindex.netlify.app](https://neglectindex.netlify.app/)

---

## Executive Summary

The Hunts Point peninsula (Census Tracts 89.0 and 50.01) distributes **60% of NYC’s produce** and **50% of its meat**, yet remains unshielded within a 100-year floodplain. 

By analyzing **10,438 NYC infrastructure projects**, this research reveals a stark divide in spatial adaptation: municipal strategies heavily prioritize capital-rich real estate while leaving vital logistical and supply-chain networks exposed. This project provides the spatial processing pipeline, computational geometry, and spatial index models used to quantify this protection gap.

---

## Key Findings

* **Logistical Vulnerability:** Despite its central role in feeding the region, Hunts Point lacks the coastal defense capital allocated to adjacent commercial and high-rent residential zones.
* **Project Disparity:** Statistical evaluation of 10k+ municipal infrastructure entries demonstrates a capital-driven protection hierarchy across NYC's shorelines.
* **Policy Recommendation:** Recommends transitioning from real-estate valuation metrics to a utility-based infrastructure protection framework before storm surges test vulnerable flood zones.

---

## Tech Stack & Data Pipeline

* 📓 **Notebook Pipeline:** View the complete [Analysis Pipeline Notebook](./FloodVul.ipynb)
* **Data Processing & Analysis:** `Python`, `pandas`, `GeoPandas`, `Shapely`
* **Spatial Geometry Operations:** Buffer analysis, spatial joins, centroid intersections, and custom vulnerability indexing
* **Environment:** Google Colab
* **Web Visualization:** Interactive web map deployed on Netlify

---

---

## Data Sources

* **[NYC Participatory Budgeting Project Tracker](https://data.cityofnewyork.us/City-Government/Participatory-Budgeting-Project-Tracker/qm5f-frjb/about_data):** City of New York, Mayor's Office of Operations (NYC Open Data)
* **[NYC Flood Vulnerability Index](https://data.cityofnewyork.us/Environment/New-York-City-s-Flood-Vulnerability-Index/mrjc-v9pm/about_data):** City of New York, Mayor's Office of Climate and Environmental Justice (NYC Open Data)
* **[Social Vulnerability Index (SVI)](https://svi.cdc.gov/dataDownloads/data-download.html):** Centers for Disease Control and Prevention (CDC)
* **NYC Special Initiative for Rebuilding and Resiliency (SIRR):** City of New York (2013)
