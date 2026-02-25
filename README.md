# 🔋 Machine Learning Based Battery Management System :SOC, SOH and RUL Prediction of Lithium-ion Batteries

---

## Project Overview

This project presents a **Machine Learning based Battery Management System (BMS)** that predicts:

- 🔹 **State of Charge (SOC)**
- 🔹 **State of Health (SOH)**
- 🔹 **Remaining Useful Life (RUL)**

using battery operational data such as **voltage, current, temperature, and load conditions**.

The system helps improve **battery safety, performance, and lifespan** in:

- Electric Vehicles 🚗  
- Renewable Energy Storage 🔋  
- Portable Electronics 📱  

---

## 🎯 Objectives

- Predict battery **SOC, SOH and RUL**
- Analyze battery behavior using data visualization
- Compare multiple ML models
- Identify important battery parameters
- Build a simple prediction system

---

## 📂 Dataset

Dataset used: **NASA Lithium-ion Battery Dataset**

Features include:

- Voltage_measured  
- Current_measured  
- Temperature_measured  
- Current_load  
- Voltage_load  
- Current_charge  
- Voltage_charge  
- Time / Cycle data  

---

## 🧠 Machine Learning Models Used

- 🌳 **Random Forest Regressor (Primary Model)**
- 🌲 Decision Tree Regressor
- 📈 Linear Regression

---

## ⚙️ Methodology

1. Data preprocessing  
2. Feature selection  
3. Data sampling (10,000 rows for faster training)  
4. Model training (Random Forest)  
5. Model evaluation (MAE, RMSE, R²)  
6. Visualization (graphs + heatmap + feature importance)  
7. Prediction using user input  

---

## 📊 Results

- ✔ Low Mean Absolute Error (MAE)  
- ✔ Good R² Score (close to 1)  
- ✔ Accurate RUL prediction  
- ✔ Strong correlation between voltage and current  



