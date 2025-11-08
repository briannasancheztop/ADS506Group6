**📘 Project README: Time Series Analysis of California EMS Hourly Load Data**

This README outlines the purpose, structure, and methodology of our time series analysis project using historical EMS hourly load data from California ISO.

---

## 🧠 Project Overview

This project explores and models hourly electricity load data across California's major utility regions using time series techniques. The goal is to understand temporal patterns, detect seasonality, and build accurate forecasting models that support operational insights and planning.

We focus on:
- **Data cleaning and preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Feature engineering for time-based insights**
- **Modeling and forecasting using ARIMA, ETS, and machine learning**
- **Team collaboration and reproducible reporting using Jupyter notebooks and GitHub**

---

## 📊 Data Source

- **Provider**: California Independent System Operator (CAISO)
- **Dataset**: Historical EMS Hourly Load
- **URL**: [CAISO Historical EMS Hourly Load](https://www.caiso.com/library/historical-ems-hourly-load)
- **Coverage**: Hourly load data across multiple balancing authorities including PGE, SCE, SDGE, VEA, and CAISO aggregate
- **Format**: Excel files (.xlsx) organized by month and year

---

## 🧹 Data Preprocessing

- Combined `Date` and `HR` fields to create precise hourly timestamps
- Removed invalid or missing date entries (e.g., "CAISO Public")
- Indexed the DataFrame by timestamp for time series operations
- Extracted temporal features: hour, day, weekday, month, season, etc.
- Validated chronological order and data integrity

---

## 🔍 Exploratory Analysis

- Visualized hourly and monthly load trends for SDGE and other regions
- Analyzed distribution and correlation across utilities
- Identified seasonal patterns and weekend effects
- Used STL decomposition and smoothing techniques

---

## 📈 Modeling Approach

- Applied ARIMA and ETS models for baseline forecasting
- Compared performance using RMSE and MAE
- Explored ensemble methods and machine learning extensions
- Prepared for Shiny app integration and storytelling in later modules

---

## 🧑‍🤝‍🧑 Team Collaboration

- Version control via GitHub (`ADS506Group6`)
- Jupyter notebooks for reproducible analysis
- Modular code structure for data, EDA, and modeling
- Final deliverables include a technical report and interactive presentation

---

## 📁 Project Structure

```
ADS506Group6/
│
├── Code/
│   ├── Data/                # Raw Excel files from CAISO
│   ├── EDA_Group6.ipynb     # Exploratory analysis notebook
│   └── Modeling/            # Forecasting models and evaluation
│
├── README.md                # Project overview
└── Final_Report/            # Team deliverables (Module 6 & 7)
```

---

## 📅 Timeline

- **Start Date**: November 7, 2025
- **Final Deliverables Due**: December 8, 2025
- Milestones include literature review, EDA draft, data story, and final report

---

Let me know if you'd like a Markdown version or want to include badges, licensing, or contributor credits.
