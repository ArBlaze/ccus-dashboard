# 🛢️ CCUS Projects Dashboard — Data Cleaning & Visualization

This repository contains a cleaned and restructured version of the **IEA CCUS Projects Database**, along with a **Tableau dashboard** that highlights key trends, insights, and developments in carbon capture, utilization, and storage (CCUS) projects worldwide.

## 🌍 Overview

The original dataset is sourced from the [International Energy Agency (IEA)](https://www.iea.org/data-and-statistics/data-product/ccus-projects-database), which tracks large-scale CCUS projects globally. This repository focuses on:

- Cleaning and standardizing the data for analysis
- Building an interactive dashboard in Tableau
- Highlighting insights such as regional trends, technology types, project status, and capacity growth over time

## 📁 Repository Structure

```plaintext
ccus-projects/
├── data/
│   ├── ccus_projects_raw.xlsx
│   └── ccus_projects_cleaned.xlsx
├── tableau/
│   └── ccus_dashboard.twbx
├── notebooks/
│   └── data_cleaning.ipynb
└── README.md
```

## ✨ Dashboard Highlights

The Tableau dashboard includes:
- 📍 **Map of CCUS projects** with filterable views by status, location, and capture type
- 📈 **Trend lines** showing historical and projected CO₂ capture capacity
- 🏗️ **Project pipeline breakdown** (Operational, In Development, Announced)
- 🧪 **Technology breakdowns** by capture, transport, and storage type

## 🧹 Data Cleaning Summary

- Removed or filled null/missing values where appropriate
- Standardized column headers and data formats
- Parsed key fields (e.g., dates, capacity in MtCO₂/year)
- Consolidated inconsistent naming conventions across technologies and regions

## 📊 Tools Used

- **Python (Pandas, Jupyter)** – Data wrangling and preprocessing
- **Tableau Public** – Dashboard creation and data visualization

## 📦 Dataset Source

- **Name**: CCUS Projects Database  
- **Publisher**: International Energy Agency (IEA)  
- **Download link**: [https://www.iea.org/data-and-statistics/data-product/ccus-projects-database](https://www.iea.org/data-and-statistics/data-product/ccus-projects-database)  
- **Last updated**: April 30, 2025  
- **License**: Refer to [IEA’s terms of use](https://www.iea.org/terms) for data licensing information.

## 🚧 To Do

- [ ] Create initial data visualizations
- [ ] Finalize layout of principal dashboard
- [ ] Add insights section to README or GitHub Pages site
- [ ] Conduct feature engineering to uncover interesting insights
- [ ] Create new data visualizations if needed, and create final dashboard

## 🙌 Acknowledgments

- Original dataset by the **International Energy Agency (IEA)**
- Inspired by public dashboards like [IEA’s online CCUS Explorer](https://www.iea.org/data-and-statistics/data-tools/ccus-projects-explorer)

---

> *This project is not affiliated with or endorsed by the IEA.*
