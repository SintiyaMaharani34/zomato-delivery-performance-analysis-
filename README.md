# 🚚 Zomato Delivery Operation Performance Analysis

## 📌 Project Overview

Delivery time is one of the most critical KPIs in food delivery services. Longer delivery times negatively impact customer satisfaction and increase operational costs.

This project analyzes Zomato's delivery operations to identify the operational factors that influence delivery performance and provides data-driven recommendations to improve delivery efficiency.

The project covers the complete analytics workflow, including:

- Data Preparation
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Insights
- Interactive Power BI Dashboard
- Business Recommendations

---

# 🎯 Business Problem

Zomato aims to improve the efficiency of its food delivery operations by identifying the factors that contribute to longer delivery times.

The analysis addresses the following business questions:

### Business Problem 1

**Which factors have the greatest impact on delivery time?**

---

### Business Problem 2

**How does delivery performance vary across different operational conditions such as weather, traffic, delivery distance, vehicle type, and city?**

---

### Business Problem 3

**Which operational segments should be prioritized to improve delivery efficiency?**

---

# 🎯 Project Objectives

- Identify the operational factors affecting delivery time.
- Discover operational bottlenecks.
- Provide actionable business recommendations.
- Build an interactive dashboard for operational monitoring.

---

# 🗂 Dataset Information

| Item | Description |
|------|-------------|
| Dataset | Zomato Food Delivery Dataset |
| Records | 43,697 Delivery Orders |
| Features | 28 Variables |
| Target Variable | Delivery Time (minutes) |
| Industry | Food Delivery & Logistics |

---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

---

# 📋 Project Workflow

```
Raw Dataset
      │
      ▼
Data Preparation
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Insights
      │
      ▼
Interactive Power BI Dashboard
      │
      ▼
Business Recommendations
```

---

# 🧹 Data Preparation

The dataset was prepared through several preprocessing stages to ensure data quality before analysis.

### Data Validation

- Dataset structure validation
- Data type verification
- Duplicate checking

### Data Cleaning

- Removed missing order time records
- Standardized time formats
- Corrected inconsistent values
- Removed invalid observations

### Feature Engineering

Created new analytical features:

- Delivery Distance (km)
- Preparation Time
- Order Datetime
- Pickup Datetime
- Order Hour
- Day of Week
- Weekend Indicator
- Time of Day

---

# 📊 Exploratory Data Analysis

The exploratory analysis consists of three levels:

## 1. Univariate Analysis

- Distribution analysis
- Descriptive statistics
- Outlier detection

## 2. Bivariate Analysis

Relationship analysis between:

- Traffic Density vs Delivery Time
- Weather vs Delivery Time
- Vehicle Type vs Delivery Time
- Delivery Distance vs Delivery Time
- City vs Delivery Time

## 3. Multivariate Analysis

Interaction analysis among:

- Weather
- Traffic Density
- Vehicle Type
- Delivery Distance
- Delivery Time

---

# 📈 Key Findings

### Business Problem 1

- Traffic congestion is the strongest operational factor affecting delivery time.
- Delivery distance has a strong positive relationship with delivery time.
- Weather conditions moderately influence delivery performance.
- Vehicle type has relatively little impact compared with traffic and delivery distance.

---

### Business Problem 2

- Road traffic density is the most significant operational factor affecting delivery time.
- Long-distance deliveries become substantially slower under heavy traffic conditions.
- Weather conditions contribute to longer delivery times, but their impact is smaller than traffic congestion.
- Semi-urban areas record the longest average delivery times despite representing only a small proportion of total orders.
- Vehicle type has a relatively limited impact compared with traffic density and delivery distance.

---

### Business Problem 3

Operational improvement should prioritize:

1. Traffic Congestion
2. Long-Distance Deliveries
3. Weather Conditions
4. Festival Operations
5. Vehicle Type

---

# 📊 Interactive Dashboard

The Power BI dashboard provides an interactive overview of delivery performance.

Dashboard includes:

- KPI Cards
- Traffic Analysis
- Weather Analysis
- Distance Analysis
- Vehicle Analysis
- City Analysis
- Business Insights
- Operational Recommendations

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations are proposed:

- Implement traffic-aware route optimization.
- Prioritize efficient courier allocation for long-distance deliveries.
- Improve dispatch planning during peak traffic periods.
- Monitor high-risk operational segments through interactive dashboards.
- Develop proactive operational strategies for adverse weather conditions.

---

# 📁 Repository Structure

```
zomato-delivery-performance-analysis/

│
├── data/
│   ├── zomato_delivery_raw.csv
│   └── zomato_delivery_clean.csv
│
├── notebooks/
│   ├── 01_Data_Preparation.ipynb
│   └── 02_Exploratory_Data_Analysis.ipynb
│
├── dashboard/
│   ├── Zomato_Dashboard.pbix
│   └── Dashboard_Preview.png
│
├── presentation/
│   └── Zomato_Delivery_Performance_Case_Study.pdf
│
├── images/
│   ├── dashboard.png
│   ├── data_preparation.png
│   ├── univariate.png
│   ├── bivariate.png
│   ├── multivariate.png
│   └── business_problem.png
│
└── README.md
```

---

# 📷 Dashboard Preview

> <img width="521" height="325" alt="image" src="https://github.com/user-attachments/assets/d1cf35ec-156b-4594-80fb-e310eb9190ea" />


```

# 📌 Project Highlights

✔ End-to-End Data Analytics Project

✔ Data Cleaning & Feature Engineering

✔ Exploratory Data Analysis

✔ Business Insight Generation

✔ Interactive Power BI Dashboard

✔ Business Recommendations

---

# 👤 Author

**Sintiya Maharani**

Data Analyst | Business Intelligence | Former Tax Consultant
