# 🧪 Nutrition Training Dashboard – Cycle-based Performance Insights

This interactive dashboard was developed to analyze and visualize data from community-based nutrition training programs. It provides stakeholders with actionable insights based on training cycles, regions, and gender distribution.

A Looker Studio dashboard for visualizing and analyzing training sessions across districts and training cycles.

![Dashboard Preview](dashboard-preview.png)

🔗 **Live Dashboard Preview:** [View the Dashboard](https://lookerstudio.google.com/reporting/6c91d0cf-7bf0-4d0e-9d5a-e056d3b02924)

---

## 📊 Project Summary

**Tool:** Looker Studio  
**Data Source:** Google Sheets  
**Role:** Dashboard Developer / Data Analyst  
**Domain:** Health & Nutrition Training  
**Status:** Demo with limited data and functionality

---

## 🎯 Objective

To design a user-friendly, single-page dashboard that helps program managers and stakeholders:

- Track training activities across time
- Compare performance by training cycle (Cycle 1 vs Cycle 2)
- Identify gender gaps in participation
- Drill down into district and community-level metrics

---

## 🔍 Key Features

- **Cycle Filter (Slicer):**  
  Choose between Cycle 1 or Cycle 2 to update all visualizations dynamically.

- **Trainings Over Time (Time Series Chart):**  
  Visualizes the number of trainings conducted over time using `training_date`.

- **District-wise Training Summary:**  
  Bar chart showing distribution of trainings across districts.

- **Trainer Insights:**  
  Table and bar chart displaying:
  - Number of trainings led by each trainer
  - Regional distribution of trainers
  - Identifies top-performing trainers and areas needing support

- **Gender Distribution (Pie Chart):**  
  Analyzes gender participation in training sessions.

- **Community/Sub-district Tables:**  
  Tabular summaries for deeper drill-down into implementation areas.

- **Date Range Filter:**  
  Allows flexible filtering by specific training dates.

---

## ⚙️ Data Processing Notes

- Dates were imported from Google Sheets in `DD/MM/YYYY` format and parsed into `MM/DD/YYYY` using formulas to ensure compatibility with Looker Studio’s date functions.
- Due to data privacy restrictions, this dashboard uses a **demo dataset** with limited functionality and records. The structure and logic, however, reflect the kind of real-world analytics dashboards used in similar projects.

---

## 🙏 Acknowledgements

Special thanks to one of my former employers for granting permission to use this restricted dataset for demo purposes. More dashboards can be developed and tailored to match specific program needs.

---

## 👋 About Me

I’m **Abubakari Sherifdeen**, a software engineer and data analyst passionate about using data for impact.  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/abubakari-sherifdeen-b67a6864/) 



---

> 📬 For collaboration or custom dashboard requests, feel free to reach out!
