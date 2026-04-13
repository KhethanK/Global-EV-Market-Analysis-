# Global-EV-Market-Analysis-
# ⚡ Global EV Analytics Dashboard (IEA Data-Driven Insights)

## 📌 Executive Summary

This project delivers a **data-driven analytics dashboard** built on the **IEA Global EV Data 2024 dataset**, providing a comprehensive view of global electric vehicle adoption, infrastructure growth, and powertrain evolution.

The solution enables stakeholders to **analyze historical trends, compare regional performance, and evaluate future EV scenarios (APS & STEPS)** using interactive visualizations.

---

## 🎯 Business Objectives

* Assess **global EV adoption trends (2010–2040)**
* Benchmark **regional EV performance and growth trajectories**
* Analyze **powertrain transition (BEV, PHEV, FCEV)**
* Evaluate **charging infrastructure expansion**
* Support **policy, investment, and market strategy decisions**

---

## 📊 Dashboard Capabilities

### 🔹 Global EV Sales & Forecasting

* Historical EV growth trends
* Scenario-based projections:

  * **APS (Announced Pledges Scenario)**
  * **STEPS (Stated Policies Scenario)**
* Market expansion visualization up to 2040

### 🔹 Regional Benchmarking

* Region-wise EV adoption (China, Europe, USA, etc.)
* Comparative performance across:

  * Sales
  * Stock
  * Growth rate

### 🔹 Powertrain Intelligence

* Distribution of:

  * **BEV (Battery Electric Vehicles)**
  * **PHEV (Plug-in Hybrid EVs)**
  * **FCEV (Fuel Cell EVs)**
* Transition trends toward full electrification

### 🔹 Infrastructure & Energy Analysis

* Public charging infrastructure:

  * Fast vs slow chargers
* Energy consumption (GWh)
* Oil displacement impact

### 🔹 Time-Series & Comparative Insights

* EV growth trajectory of top regions
* Peak adoption years
* EV stock vs sales evolution

---

## 📂 Dataset Information

* **Source:** International Energy Agency (IEA)
* **Dataset:** *Global EV Data 2024*
* **Nature:** Official, policy-grade dataset used in global EV research

### 📌 Coverage

* Time Period: **2010 – 2040**
* Geography: **Global, regional, and country-level**
* Data Types:

  * Historical observations
  * Scenario-based projections (APS & STEPS)

---

## 🧾 Data Schema (Column-Level Explanation)

| Column Name    | Description                                                |
| -------------- | ---------------------------------------------------------- |
| **Region**     | Country or geographic region (e.g., China, Europe, USA)    |
| **Year**       | Time dimension for analysis (2010–2040)                    |
| **Parameter**  | Metric type (EV Sales, EV Stock, Charging Points, etc.)    |
| **Mode**       | Vehicle category (Cars, Buses, Vans, Trucks)               |
| **Powertrain** | EV technology type (BEV, PHEV, FCEV)                       |
| **Unit**       | Measurement unit (Vehicles, %, GWh, Million Barrels, etc.) |
| **Value**      | Numerical value of the metric                              |
| **Scenario**   | Projection scenario (APS / STEPS / Historical)             |

---

## 📊 Key Analytical Insights

* 🚀 **China leads global EV adoption**, contributing the highest EV stock and sales
* 🔋 **BEVs dominate (~75% market share)**, indicating rapid transition to full electrification
* 🌍 **Europe shows consistent, policy-driven growth**
* ⚡ **Charging infrastructure is expanding**, but uneven across regions
* 📈 EV market projected to reach **multi-billion scale (~5.4B+) by 2040**

---

## 🛠️ Tech Stack

* **BI Tool:** Power BI
* **Data Processing:** Power Query
* **Data Source:** IEA Global EV Data 2024
* **Techniques Used:**

  * Time series analysis
  * Scenario-based forecasting
  * Comparative analytics
  * Interactive dashboard design

---

## 📁 Project Structure

```
EV-Analytics-Dashboard/
│
├── data/
│   └── IEA_Global_EV_Data_2024.csv
│
├── dashboard/
│   └── EV_Dashboard.pbix
│
├── images/
│   ├── global_ev_sales.png
│   ├── powertrain_analysis.png
│   ├── parameter_analysis.png
│   └── time_series_analysis.png
│
├── docs/
│   └── ER_Diagram.png
│
├── README.md
└── requirements.txt (optional)
```

---

## 🚀 How to Run

1. Download the repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Load dataset if prompted (`data/IEA_Global_EV_Data_2024.csv`)
4. Use slicers:

   * Region
   * Year
   * Mode / Powertrain
5. Interact with visuals for insights

---

## 🔮 Future Enhancements

* Integrate **real-time EV datasets / APIs**
* Add **machine learning forecasting models (XGBoost, ARIMA)**
* Deploy dashboard using **Streamlit / Power BI Service**
* Add **geospatial EV adoption maps**
* Incorporate **carbon emission reduction analytics**

---

## 💼 Resume-Ready Highlights

* Built a **Power BI dashboard using IEA Global EV dataset** covering 30+ regions
* Performed **multi-dimensional EV analysis** across sales, stock, and infrastructure
* Implemented **scenario-based forecasting (APS & STEPS)** till 2040
* Identified **BEV dominance (~75%)** and regional adoption patterns
* Delivered **actionable insights for policy and investment decisions**

---

## 🏁 Conclusion

This project demonstrates strong capabilities in:

* Business Intelligence
* Data Analysis
* Data Visualization
* Strategic Insight Generation

It provides a **holistic, policy-grade view of the global EV ecosystem**, making it highly relevant for **data analyst, BI analyst, and AI/ML roles**.

---

## 📬 Contact

For queries or collaboration:

* LinkedIn: https://www.linkedin.com/in/khethan-kalluru-7723aa376/
* Email: khethankalluru05@gmail.com

---

## ⭐ If you found this useful

Give this repo a star ⭐ — it helps visibility!

