# 📈 Forecasting Sales Revenue Using LSTM Models

> A predictive model for Kontakt Home's 2020 revenue using historical sales data and LSTM neural networks.

---

## 📝 Project Overview

The aim of this thesis is to **forecast the 2020 revenue of Kontakt Home**, a major retailer in Azerbaijan, using **historical sales data from 2018 and 2019**.  

The **Long Short-Term Memory (LSTM)** neural network was employed due to its ability to capture temporal dependencies and nonlinear trends in time-series data.

The research simulates predictions assuming no external disruptions (e.g., COVID-19) and evaluates the **monthly revenue forecasts** across various stores and product categories.

---

## ⚙️ Methodology

- **Data:** Sales data from 2018–2019  
- **Model:** LSTM (Long Short-Term Memory)  
- **Evaluation Metrics:**  
  - Root Mean Squared Error (RMSE)  
  - Mean Absolute Error (MAE)  

> The LSTM model captures general sales patterns but struggles during periods of high volatility, particularly mid-2020.

---

## 📊 Results

![Revenue Forecast Visualization](https://github.com/user-attachments/assets/6a1479b9-8069-4b04-aff9-1799525350d0)

- The model provides a reasonable approximation of monthly sales trends.  
- Highlights the importance of accounting for **external factors** to improve predictive accuracy.  

---

## 🔍 Insights & Applications

- **Inventory Management:** Better stock planning based on predicted demand  
- **Marketing Strategy:** Targeted promotions according to forecasted trends  
- **Customer Segmentation:** Understanding sales behavior per store and category  

---

## 🛠️ Tools & Environment

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** `numpy`, `pandas`, `tensorflow`, `matplotlib`, `seaborn`  

---

## 📂 Repository Structure

```text
Forecasting-Sales-Revenue-Using-LSTM-Models/
├─ data/               # Raw and processed sales datasets
├─ notebooks/          # Jupyter notebooks with analysis and modeling
├─ models/             # Saved LSTM models
├─ README.md           # Project documentation
