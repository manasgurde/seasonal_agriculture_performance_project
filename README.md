# 🌾 Seasonal Agriculture Performance Analysis
> **VOIS AICTE Batch 1 (2026–2027) — Major Project**  
> An end-to-end data analytics and statistical investigation into seasonal agricultural productivity, resource usage efficiency, and economic outcomes across Kharif, Rabi, and Zaid seasons in India.

---

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Libraries](https://img.shields.io/badge/Stack-Pandas%20%7C%20Seaborn%20%7C%20SciPy-brightgreen.svg)]()
[![License](https://img.shields.io/badge/License-MIT-purple.svg)]()

---

## 📌 Project Overview

Agricultural productivity is governed by complex seasonal interactions between environmental factors, resource availability, agronomic management, and market forces. Raw agricultural records often obscure these dynamic relationships.

This major project conducts a rigorous, evidence-based exploration of **4,001 farm records across 28 parameters** to uncover how seasonal variations influence:
- **Crop Yield & Production Volume** (Tonnes/Ha & total output)
- **Environmental Dynamics** (Rainfall, temperature, solar radiation, humidity, and soil chemistry)
- **Input Resource Utilization** (Irrigation water volume, NPK nutrients, pesticides, and efficiency metrics)
- **Economic Viability** (Production costs, market realization, net profit, and profit margins)
- **Pest & Disease Vulnerability**

---

## 🎯 Key Questions Investigated

1. How do crop yield, total production, and farmer profit margins fluctuate across **Kharif, Rabi, and Zaid** seasons?
2. What are the key environmental indicators characterizing each season, and how strongly do they correlate with yield?
3. How does water efficiency (Tonnes per 1,000 m³) differ across irrigation techniques (Drip, Sprinkler, Flood, Rainfed)?
4. Are observed seasonal differences statistically significant, or can they be explained by random chance?
5. Which crops deliver the highest return on investment (ROI) within each distinct cropping window?
6. What anomalous patterns or extreme loss-making operational conditions exist in seasonal farming?

---

## 📊 Dataset Profile

| Metric | Details |
|---|---|
| **Total Records** | 4,001 farm observations |
| **Feature Dimensions** | 28 attributes (Agronomic, Environmental, Economic, Resource) |
| **Temporal Coverage** | 3 Cropping Seasons: *Kharif*, *Rabi*, *Zaid* |
| **Crops Covered** | Wheat, Rice, Maize, Pulses, Cotton |
| **Geographic Scope** | Multiple Indian agricultural states (Andhra Pradesh, Maharashtra, Karnataka, Telangana, Gujarat, Tamil Nadu, etc.) |

---

## 🔬 Methodology & Notebook Workflow

The analysis is documented inside [`Seasonal_Agriculture_Performance_Analysis.ipynb`](./Seasonal_Agriculture_Performance_Analysis.ipynb) across 13 structured sections:

1. **Title & Project Introduction** — Background context, problem formulation, and key investigative themes.
2. **Library Setup & Data Ingestion** — Configuration of analytical libraries and aesthetic visualization templates.
3. **Exploratory Data Analysis (EDA)** — Data topology, distribution profiles, unique categoricals, and null value verification.
4. **Data Preprocessing & Feature Engineering** — Outlier audits (IQR method), data sanitization, and derivation of key indicators (`Profit_Margin_pct`, `Cost_per_Hectare`, `Water_Efficiency`, `Total_Nutrients_kg_ha`, `Is_Profitable`).
5. **Core Seasonal Performance Analysis** — Bivariate and multivariate comparisons across yield, economics, environment, and irrigation.
6. **Correlation & Relationship Analytics** — Global and season-stratified correlation matrices and environmental scatter plots.
7. **Geographic & Crop Stratification** — Cross-tabulated heatmaps of State × Season and Crop × Season performance.
8. **Hypothesis Testing & Statistical Inference** — ANOVA and Kruskal-Wallis tests, Bonferroni-corrected Mann-Whitney U pairwise post-hoc tests, and Chi-Square tests of independence.
9. **Anomaly & Outlier Detection** — Z-score screening (|z| > 3), extreme performer profiling, and disease risk clustering.
10. **Consolidated Key Findings** — Comprehensive data dashboard synthesizing key quantitative takeaways.
11. **Project Tasks & Questions Compliance Matrix** — Formal verification against all required project criteria from the VOIS AICTE guidelines.
12. **Actionable Recommendations** — 12 evidence-grounded strategic interventions for farmers and agricultural planners.
13. **Conclusion & Future Directions** — Summary, project boundaries, and machine learning roadmap.

---

## 📈 Key Findings Summary

- **Seasonal Performance Shifts**: Agricultural yields and profitability rates vary distinctly across seasons, driven by environmental thresholds and water availability.
- **Resource Efficiency**: Drip and sprinkler systems consistently deliver higher water efficiency (Tonnes/1,000 m³) compared to flood irrigation, especially during water-stressed Zaid seasons.
- **Statistical Significance**: Non-parametric Kruskal-Wallis and ANOVA tests confirm that seasonal variations in rainfall, temperature, water usage, and crop yields are statistically significant ($p < 0.001$).
- **Economic Risk**: Loss-making farms are predominantly linked to high pesticide/fertilizer input costs paired with suboptimal seasonal crop matching.

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.9+
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Statistical Computing**: `scipy` (stats, hypothesis testing)
- **Environment**: Jupyter Notebook / VS Code

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/seasonal-agriculture-performance-analysis.git
cd seasonal-agriculture-performance-analysis
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 3. Launch Notebook
```bash
jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
```

---

## 📜 Academic Affiliation

- **Program**: VOIS AICTE Batch 1 (2026–2027)
- **Domain**: Data Analytics & Machine Learning
- **Project Type**: Major Project