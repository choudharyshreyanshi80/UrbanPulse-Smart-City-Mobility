# UrbanPulse: Smart City Mobility Intelligence Platform

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**UrbanPulse** is a Data Engineering and Analytics project designed to explore urban mobility patterns in Delhi, India.

The project integrates road network information, traffic probe observations, historical weather, road accident statistics, and public transport schedule data using Databricks, PySpark, Delta Lake, and Medallion Architecture.

---

## Project Overview

UrbanPulse processes data through three layers:

1. **Bronze Layer:** Stores raw source data.
2. **Silver Layer:** Cleans, standardizes, and transforms datasets.
3. **Gold Layer:** Produces analytics-ready summary tables.

## Problem Statement

Urban mobility involves interconnected factors such as road infrastructure, traffic activity, weather conditions, road safety, and public transportation. UrbanPulse brings these datasets together into a structured analytical platform.

## Project Objectives

- Build an end-to-end data engineering workflow.
- Ingest multiple urban mobility datasets.
- Implement Medallion Architecture.
- Transform data using PySpark and Spark SQL.
- Store analytical data using Delta Lake.
- Build interactive Databricks AI/BI dashboards.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python, SQL |
| Big Data | Apache Spark, PySpark |
| Platform | Databricks |
| Storage | Unity Catalog Volumes |
| Data Format | Delta Lake |
| Visualization | Databricks AI/BI Dashboards |
| Version Control | Git, GitHub |

## Data Sources

| Source | Purpose |
|---|---|
| OpenStreetMap | Delhi road network |
| Traffic Probe Dataset | Traffic activity observations |
| Open-Meteo | Historical weather |
| Delhi Accident Statistics | Historical road accidents |
| GTFS | Public transport schedules |

**Dataset notes:**
Probe observations indicate traffic activity; they are not actual vehicle counts.

GTFS represents scheduled transport information, not live service performance.

Weather data provides environmental context for exploratory analysis.
- Probe observations indicate traffic activity; they are not actual vehicle counts.
- GTFS represents scheduled transport information, not live service performance.
- Weather data provides environmental context for exploratory analysis.
