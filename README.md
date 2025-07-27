# 🚖 Uber Fares Data Analysis Project (Power BI)

A data analytics project using the Uber Fares Dataset from Kaggle. This project includes data cleaning, feature engineering, statistical exploration using Python, and visualization through an interactive Power BI dashboard.

---

## 📑 Table of Contents

1. [📘 Introduction](#-introduction)  
2. [🛠️ Methodology](#️-methodology)  
3. [📊 Analysis](#-analysis)  
4. [🔍 Results](#-results)  
5. [🧾 Conclusion](#-conclusion)  
6. [💡 Recommendations](#-recommendations)  
7. [📈 Power BI Dashboard](#-power-bi-dashboard)  
8. [📂 Files & Repository Structure](#-files--repository-structure)  
9. [🧑‍💻 How to Run the Project](#-how-to-run-the-project)  
10. [🧠 Author & Contact](#-author--contact)

---

## 📘 Introduction

This project analyzes the Uber Fares Dataset to identify fare trends, ride volumes, and time-based patterns. The objective is to provide a comprehensive dashboard for operational and business insights using Power BI.

---

## 🛠️ Methodology

- **Dataset Source**: [Uber Fares Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- **Technologies Used**:
  - Python (Pandas, Seaborn, Matplotlib)
  - Power BI Desktop
- **Steps**:
  1. Load and clean the dataset
  2. Feature engineering (hour, weekday, peak time, etc.)
  3. Exploratory data analysis (EDA)
  4. Build Power BI visuals and dashboards

---

## 📊 Analysis

Key descriptive statistics:
- **Mean Fare**: \$11.36  
- **Median Fare**: \$8.50  
- **Mode**: \$6.50  
- **Outliers**: 17,166 detected using IQR

Features engineered:
- Time features: `hour`, `day`, `month`, `weekday`
- Categorical flags: `peak_period`
- Label-encoded variables for Power BI

---

## 🔍 Results

- **Peak Times**: 7–9 AM & 4–7 PM
- **Busiest Days**: Weekdays (especially Fridays)
- **Fare Pattern**: Higher fares during rush hours
- **Seasonality**: Increased activity during summer months

---

## 🧾 Conclusion

The analysis uncovered valuable temporal and geographical trends. Peak periods are consistent with commuter hours, and weekday activity is significantly higher. Outliers likely include rare long-distance rides or data issues.

---

## 💡 Recommendations

- 🚗 Boost driver presence during known peak hours
- 💰 Use dynamic pricing during high-demand times
- 🧹 Filter and validate fare inputs to reduce data noise
- 🗺 Improve driver coverage in high-fare zones

---

## 📈 Power BI Dashboard

The interactive Power BI dashboard includes:
- 📊 Histogram and boxplot for fare distribution
- ⏰ Ride volume by hour, weekday, and month
- 🌍 Geographic distribution of pickup locations
- 🎛️ Slicers for time filters and peak periods

📁 Download `.pbix` file → [PowerBI_Dashboard.pbix]([./PowerBI_Dashboard.pbix](https://raw.githubusercontent.com/emerick149/cyizere-siborurema-elie-power-BI-/refs/heads/main/power%20BI%20files/powerBI%20dashboard.pbix))

---

## 📂 Files & Repository Structure

