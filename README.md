# 🌍 AIR Pulse — Global AQI Analytics

<p align="center">
  <img src="https://img.shields.io/badge/Project-Environmental%20Analytics-green"/>
  <img src="https://img.shields.io/badge/Domain-Public%20Health-blue"/>
  <img src="https://img.shields.io/badge/Tools-Python%20%7C%20Tableau-orange"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen"/>
</p>

---

## 🚀 Executive Summary
Air pollution is one of the most critical global challenges.

- 🌍 **Average AQI:** 132.1 (Unhealthy)  
- 🌫 **PM2.5 Levels:** 71.72 µg/m³ (>14× WHO limit)  
- 📊 **Dataset:** 34,885 city-year records  

👉 This project identifies **key drivers of air pollution** and provides **data-driven policy recommendations**.

---

## 🎯 Problem Statement
> Despite increasing environmental spending, air quality continues to deteriorate.

**Goal:**  
Identify **which factors drive AQI** and **what interventions improve it most effectively.**

---

## 📊 Dataset Overview

| Attribute | Value |
|----------|------|
| Records | 34,885 |
| Time Period | 2000–2023 |
| Variables | 17 |
| Granularity | City-level |

---

## 📂 Key Variables

| Variable | Description |
|--------|------------|
| AQI | Air Quality Index |
| PM2.5 | Fine particulate matter |
| CO₂ Emissions | Carbon output |
| Vehicle Growth | % increase in vehicles |
| Green Space | Vegetation coverage |
| Deforestation | Forest loss rate |
| Population Density | People/km² |
| Environmental Budget | Govt spending |
| Life Expectancy | Health outcome |

---

## ⚙️ Data Pipeline
Raw Data → Cleaning → Feature Engineering → Analysis → Tableau Dashboard

---

## 🔧 Data Engineering

### Cleaning

| Step | Description |
|------|------------|
| 🧹 Duplicate Removal | Removed repeated records |
| 📉 Missing Values | Median imputation |
| 📊 Outliers | IQR method |
| 🔄 Standardization | Unified formats |

### Feature Engineering

| Feature | Formula |
|--------|--------|
| Net Forestation | Afforestation − Deforestation |
| Urban Stress Index | Density + pollution |
| Sustainability Score | Green + Life Expectancy − Pollution |

---

## 📈 KPI Framework

| Category | KPIs |
|--------|------|
| 🌫 Air Quality | AQI, PM2.5, PM10 |
| 🚗 Drivers | CO₂, Vehicles, Deforestation |
| 💰 Policy | Environmental Budget |
| ❤️ Outcomes | Life Expectancy |

---

## 🔍 Key Insights

| Insight | Finding |
|--------|--------|
| 🚗 Vehicles | r = 0.79 (major driver) |
| 🏭 CO₂ | r = 0.90 (strongest driver) |
| 🌿 Green Space | r = -0.87 (best mitigator) |
| 💰 Budget | r = -0.49 (reduces AQI) |

---

## 🧠 Advanced Analysis

### Correlation Table

| Factor | Correlation |
|--------|------------|
| CO₂ Emissions | 0.898 |
| Vehicle Growth | 0.790 |
| Industry Growth | 0.745 |
| Deforestation | 0.631 |
| Population Density | 0.578 |
| Green Space | -0.866 |
| Environmental Budget | -0.487 |

---

## 🌍 City Segmentation

| Category | Description |
|----------|------------|
| 🔴 High Risk | High AQI + Low budget + Low green |
| 🟡 Mid Range | Moderate AQI |
| 🟢 Model Cities | Low AQI + High sustainability |

---

## 🏆 Top Sustainability Rankings

| Country | AQI | Budget | Green % | Life Exp | Score |
|--------|-----|--------|---------|---------|------|
| Sweden | 37.8 | 399.2 | 42.3 | 83.9 | 100.1 |
| Netherlands | 37.3 | 407.1 | 42.5 | 83.9 | 99.7 |
| Australia | 37.7 | 390.6 | 42.5 | 83.9 | 98.7 |

---

## 📊 Tableau Dashboard

### 🔹 Dashboard Structure

| Page | Focus |
|------|------|
| 🟢 Executive | AQI overview & trends |
| 🟡 Root Cause | Drivers analysis |
| 🔵 Solutions | Policy impact |

### 📸 Dashboard Preview
### 🟢 Executive Overview
<p align="center">
  <img src="images/dashboard1.png" width="90%" />
</p>

---

### 🟡 Root Cause Analysis
<p align="center">
  <img src="images/dashboard2.png" width="90%" />
</p>

---

### 🔵 Solutions & Policy Effectiveness
<p align="center">
  <img src="images/dashboard3.png" width="90%" />
</p>
---

## 💡 Recommendations

| Action | Impact |
|--------|--------|
| 🌿 Expand Green Space | AQI ↓ 15–30 |
| 🚗 Reduce Vehicles | Stabilize AQI |
| 💰 KPI Budgeting | Better efficiency |
| 🌳 Stop Deforestation | Long-term AQI ↓ |
| 🎯 Focus 50 Cities | High impact |

---

## 📉 Impact Estimation

| Domain | Impact |
|------|--------|
| AQI | ↓ 15–30 points |
| Life Expectancy | +1–3 years |
| PM2.5 | ↓ 20–35% |

---

## ⚠️ Limitations
- Correlation ≠ causation  
- Missing governance data  
- City-level aggregation  

---

## 🚀 Future Scope
- Real-time AQI dashboards  
- ML forecasting  
- Satellite monitoring  
- Policy simulation  

---

## 👥 Contribution Matrix

| Member | ETL | EDA | Stats | Dashboard | Report |
|-------|-----|-----|------|----------|--------|
| Shreya | ✓ | ✓ | ✓ | ✓ | ✓ |
| Ashutosh | ✓ | ✓ | ✓ |  | ✓ |
| Mausam |  | ✓ | ✓ | ✓ |  |
| Satyam | ✓ | ✓ | ✓ |  |  |
| Himanshu | ✓ |  | ✓ | ✓ |  |
| **Shagun Vishnoi** | ✓ | ✓ |  | ✓ |  |

---

## 📅 Submission

| Field | Value |
|------|------|
| Institute | Newton School of Technology |
| Date | April 29, 2026 |

---

## ⭐ Conclusion
Air pollution is **not inevitable** — it is driven by controllable factors.

✔ Cities investing in:
- Green infrastructure  
- Sustainable transport  
- Smart budgeting  

👉 Achieve **lower AQI and better health outcomes**

---

