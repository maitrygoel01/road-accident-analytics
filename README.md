# 🚗 Road Accident Analysis Dashboard

## 📌 Project Overview

Road Accident Analysis Dashboard is an end-to-end Power BI solution designed to analyze road accident trends, casualty patterns, vehicle involvement, and environmental factors affecting road safety. The dashboard provides a centralized view of accident-related KPIs, enabling stakeholders, transportation authorities, and policymakers to identify high-risk areas, understand accident causes, and develop data-driven road safety strategies.

The project analyzes accident and casualty data across different vehicle types, road categories, locations, weather conditions, road surfaces, and lighting conditions to uncover key trends and improve traffic safety outcomes.

---

# 🎯 Business Problem

Road accidents result in significant human, social, and economic costs. Transportation authorities often face challenges in:

* Monitoring accident trends across regions
* Identifying accident-prone locations
* Understanding casualty severity patterns
* Evaluating the impact of weather and road conditions
* Assessing vehicle involvement in accidents
* Improving road safety planning and interventions
* Reducing fatalities and serious injuries

This dashboard transforms accident data into actionable insights that support evidence-based road safety decision-making.

---

# 📊 Road Safety Performance KPIs

| KPI                   | Value  |
| --------------------- | ------ |
| CY Casualties         | 195.7K |
| CY Accidents          | 144.4K |
| CY Fatal Casualties   | 2.9K   |
| CY Serious Casualties | 27.0K  |
| CY Slight Casualties  | 165.8K |

### Year-over-Year Performance

| Metric             | Change |
| ------------------ | ------ |
| Casualties         | -11.9% |
| Accidents          | -11.7% |
| Fatal Casualties   | -33.3% |
| Serious Casualties | -16.2% |
| Slight Casualties  | -10.6% |

---

# 🔷 1. Executive Road Safety Overview

The Executive Dashboard provides a consolidated view of road accident and casualty performance.

### Key Insights

### Accident Overview

* Total Accidents: 144.4K
* Total Casualties: 195.7K
* Fatal Casualties: 2.9K
* Serious Casualties: 27.0K
* Slight Casualties: 165.8K

### Trend Analysis

* Year-over-Year Accident Comparison
* Monthly Casualty Trends
* Severity Distribution Analysis

### Environmental Analysis

* Road Surface Conditions
* Weather Conditions
* Urban vs Rural Analysis
* Day vs Night Accident Analysis

---

# 🔷 2. Casualty Severity Analysis

The Casualty Dashboard focuses on understanding accident severity and casualty distribution.

### Business Questions Answered

* What proportion of casualties are fatal, serious, or slight?
* How have casualty levels changed compared to the previous year?
* Which factors contribute most to severe accidents?
* How do casualty patterns vary throughout the year?

### Analysis Performed

### Casualty Classification

The dashboard categorizes casualties into:

* Fatal Casualties
* Serious Casualties
* Slight Casualties

### Monthly Casualty Trends

Compares Current Year (CY) and Previous Year (PY) casualty trends to identify seasonal fluctuations and safety improvements.

### Business Value

* Supports road safety planning.
* Identifies areas requiring intervention.
* Measures effectiveness of safety initiatives.

---

# 🔷 3. Vehicle Type Analysis

The Vehicle Dashboard examines casualty distribution across vehicle categories.

### Key Metrics

| Vehicle Type         | Casualties |
| -------------------- | ---------- |
| Car                  | 155,804    |
| Van                  | 15,905     |
| Bike                 | 15,610     |
| Bus                  | 6,573      |
| Other                | 1,446      |
| Agricultural Vehicle | 399        |

### Analysis Performed

### Casualties by Vehicle Type

Measures the contribution of each vehicle category to overall casualties.

### Vehicle Risk Assessment

Identifies vehicle types associated with higher casualty counts.

### Business Value

* Supports vehicle-specific safety campaigns.
* Helps prioritize road safety initiatives.
* Identifies high-risk transportation segments.

---

# 🔷 4. Location & Geographic Analysis

The Location Dashboard identifies accident hotspots and high-risk areas.

### Business Questions Answered

* Which locations experience the highest casualty counts?
* Which regions require additional safety measures?
* How are casualties distributed geographically?

### Analysis Performed

### Top Locations by Casualties

Highest casualty locations include:

* Birmingham
* Leeds
* Bradford
* Manchester
* Liverpool

### Geographic Risk Assessment

Ranks locations based on casualty volumes and accident frequency.

### Business Value

* Prioritizes infrastructure improvements.
* Supports targeted enforcement strategies.
* Identifies accident-prone regions.

---

# 🔷 5. Road Infrastructure Analysis

The Road Type Dashboard evaluates casualty distribution across different road categories.

### Analysis Performed

### Casualties by Road Type

Road categories analyzed include:

* Single Carriageway
* Dual Carriageway
* Roundabout
* One-Way Street
* Slip Road

### Key Findings

