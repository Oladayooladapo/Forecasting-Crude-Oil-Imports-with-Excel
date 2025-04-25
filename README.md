# Forecasting-Crude-Oil-Imports-with-Excel
A Comparative Analysis Using Time Series Forecasting Techniques

## Project Overview

This project focuses on building a reliable and accurate **forecasting model** for crude oil import volumes into the United States. Conducted for **Eagle Energy Enterprises**, a key player in the oil refining sector, the goal was to mitigate the impact of import volatility by predicting future volumes using multiple time series forecasting techniques in **Microsoft Excel**.

By applying and comparing traditional forecasting models, the project demonstrates my ability to carry out **end-to-end forecasting**, evaluate model performance, and support data-driven operational planning.

---

## Business Context

**Eagle Energy Enterprises** refines crude oil into essential fuels across the U.S. Given the fluctuating nature of oil imports, the company needs a robust forecasting system to:

-  Predict monthly import volumes
-  Align procurement and production schedules
-  Improve budget planning and profitability
-  Enhance decision-making in a volatile energy market

---

## Project Goals

- Apply various forecasting techniques in Excel
- Measure model performance using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Percentage Error (MAPE)**
- Identify the most accurate forecasting method
- Enable better planning through data-backed projections

---

## Dataset Description

| Column | Description |
|--------|-------------|
| `Date` | Monthly timestamps for oil import data |
| `Monthly Import Level` | Crude oil import volume (barrels) |

---

##  Forecasting Techniques Applied

| Model | Description |
|-------|-------------|
| **Naïve Forecast** | Assumes the next value equals the last observed value |
| **2-Month Moving Average** | Averages the last 2 months' data |
| **3-Month Moving Average** | Averages the last 3 months' data |
| **4-Month Moving Average** | Averages the last 4 months' data |
| **Exponential Smoothing (0.2)** | Smoothing factor: α = 0.2 |
| **Exponential Smoothing (0.3)** | Smoothing factor: α = 0.3 |
| **Exponential Smoothing (0.4)** | Smoothing factor: α = 0.4 |
| **Linear Regression** | Uses a line of best fit to forecast values |

---

## Model Evaluation Metrics

| Metric | Description |
|--------|-------------|
| **Mean Absolute Error (MAE)** | Measures average absolute error between actual and forecasted values |
| **Mean Squared Error (MSE)** | Penalizes larger errors more heavily to show overall forecast variance |
| **Mean Absolute Percentage Error (MAPE)** | Expresses forecast accuracy as a percentage |
| **Accuracy** | Complement of MAPE (100% - MAPE) |

---

## Results Summary

| Model | MAE | MSE | MAPE | Accuracy |
|-------|-----|-----|------|----------|
| Naïve | 13,342.13 | 327,009,534.40 | 5.84% | 94.16% |
| **2-Month MA** | **11,175.28** ✅ | **212,054,795.18** ✅ | **4.95%** ✅ | **95.05%** ✅ |
| 3-Month MA | 11,269.22 | 214,576,194.57 | 4.98% | 95.02% |
| 4-Month MA | 11,262.22 | 218,415,040.57 | 4.97% | 95.03% |
| ES (0.2–0.4) | 12,259.08 | 270,409,988.88 | 5.38% | 94.62% |
| Linear Regression | 14,457.79 | 289,353,722.48 | 6.36% | 93.64% |

 **Best performing model:** 2-Month Moving Average  
 **Least performing model:** Linear Regression (in this dataset context)

---

## Key Takeaways

- **Short-term moving average models outperformed more complex methods** in this dataset.
- **Excel** can serve as a powerful and flexible forecasting tool when equipped with the right logic.
- Model selection depends heavily on data behavior—there’s no one-size-fits-all solution.

---

## What's Included in This Repo

| File | Description |
|------|-------------|
| `forecasted_dataset.xlsx` | Forecast results for all 8 models (compressed file) |
| `README.md` | Project overview and methodology |
| `raw_data.xlsx` | Clean version of the original time series (compressed file) |

---

This project illustrates my ability to apply forecasting techniques, critically compare models, and deliver insights using just Excel—a crucial skill for business analysts and forecasters alike.

