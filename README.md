# 🚗 British Road Accident Analysis Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Live_Dashboard-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiNWEwYjA0MmItOWYxZS00ZjU4LWExNDctMWY1NWY4Y2ZhMjkxIiwidCI6ImI4YTM2ODUyLTYxMjktNDM4NS04NmMwLWIxZDUzOTNiYmE5NSJ9&pageName=ReportSection)
[![Data Analysis](https://img.shields.io/badge/Domain-Road_Safety_%26_Analytics-blue?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](#)

---

## 📌 Interactive Live Dashboard

🔗 **[View Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWEwYjA0MmItOWYxZS00ZjU4LWExNDctMWY1NWY4Y2ZhMjkxIiwidCI6ImI4YTM2ODUyLTYxMjktNDM4NS04NmMwLWIxZDUzOTNiYmE5NSJ9&pageName=ReportSection)**

---

## 📖 Executive Summary

The **British Road Accident Analysis Dashboard** provides an executive-level overview of road safety statistics across Great Britain. Built using Power BI, Power Query, and DAX, this interactive report analyzes historical accident records to uncover key trends, high-risk conditions, spatial distribution, and severity breakdowns.

The goal of this dashboard is to assist traffic authorities, urban planners, and safety analysts in identifying high-density risk areas, peak casualty periods, and key contributing environmental factors to support data-driven policy decisions.

---

## 📊 Key Metrics & Highlights

* **Total Accidents Analyzed:** **307,973**
* **Total Casualties Recorded:** **417,883**
* **Total Vehicles Involved:** **563,302**
* **Timeframe:** **2021 – 2022**

### Casualty Breakdown by Severity
* 🟢 **Slight:** 263,280 casualties (~85.5%)
* 🟡 **Serious:** 40,740 casualties (~13.2%)
* 🔴 **Fatal:** 3,953 casualties (~1.3%)

---

## Key Business Questions Addressed

1. **Casualty Metrics:** What is the trend of total casualties across years, months, and days of the week?
2. **Vehicle Involvement:** Which vehicle types (Cars, Vans, Buses, Bikes) are involved in the highest proportion of casualties?
3. **Environmental Impact:** How do road surface conditions, light conditions, and weather factors correlate with casualty frequency?
4. **Demographic & Location Segmentation:** What is the ratio of urban vs. rural casualties, and how do severity levels differ by road type and speed limit?

---

## 🛠️ Data Architecture & Modeling

### Data Sources
* **`MAINDATA.xlsx`**: Core accident dataset containing spatial details (Latitude/Longitude), environmental factors, vehicle types, road conditions, and casualty counts.
* **`CALENDER.xlsx`**: Custom calendar table supporting year-over-year (YoY) and month-over-month (MoM) DAX calculations.

### Data Cleaning & Transformation (Power Query)
* **Custom Groupings:** Created custom grouping fields for `Vehicle_Type`, `Light_Conditions`, and `Junction_Control` to streamline reporting categories.
* **Data Sanitization:** Handled missing values in carriageway hazards and validated latitude/longitude geospatial values.
* **Date Parsing:** Standardized accident dates and built relationships between `MAINDATA[Accident Date]` and `CALENDER[Date]`.

---

## 🎯 Dashboard Features & Visualizations

1. **KPI Scorecards:** Instant access to total casualties, total accidents, total vehicles, and primary severity breakdowns.
2. **Casualty Trend Analysis:** Line charts comparing casualty counts across months and years.
3. **Vehicle & Location Breakdown:** Bar charts categorizing casualties by vehicle group (Car, Bus, Bike, Van, Other) and road classification (Urban vs. Rural).
4. **Environmental Conditions Analysis:** Heatmaps and matrix grids illustrating road surface conditions (Dry, Wet, Snow/Ice) and lighting conditions (Daylight, Dark with/without streetlights).
5. **Interactive Slicers:** Filter by year, region/police force, severity level, urban/rural zones, and road types.

---

## 🚀 How to Run Locally

### Prerequisites
* [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Latest Version recommended)

### Steps
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/BRITISH-ROAD-ACCIDENT-ANALYSIS.git](https://github.com/YOUR_USERNAME/BRITISH-ROAD-ACCIDENT-ANALYSIS.git)
