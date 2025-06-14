# 🏡 Japanese Housing Trends (2005–2024) | Migration & Prices

This project analyzes 20 years of housing transactions and migration trends across Japan's 47 prefectures. Using Python and visual analytics, it explores how population shifts and urbanization have shaped the real estate market—especially in the post-2020 landscape.

---

## 📊 Project Overview

- **🎯 Objective**: Understand regional housing and migration dynamics across time.
- **📅 Scope**: Data from 2005 to 2024.
- **🛠️ Tools Used**:  
  Python, Pandas, NumPy, Seaborn, Matplotlib, Jupyter Notebook

---

## 🗂️ Datasets

- **All_prefectures_buildings.csv**  
  Real estate transaction records: price, area, usage type, structure, year, and prefecture.

- **All_prefectures_migration.csv**  
  Annual inter-prefecture migration data: number of residents moving in/out.

---

## 🧹 Data Preparation

- Cleaned null values, outliers, and duplicates
- Converted dates to datetime format
- Standardized column names
- Merged datasets by prefecture and year for combined analysis

---

## 📌 Key Features

- 🗺️ **Migration Heatmap**  
  Yearly migration trends across all prefectures

- 📈 **Correlation Heatmap**  
  Feature-to-feature relationship insights (e.g., area vs. price)

- 🔍 **Area vs. Price Scatter Analysis**  
  Distribution of property size vs. transaction value

- ✅ **Cleaned Dataset for Reuse**  
  Ideal for future forecasting or modeling

---

## 🖼️ Sample Visualizations

*(Add these if you upload chart images to your repo)*

![Migration Heatmap](images/migration_heatmap.png)
![Scatter Plot](images/area_vs_value.png)
![Correlation Heatmap](images/correlation_heatmap.png)

---

## 🧠 Key Insights

- **Tokyo** leads in both transaction volume and migration inflows, showing continued urban attraction.
- Post-2020 data reveals intensified **urban migration**, likely tied to remote work and lifestyle shifts.
- Several **rural prefectures** (e.g., Akita, Shimane) face declining population through negative migration balances.
- Area and transaction value show a weak but notable correlation, with region-specific variations.

---

## 🔮 Future Directions

- Time-series modeling of migration and transaction trends
- Integration with socioeconomic indicators: employment, income, and aging demographics
- Scenario simulations: how would remote work or tax incentives affect migration?



