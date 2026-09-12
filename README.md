# Hi, I'm Karan Trivedi

Data Analyst | Healthcare · Pharma · Finance Analytics  
MS Data Analytics — Webster University (Dec 2024) | Piscataway, NJ  
Lean Six Sigma Black Belt | Python · SQL · R · Streamlit · Power BI

I build end-to-end analytics projects on real government and open datasets — from raw data pipelines through ML models and live interactive dashboards. All work is version-controlled with documented, reproducible code.

---

## Current Role

**Data Analyst — Phoenix Tech Solutions Inc.** (Dec 2025 – Present, Remote)  
Building a portfolio of sector-specific analytics solutions using public datasets to support new business proposals across healthcare, pharma, supply chain, and financial services.

---

## Featured Projects

| # | Project | What It Does | Scale | Stack | Live |
|---|---------|-------------|-------|-------|------|
| 1 | **CMS Fraud, Waste & Harm Command Center** | Joined 5 government datasets to surface where pharma payments, opioid prescribing and patient harm intersect. 3 theses proven. | 1.6M providers · 27GB | Python · SQL · Streamlit | [Dashboard](https://cms-command-center-wpbn3mbqgpkwae6syflrbp.streamlit.app) · [Repo](https://github.com/Karant15/CMS-Command-Center) |
| 2 | **Finance Fraud Detection** | XGBoost + SHAP fraud classifier on 590k real transactions. ROC-AUC 0.915. Live transaction risk scorer. | 590k transactions | XGBoost · SHAP · SMOTE · Streamlit | [Repo](https://github.com/Karant15/Finance-Fraud-Detection) |
| 3 | **Healthcare Workforce Analytics** | Mapped physician shortages across all 50 US states using 9.6M Medicare records. | 9.6M records · 1.1M providers | Python · Streamlit · CMS | [Dashboard](https://karan-healthcare-analytics.streamlit.app) |
| 4 | **Healthcare Readmission ML** | Predicts 30-day hospital readmission risk. XGBoost + SHAP. Live risk predictor with gauge chart. | 101k patient records | XGBoost · SHAP · SMOTE · Streamlit | [Dashboard](https://karan-healthcare-ml.streamlit.app) |
| 5 | **Supply Chain KPI + DMAIC + SQL** | 57% late delivery rate found in 180k orders. 15 SQL queries. Full Six Sigma DMAIC analysis. | 180k orders | Python · SQL · SQLite · Streamlit | [Dashboard](https://karan-supply-chain.streamlit.app) |
| 6 | **SQL Business Analytics** | 25 SQL queries — basic aggregations through advanced window functions. Live SQL explorer in browser. | 2 real datasets | SQL · SQLite · Python · Streamlit | [Dashboard](https://karan-sql-analytics.streamlit.app) |
| 7 | **Human Capital Analysis** | 97% turnover prediction accuracy. Decision Tree 0.97 AUC. 15,000+ employee records. | 15k employees | R · Logistic Regression · Decision Trees | [Repo](https://github.com/Karant15/Human-Capital-Analysis) |
| 8 | **Bank Loan Default Risk** | 80.65% sensitivity. $1.165M cost reduction through threshold optimisation. | 5,960 applicants | R · Logistic Regression | [Repo](https://github.com/Karant15/Bank-Loan-Decision-Making-Analysis) |
| 9 | **Consumer Segmentation** | K-Means + Random Forest segmentation for AXANTEUS market research agency. | 600 profiles | R · K-Means · Random Forest | [Repo](https://github.com/Karant15/Consumer-Segmentation-Analysis) |

---

## Project Highlights

### 🏥 CMS Fraud, Waste & Harm Command Center — LIVE
*Sep 2026 · Biggest project*

Joined 5 US government datasets (27GB total) — Open Payments, Medicare Part D, Medicare Part B, Hospital Compare, and the NPPES NPI Registry — using the NPI number as the primary key to build a master table of 1.6 million US providers.

**Three theses proven with real data:**
- Opioid outliers prescribe at **113.5x** the rate of low-scoring specialty peers
- Brand drug outliers prescribe brand-name drugs **165% above** specialty average
- Top **6.4%** of billing outliers account for **72.3%** of all Medicare services billed

**NJ Spotlight:** 1,920 NJ providers · 213 high-risk · 477 opioid outliers

**Dashboard:** 6 interactive tabs — national risk map, 3 thesis views, NJ spotlight, provider lookup with risk gauge chart

🔗 [Live Dashboard](https://cms-command-center-wpbn3mbqgpkwae6syflrbp.streamlit.app) · [GitHub Repo](https://github.com/Karant15/CMS-Command-Center)

`Python` `Pandas` `NumPy` `SciPy` `SQLite` `SQL` `Streamlit` `Plotly`

---

### 💳 Finance Fraud Detection Dashboard — LIVE
*Aug 2026*

End-to-end fraud detection pipeline on 590,540 real IEEE-CIS financial transactions.

- XGBoost classifier with SMOTE class balancing — **ROC-AUC 0.915**
- SHAP explainability layer for compliance team transparency
- SQL intelligence layer — 6 queries including running total window functions
- Live transaction risk scorer with fraud probability gauge

🔗 [GitHub Repo](https://github.com/Karant15/Finance-Fraud-Detection)

`XGBoost` `SHAP` `SMOTE` `SQLite` `Streamlit` `Plotly`

---

### 🏥 Healthcare Workforce Analytics — LIVE
*Jan 2026*

Analysed 9.6M real US Medicare records to surface physician staffing gaps.

- 1.1M unique providers across 104 medical specialties
- US choropleth map — state-level shortage classification
- Wyoming, Vermont, Alaska identified as most critically underserved
- DMAIC Six Sigma recruitment gap analysis

🔗 [Live Dashboard](https://karan-healthcare-analytics.streamlit.app)

---

### 🏥 Healthcare Readmission ML Pipeline — LIVE
*Mar 2026*

Predicts 30-day hospital readmission risk from 101,745 real patient records.

- 4 models trained and compared — XGBoost ROC-AUC 0.598
- SHAP explainability surfaces top clinical risk drivers
- SMOTE handles 11.2% class imbalance
- Live risk predictor with gauge chart and clinical recommendations

🔗 [Live Dashboard](https://karan-healthcare-ml.streamlit.app)

---

### 📦 Supply Chain KPI + DMAIC + SQL — LIVE
*Feb 2026*

180,519 real orders — 57% delivered late across 23 global regions.

- 15 SQL queries: aggregations, joins, subqueries, window functions
- ABC inventory analysis — Class A drives 80% of revenue
- Full DMAIC Six Sigma structured root cause analysis

🔗 [Live Dashboard](https://karan-supply-chain.streamlit.app)

---

### 🗄️ SQL Business Analytics — LIVE
*Apr 2026*

25 SQL queries across healthcare and supply chain real datasets.

- Window functions: RANK, DENSE_RANK, ROW_NUMBER, LAG, LEAD, running totals, moving averages
- CTEs for ABC classification and cross-domain joins
- Live SQL Explorer — write and run any query in the browser

🔗 [Live Dashboard](https://karan-sql-analytics.streamlit.app)

---

## Tech Stack

```
Languages      Python · R · SQL
Visualization  Plotly · Streamlit · Power BI · Tableau · Seaborn
ML             XGBoost · SHAP · SMOTE · Scikit-learn · Random Forest
               Logistic Regression · Decision Trees · K-Means Clustering
Database       SQLite · PostgreSQL · MySQL · SQL Server · DAX
               Relational Modelling · Dimensional Modelling
Process        Lean Six Sigma Black Belt · DMAIC · SIPOC · RCA · FMEA
Domain         Healthcare · Pharma · Finance · Supply Chain · HR Analytics
Tools          Git · GitHub · Jupyter · VS Code · Power BI Desktop
```

---

## Certifications & Education

- **MS Data Analytics** — Webster University (Dec 2024) · GPA 3.31
- **Lean Six Sigma Black Belt** — Benchmark Six Sigma (2021)
- **Lean Six Sigma Green Belt** — Benchmark Six Sigma (2021)
- **Google Data Analytics** — Coursera
- **Microsoft PL-300 Power BI** — Microsoft Learn

---

## Prior Experience

**Senior Accounts Manager — ID Medical LLP** (Nov 2016 – Jul 2021)  
Managed 30+ NHS hospital accounts across the UK · Forecasting accuracy +25% · 15% YoY revenue growth · Supported a CMS-focused healthcare sourcing initiative — directly relevant to the CMS analytics work above

**Senior Recruitment Consultant — QX KPO Services** (Aug 2014 – Oct 2016)  
453 shifts filled in one month · £25,000 revenue · Led a 4-member team

**International Peer Mentor / Writing Coach — Webster University** (Jan 2023 – Dec 2024)  
CRLA Level 2 Certified · 94% positive outcome rate

---

## Contact

📫 krntrivedi@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/karan-r-trivedi-b9a96a56)  
🔗 [CMS Command Center](https://cms-command-center-wpbn3mbqgpkwae6syflrbp.streamlit.app) · [Healthcare Analytics](https://karan-healthcare-analytics.streamlit.app) · [Fraud Detection](https://github.com/Karant15/Finance-Fraud-Detection) · [Supply Chain](https://karan-supply-chain.streamlit.app)