* Single carriageways account for the highest proportion of casualties.
* Dual carriageways contribute significantly fewer casualties.
* Roundabouts and one-way streets show comparatively lower accident severity.

### Business Value

* Supports infrastructure investment decisions.
* Identifies high-risk road categories.
* Improves road design planning.

---

# 🔷 6. Urban vs Rural Analysis

The dashboard compares accident occurrence between urban and rural environments.

### Analysis Performed

### Casualties by Area Type

* Urban: 61.95%
* Rural: 38.05%

### Key Insight

Urban areas account for the majority of casualties due to:

* Higher traffic density
* Increased vehicle volume
* Greater pedestrian activity

### Business Value

* Supports city-level safety planning.
* Helps optimize traffic management strategies.
* Improves urban mobility initiatives.

---

# 🔷 7. Environmental Conditions Analysis

The Environmental Dashboard examines external factors influencing accident outcomes.

### Analysis Performed

### Casualties by Light Conditions

* Day: 73.84%
* Night: 26.16%

### Road Surface Analysis

Filters allow analysis based on:

* Dry Roads
* Wet Roads
* Snow/Ice Conditions
* Other Surface Conditions

### Weather Condition Analysis

Evaluates casualty patterns across:

* Fine Weather
* Rain
* Fog
* Snow
* Other Weather Conditions

### Business Value

* Supports weather-based safety campaigns.
* Improves emergency response planning.
* Enhances accident prevention strategies.

---

# 📈 Key Business Insights

## Casualty Insights

* Total casualties decreased by 11.9% compared to the previous year.
* Fatal casualties declined significantly by 33.3%.
* Slight casualties represent the largest share of overall casualties.

## Vehicle Insights

* Cars account for the majority of casualties.
* Motorcycles and vans contribute substantial casualty volumes.
* Agricultural vehicles represent the smallest casualty segment.

## Geographic Insights

* Birmingham records the highest number of casualties.
* Major urban centers experience higher accident concentrations.
* Accident hotspots can be prioritized for safety improvements.

## Infrastructure Insights

* Single carriageways are associated with the highest casualty counts.
* Road design plays a critical role in accident severity.

## Environmental Insights

* Most casualties occur during daylight hours.
* Urban roads account for nearly two-thirds of all casualties.
* Weather and road surface conditions significantly impact accident outcomes.

---

# 🛠️ Technical Implementation

## Data Modeling

A star schema model was implemented to support efficient reporting and analysis.

### Fact Table

* Fact Road Accidents

### Dimension Tables

* Dim Date
* Dim Vehicle Type
* Dim Location
* Dim Road Type
* Dim Weather Condition
* Dim Road Surface
* Dim Light Condition

---

## Power Query Transformations

The ETL process included:

* Data Cleaning
* Missing Value Handling
* Data Type Conversion
* Casualty Classification
* Relationship Creation
* Data Validation
* Derived Column Generation

---

## DAX Measures

* Total Casualties
* Total Accidents
* Fatal Casualties
* Serious Casualties
* Slight Casualties
* Casualty Growth %
* Accident Growth %
* Urban Casualty %
* Rural Casualty %
* Casualties by Vehicle Type
* Casualties by Road Type

---

# 🎨 Dashboard Features

## Interactive Navigation

* Executive Overview
* Casualty Analysis
* Vehicle Analysis
* Environmental Analysis

## Dynamic Filters

* Road Surface
* Weather Condition
* Location
* Vehicle Type
* Year

## User Experience

* Interactive KPI Cards
* Dynamic Slicers
* Cross Filtering
* Drill-Down Analysis
* Responsive Layout

---

# 🧰 Tools & Technologies

| Tool             | Purpose                |
| ---------------- | ---------------------- |
| Power BI Desktop | Dashboard Development  |
| Power Query      | Data Transformation    |
| DAX              | KPI & Measure Creation |
| Excel / CSV      | Data Source            |
| Data Modeling    | Star Schema Design     |

---

# 📷 Dashboard Screenshots

## Executive Dashboard

<img width="838" height="507" alt="image" src="https://github.com/user-attachments/assets/bb71a5b4-7da9-43d6-b461-7192638a4c02" />

---

# 📂 Project Structure

```text
Road-Accident-Analysis-Dashboard/
│
├── Dataset/
│   └── road_accident_data.csv
│
├── Dashboard/
│   └── Road_Accident_Analysis.pbix
│
├── Images/
│   └── road-accident-dashboard.png
│
└── README.md
```

---

# 📌 Conclusion

The Road Accident Analysis Dashboard provides a comprehensive road safety intelligence platform that enables transportation authorities and policymakers to monitor accident trends, analyze casualty severity, identify accident hotspots, evaluate environmental impacts, and implement targeted safety initiatives through data-driven decision-making.

---

# ⭐ Project Summary

An interactive Power BI dashboard that analyzes road accidents, casualties, vehicle involvement, environmental conditions, and geographic risk factors to improve road safety, reduce accident severity, and support evidence-based transportation planning.
