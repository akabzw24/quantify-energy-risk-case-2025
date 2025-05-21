# Quantify Energy Risk Case Competition 2025

This repository contains the deliverables for our team submission to the **Quantify 2025 Energy Risk & Insurance Case Competition**. We explored CAT event loss modeling, parametric trigger analysis, and strategic feasibility for Quant Co.'s expansion into renewable energy.

---

## Problem Statement

Quant Co. seeks to expand into renewable energy (solar & wind) but faces increasing CAT-related risks such as wildfires, hail and winterstorms. Our task was to assess these risks and design a parametric insurance strategy to support their expansion.

---

## Deliverables
- Machine Learning classification of high-loss CAT events (Logistic Regression, Random Forest, XGBoost)
- Power BI dashboard with interactive risk insights
- Strategic recommendations for expansion by region & hazard type
- Slide deck from Power BI and QR code demo

---

## Model Performance Summary

| Model              | AUC  | Precision | Recall |
|-------------------|------|-----------|--------|
| Logistic Regression | 0.56 | 0.40      | 0.33   |
| Random Forest       | 0.56 | 0.38      | 0.40   |
| **XGBoost**         | **0.60** | **0.45** | **0.33** |

- SMOTE oversampling is used to handle class imbalance.
- Top features: max wind speed, rainfall, hail size, structures destroyed.

---

## Tools & Technologies

- Python: pandas, scikit-learn, imblearn, matplotlib)
- Machine Learning: XGBoost, Random Forest, Logistic Regression
- Power BI: Interactive visual dashboard with filters and KPIs
- Git & GitHub: Version control and collaboration

---

## Contact

Feel free to connect or follow more of my work:
- [Bozhao Wang's github Profile](https://github.com/akabzw24)


