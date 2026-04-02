# 🌊 National River Toxin Analysis

This repository contains an end-to-end **exploratory data analysis project examining heavy metal contamination and water quality** across five major global river systems, built to demonstrate skills in **data cleaning, statistical analysis, and Python-based data visualisation**.

The project explores toxin levels, seasonal pollution patterns, river acidity, and nutrient loads using the **National River Toxin Dataset**.

---
## 🔗 Live Dashboard

👉 [View the Visualisations and Analysis](https://github.com/jayso10/National-River-Toxins-Analysis-python-/blob/main/EDA%20River%20System.ipynb)

📈 [View the Full Report and Documentation](https://github.com/jayso10/National-River-Toxins-Analysis-python-/blob/main/Full%20Report%20and%20Insight.pdf)

---

## 📊 Project Overview

The goal of this project was to analyse river toxin data to uncover insights into:

- Heavy metal contamination across river systems
- Seasonal and yearly pollution trends
- Water acidity and alkalinity profiles
- Nutrient pollution levels
- Statistical differences between rivers

The analysis demonstrates the full workflow of a data analytics project:

**Raw Data → Data Profiling → Data Cleaning → Analysis → Visualisation → Statistical Testing**

---

## 📊 Project Summary

Dataset statistics:

- **Total Observations:** 1,305
- **River Systems:** 5 (Amazon, Nile, Yangtze, Mississippi, Danube)
- **Variables:** 10
- **Years Covered:** 2018 – 2022
- **Toxins Analysed:** Lead, Mercury, Arsenic

The dataset combines water quality readings, heavy metal concentrations, and environmental indicators to analyse pollution levels and river health across regions.

---

## ❓ Research Questions

This analysis aimed to answer several key questions:

- Which **rivers have the highest heavy metal contamination?**
- Are there **seasonal or yearly patterns** in toxin levels?
- Which rivers are the most **acidic or alkaline?**
- Which rivers carry the **highest nutrient loads?**
- Are there **outliers or abnormal contamination events** in the data?
- Are the **differences between rivers statistically significant?**

---

## 🧠 Approach

### 1️⃣ Data Profiling

Explored the raw dataset to understand its structure, column types, and summary statistics before any transformations were applied.

- Checked dataset shape (1,305 rows × 10 columns)
- Reviewed data types and column distributions
- Identified missing values across all columns

---

### 2️⃣ Data Cleaning

Addressed data quality issues to ensure reliable analysis.

- Detected and quantified missing values per column
- Filled missing numeric values using **column mean imputation**
- Converted the `Date` column from string to **datetime format**

---

### 3️⃣ Analysis & Visualisation

Conducted a multi-layered analysis covering toxin levels, pH, nutrients, trends, and statistical comparisons.

Key analyses include:

- **Average and total toxin levels** by river system
- **pH analysis** — identifying the most acidic and most alkaline rivers
- **Nutrient analysis** — Nitrates and Phosphates by river
- **Outlier detection** using the IQR method
- **Seasonal trend analysis** — monthly and yearly toxin averages
- **Correlation matrix and heatmap** across all numeric variables
- **T-tests** for all river pair combinations across all three toxins
- **Linear regression** — pH as a predictor of Lead levels

---

## 📈 Key Insights

- **The Yangtze is the most polluted river** across all three heavy metals — Lead, Mercury, and Arsenic.
- **The Amazon is the cleanest** in terms of heavy metal toxins, but is the only river with an acidic pH (6.99).
- **The Mississippi is the most alkaline river** (pH 7.80) and carries one of the highest nutrient loads.
- **Lead and Arsenic follow a seasonal pattern** — peaking January to May and dipping August to October — suggesting agricultural and rainfall-driven contamination cycles.
- **Only one outlier exists in the entire dataset** — a Lead spike of 5.80 in the Yangtze on 15 March 2021 — indicating pollution is chronic rather than event-driven.
- **Every river pair is statistically distinct** across all toxins — all 30 t-tests returned p < 0.001.
- **pH is positively correlated with Lead (r = 0.32)** — more alkaline rivers tend to carry higher Lead concentrations.

---

## 🗂️ Repository Structure
```
.
├── EDA_River_System.ipynb              # Main analysis notebook
├── National_River_Toxin_Dataset_1.csv  # Raw dataset
└── README.md                           # Project documentation
```

---

## 🛠️ Technologies Used

- **Python** – Data analysis and visualisation
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualisation
- **SciPy** – Statistical testing (t-tests)
- **Scikit-learn** – Linear regression

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
</p>

---

## 📅 How to Use

1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scipy scikit-learn`
3. Place `National_River_Toxin_Dataset_1.csv` in the same directory as the notebook
4. Open `EDA_River_System.ipynb` in Jupyter and run all cells top to bottom

---

## ✅ Key Takeaways

- Practiced **end-to-end exploratory data analysis** from raw data to findings
- Applied **statistical testing** (t-tests, correlation, regression) to validate observations
- Strengthened **Python data skills** across Pandas, Seaborn, SciPy and Scikit-learn
- Learned to use **outlier detection and seasonal decomposition** to uncover hidden patterns
- Focused on **storytelling through data** — structuring analysis around clear research questions

---

### License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>
