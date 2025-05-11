# 📊 ElectroMart Marketing Optimization – GCDA'25 Hackathon (IIT KGP)

## 🏆 Award: Second Runner-Up  
### 🏁 Organized by: **IIT Kharagpur**  
### 📈 Problem Statement by: **AnalytixLabs**

---

## 🚀 Project Overview

This repository presents a comprehensive solution for **optimizing marketing investments and strategy** for **ElectroMart**, a consumer electronics retail firm in Ontario, Canada. Developed as part of the **General Championship Data Analytics 2025 Hackathon** at IIT Kharagpur, our solution integrates advanced statistical modeling, impact analysis, and optimization frameworks to address core business objectives.

---

## 📌 Problem Statement

ElectroMart had major marketing expenditures last year. The CFO wants to understand:

- What drove revenue (Performance Driver Analysis)?
- How much did each marketing lever contribute (Marketing ROI)?
- How to allocate next year’s budget optimally?
- Which product categories should be targeted?
- Which marketing channels work best and why?

---

## 🎯 Business Objectives Solved

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
