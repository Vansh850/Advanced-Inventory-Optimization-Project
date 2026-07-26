# 📦 Inventory Optimization & Demand Forecasting using ABC Analysis and Time Series Forecasting

A data-driven inventory optimization project that integrates **ABC Analysis**, **Time Series Forecasting**, and **Procurement Planning** to improve inventory management and demand forecasting. The project identifies high-value inventory items, forecasts future demand using statistical forecasting techniques, and recommends optimal procurement policies to minimize inventory costs while maintaining product availability.

---

## 📖 Project Overview

Efficient inventory management is critical for reducing holding costs and preventing stock shortages. This project aims to:

- Classify inventory items using ABC Analysis.
- Forecast demand for high-priority inventory items.
- Compare forecasting models using MAPE.
- Recommend an optimal procurement plan based on forecasted demand.

The methodology combines inventory control techniques with statistical forecasting to support data-driven procurement decisions.

---

## 🎯 Objectives

- Perform ABC Analysis on historical inventory data.
- Identify high-value (Class A) inventory items.
- Analyze demand patterns using historical sales data.
- Compare multiple forecasting models.
- Select the best forecasting model based on Mean Absolute Percentage Error (MAPE).
- Generate monthly demand forecasts.
- Develop an optimal procurement strategy.

---

## 🛠️ Methodology

### 1. ABC Analysis

Inventory items are classified based on Annual Usage Value.

- **Class A** – High-value items requiring strict inventory control.
- **Class B** – Moderate-value items.
- **Class C** – Low-value items requiring minimal monitoring.

The project classified:

- **Class A:** 8 Items
- **Class B:** 63 Items
- **Class C:** 24 Items

Only the Class A products were selected for detailed demand forecasting and procurement planning. :contentReference[oaicite:1]{index=1}

---

### 2. Demand Forecasting

Historical monthly sales data for the previous three years was analyzed to identify:

- Trend
- Seasonality
- Irregular variation

The project evaluated two forecasting techniques:

- Decomposition Method
- Holt-Winters Additive Exponential Smoothing

The forecasting model with the lowest MAPE was selected. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

---

### 3. Model Selection

Forecasting model comparison:

| Model | MAPE |
|--------|------|
| Decomposition Method | 11.929% |
| Holt-Winters Additive Exponential Smoothing | **5.509%** |

Since Holt-Winters produced the lowest forecasting error, it was selected for future demand prediction. :contentReference[oaicite:4]{index=4}

---

## 📊 Key Features

- Inventory Classification using ABC Analysis
- Annual Usage Value Calculation
- Time Series Data Analysis
- Trend and Seasonality Detection
- Demand Forecasting
- Forecast Model Comparison
- Procurement Planning
- Forecast Accuracy Evaluation using MAPE

---

## 🧰 Tools & Technologies

- Microsoft Excel
- Time Series Forecasting
- ABC Analysis
- Holt-Winters Exponential Smoothing
- Decomposition Method
- Moving Average
- MAPE (Mean Absolute Percentage Error)

---

## 📈 Results

The project successfully:

- Classified 95 inventory items into A, B, and C categories.
- Identified the most critical inventory items.
- Forecasted monthly demand for the upcoming year.
- Selected Holt-Winters Additive Exponential Smoothing as the best-performing forecasting model.
- Developed a procurement plan based on forecasted demand.
  
## SPSS Files

This repository contains the original SPSS syntax (.sps), data (.sav), and output (.spv) files used during the analysis.

GitHub cannot preview these binary file formats. Please download them and open them using IBM SPSS Statistics.
