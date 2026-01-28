# Telangana Aadhaar Intelligence Dashboard

> **Data-Driven Insights for Citizen-Centric Digital Services**

A professional Power BI analytics project built for a UIDAI-focused hackathon. This dashboard analyzes **anonymised Aadhaar enrolment and update data for Telangana**, transforming raw datasets into actionable governance intelligence.

---

## 📌 Project Objective

The objective of this project is to:

* Analyze anonymised Aadhaar enrolment and update datasets
* Identify **patterns, trends, service stress zones, and digital inclusion indicators**
* Propose **data-driven decision frameworks** to improve citizen-centric digital services

This aligns directly with UIDAI’s vision of **efficient, inclusive, and scalable digital identity systems**.

---

## 🧩 Problem Statement

Participants are provided anonymised Aadhaar datasets related to enrolment and updates. The challenge is to:

* Perform **Exploratory Data Analysis (EDA)**
* Derive meaningful KPIs
* Design **predictive and descriptive analytics frameworks**
* Present insights in a way that supports **real-world policy and operational decisions**

This project focuses exclusively on **Telangana state** to enable district- and pincode-level insights.

---

## 🗂 Dataset Overview

* **Source**: UIDAI (Anonymised)
* **File Name**: `UIDAI Clean Data.xlsx`
* **Granularity**: Daily
* **Geography**: Telangana (State → District → Pincode)

### Key Attributes

* Date, Day, Month, Year
* State, District, Pincode
* Age 5 to 17 (Youth Aadhaar)
* Age Above 17 (Adult Aadhaar)

---

## 📊 Key Performance Indicators (KPIs)

The following KPIs are implemented and validated using the final dashboard visuals (from last image to first image):

1. **Total Aadhaar Transactions (826K)**
   Represents the overall Aadhaar enrolment and update volume processed across Telangana.

2. **District Aadhaar Load (826K)**
   Measures cumulative Aadhaar activity at district level, identifying high-demand districts.

3. **Daily Aadhaar Demand (826K)**
   Indicates daily operational load on UIDAI services.

4. **Youth Aadhaar Count (122K)**
   Number of Aadhaar transactions related to citizens aged 5–17, representing future digital inclusion.

5. **Adult Aadhaar Count (704K)**
   Aadhaar transactions from citizens above 17 years, showing working-age dependency.

6. **Youth Percentage vs Adult Percentage**
   Visualized using a donut chart to compare demographic dependency on Aadhaar services.

7. **Digital Inclusion Score (0.17)**
   Ratio of Youth Aadhaar to Adult Aadhaar, highlighting district-level digital readiness.

8. **Service Stress Index (1.00)**
   Indicates service pressure on UIDAI infrastructure for Telangana.

9. **District-wise Aadhaar Load Trend**
   Time-series analysis showing Aadhaar demand variation by day.

10. **Pincode Load & Hotspot Analysis**
    Geo-spatial KPI identifying Aadhaar service hotspots using pincode-level mapping.

---

## 📈 Dashboard Structure

### Page 1 – Telangana Aadhaar Health

* Card: Total Aadhaar Transactions
* Donut Charts: Youth % and Adult %
* Line Chart: Monthly Aadhaar Trend

### Page 2 – District Intelligence

* Bar Chart: District Aadhaar Load
* Heatmap (Matrix): Service Stress Index
* Column Chart: Digital Inclusion Score

### Page 3 – Operational Planning

* Line Chart: Daily Aadhaar Demand
* Map: Pincode Load (Service Hotspots)
* Table: Aadhaar Dependency Profile by District

---

## 🛠 Tools & Technologies

* **Power BI Desktop**
* **DAX** (Measures & Calculations)
* **Power Query** (Data Cleaning & Transformation)
* **Excel** (Source Dataset)
* **Data Visualization & Storytelling**

---

## 🧠 Key Insights & Impact

* Identifies **high-stress UIDAI districts** requiring infrastructure scaling
* Highlights **digital inclusion gaps** across Telangana
* Supports **data-driven planning** for enrolment centers and staffing
* Demonstrates how Aadhaar data can drive **policy-grade decisions**

---

## 🏆 Hackathon Value Proposition

> “This dashboard converts raw Aadhaar logs into a three-layer decision system covering **Citizen Health, Service Stress, and Future Digital Readiness** — enabling UIDAI to plan services scientifically.”

Designed to be **jury-friendly, policy-ready, and citizen-centric**.

---

## 🚀 Future Enhancements

* Predictive forecasting of Aadhaar demand
* District-wise anomaly detection
* Integration with population census data
* Real-time dashboard using live UIDAI feeds

---

## 🖼 Dashboard Screenshots

Below are key dashboard views showcasing the **Aadhaar Service Intelligence System (ASIS)**. Screenshots are ordered **from last dashboard page to first**, following the final storytelling flow used in evaluation.

### 1️⃣ Executive KPI Overview – ASIS Control Panel

![ASIS KPI Overview](images/asis_kpi_overview.png)

> Displays core KPIs including **District Aadhaar Load, Youth Aadhaar, Digital Inclusion Score, Daily Aadhaar Demand**, and demographic split (Adult % vs Youth %).

---

### 2️⃣ Geo-Spatial & District Intelligence View

![ASIS Geo District View](images/asis_geo_district.png)

> Highlights **Pincode Load hotspots**, district-wise Aadhaar load comparison, and digital inclusion scores for operational planning.

---

### 3️⃣ Aadhaar Demand & Dependency Analysis

![ASIS Demand Dependency](images/asis_demand_dependency.png)

> Focuses on **Daily Aadhaar Demand**, Aadhaar Dependency Index, and district contribution tables to assess citizen reliance on UIDAI services.

---

### 4️⃣ Raw Data Model Snapshot (UIDAI DATA)

![UIDAI Data Model](images/uidai_data_model.png)

> Represents the cleaned and structured UIDAI dataset used for analysis, including **Date, District, Pincode, Age 5–17, and Age Above 17** attributes.

---

## 👤 Author

**Nikhil Vemula**
Final-Year Engineering Student (AI & ML)
Data Analytics & Power BI Enthusiast

---

## 📜 License

This project is created for academic and hackathon purposes using anonymised public data.

---

⭐ *If you find this project insightful, consider starring the repository!*
