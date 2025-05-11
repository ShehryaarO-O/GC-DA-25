# General Championship - Data Analytics'25 - IIT Kharagpur

## 🏆 Award: Second Runner-Up  
### 🏁 Organized by: **Technology Students' Gymkhana IIT Kharagpur**  
### 📈 Problem Statement by: **AnalytixLabs**

---

## 🚀 Project Overview

This repository presents a comprehensive solution for **optimizing marketing investments and strategy** for **ElectroMart**, a consumer electronics retail firm in Ontario, Canada. Developed as part of the **General Championship Data Analytics 2025 Hackathon** at IIT Kharagpur, our solution integrates advanced statistical modeling, impact analysis, and optimization frameworks to address core business objectives.

---

## 📌 Deliverbales Required

- What drove revenue (Performance Driver Analysis)?
- How much did each marketing lever contribute (Marketing ROI)?
- How to allocate next year’s budget optimally?
- Which product categories should be targeted?
- Which marketing channels work best and why?

---

## 🎯 Our Solutions

- 📈 **Performance Driver Analysis**: Identifying KPIs that drive top-line revenue.
- 💸 **Marketing ROI Quantification**: Estimating the causal impact of different commercial levers using SHAP & CatBoost.
- 🧮 **Optimized Budget Allocation**: Solving a constrained optimization problem based on Mixed-Integer Second Order Cone Programming (MISOCP).
- 🎯 **Product Targeting Strategy**: Recommending product categories using data-driven rationale.
- 📣 **Channel Optimization**: Reallocating budget to high-performing channels based on response decomposition, saturation curves & XGBoost feature gains.

---

## 🗂️ Repository Structure

```bash
.
├── Exploratory_Data_Analysis.ipynb              # EDA, SHAP-based Impact Analysis
├── Risk_Analysis.ipynb                          # Herfindahl Index, Volatility, Risk Scores
├── Supply_Chain_KPIs.ipynb                      # Procurement SLA, CAC, CLTV metrics
├── Market_Mix_Modelling.R                       # Meta's Robyn MMM Implementation
├── Market_Mix_Optimization_Framework.ipynb      # Novel Optimization Model (MISOCP)
├── data.txt                                     # Contains links to raw and processed datasets
├── Report.pdf                                   # Detailed methodology, results & business strategy
'''
## 🧠 Approach & Methodology

### 1. 📊 EDA & Impact Analysis
- GMV trend, discount-revenue patterns, order fluctuations  
- Weather data integration via Meteostat API  
- SHAP + CatBoost for lag-based feature contribution analysis

### 2. ⚠️ Risk Modeling
- Channel dependency & volatility using Herfindahl-Hirschman Index  
- Risk-stratified budget bounding (Low to Very High Risk channels)

### 3. 📈 Marketing Mix Modelling
- Used Meta’s **Robyn** (SOTA MMM tool) in R  
- Daily spend interpolation, spline smoothing, ridge regression, saturation effects

### 4. 🧮 Optimization Framework
- Custom-built Mixed-Integer SOCP model using **Gurobi**  
- Multi-dimensional constraints (budget limits, risk factors, spend shifts)  
- Incorporated response coefficients from Robyn & internal benchmarks

### 5. 🔁 XGBoost Segment Analysis
- Per-product channel effectiveness evaluated using feature importance  
- Provided channel-level strategy recommendations

---

## 🧠 Key Insights

- 📉 High ROI channels (TV, Digital) were under-invested relative to their impact  
- 📊 Over-concentration on SEM & Sponsorship posed revenue risk  
- 📦 Supply chain inefficiencies (SLA delays) majorly impacted CLTV  
- 📈 Proposed reallocation improved projected GMV by **>20%** with **lower risk exposure**

---

## 🛠️ Tech Stack

- **Languages**: Python, R  
- **Libraries**: Pandas, Seaborn, SHAP, XGBoost, GurobiPy, Robyn  
- **Tools**: Jupyter, Google Colab, Git, GitHub  
- **APIs**: Meteostat (Weather Integration)

---

## 📎 Data Sources

- Consumer Orders (FSN ID, GMV, Delivery SLA, Units Sold)  
- SKU Metadata (Product Hierarchies)  
- Marketing Spend Logs (TV, Digital, OOH, Affiliates)  
- NPS & Calendar Metadata  
- Weather Reports (via Meteostat API)  

📄 *See* `data.txt` *for data download links.*

---

## 📘 Report

A detailed 60+ page report (`Report.pdf`) covering:

- All visualizations & pre-processing steps  
- Impact analysis (SHAP + lag features)  
- Risk modeling framework  
- Robyn MMM implementation details  
- Optimization problem formulation  
- Future strategy via an **Agentic AI System**

---

## 📄 License

This repository is part of a student academic hackathon submission and is available for educational, non-commercial use. For any other use, please contact the contributors.

---

## 👥 Contributors

- **[Your Name]** – Team Lead, Optimization & Modelling  
- **[Teammate 2]** – Risk Modeling & Data Engineering  
- **[Teammate 3]** – Robyn MMM Implementation  
- **[Teammate 4]** – Visualizations, EDA, Report Authoring

---

## 📈 Future Work

- Full agentic automation for campaign adjustment  
- Incorporate real-time marketing dashboards  
- Integration with CRM pipelines for ongoing spend adjustment

