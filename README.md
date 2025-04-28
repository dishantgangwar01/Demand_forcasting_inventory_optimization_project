# Demand_forcasting and inventory_optimization_project

---

# Demand Forecasting and Inventory Optimization  


## Overview

This project focuses on solving a classic supply chain management problem: **Demand Forecasting** and **Inventory Optimization**.  
By accurately predicting future demand and strategically managing inventory, businesses can improve operations, reduce costs, and enhance customer satisfaction.

The project walks through the process of using historical sales and inventory data to:
- Forecast future product demand
- Calculate safety stock levels
- Determine reorder points
- Apply Economic Order Quantity (EOQ) models
- Define the reorder cycle  

The product under analysis is labeled **Product_ID: P1**.

---

##  Dataset

The dataset provided includes:
- **Date**: Daily timestamps of sales and inventory data
- **Demand**: Units demanded per day
- **Inventory**: Available stock on each date

This data forms the basis for building forecasting models and optimizing inventory planning.

---

## 🔧 Tools and Libraries

- **Python 3.x**
- **Pandas**: Data manipulation
- **NumPy**: Numerical calculations
- **Matplotlib**: Data visualization
- **Statsmodels**: SARIMA modeling
- **Scikit-learn**: Model validation and evaluation

---

##  Process

### 1. Exploratory Data Analysis (EDA)
- Analyze demand patterns, identify seasonality, and visualize trends.
- Check for stationarity using statistical tests.

### 2. Demand Forecasting
- Use **SARIMA** (Seasonal ARIMA) for modeling demand due to visible seasonal effects.
- Determine optimal parameters (**p**, **d**, **q**, **P**, **D**, **Q**, **s**) using **ACF** and **PACF** plots.
- Forecast demand for the next 10 days.

### 3. Inventory Optimization
- **Safety Stock Calculation**: Based on standard deviation of demand and desired service levels.
- **Reorder Point (ROP)**: Sum of average lead-time demand and safety stock.
- **Economic Order Quantity (EOQ)**: Find the optimal order quantity minimizing holding and ordering costs.
- **Reorder Cycle**: Define the time interval between order placements.

---

## 📊 Key Concepts

- **Demand Forecasting**: Estimating future customer demand to avoid stockouts or excess inventory.
- **Safety Stock**: Buffer stock held to protect against uncertainties in demand and supply.
- **Reorder Point**: Inventory level triggering a replenishment order.
- **Economic Order Quantity (EOQ)**: Ideal quantity to order each time to minimize total inventory costs.

---

## 📁 Project Structure

```
Demand_Forecasting_Inventory_Optimization
 ┣ 📜 DF&inventory.ipynb
 ┣ 📜 demand_inventory.csv
 ┣ 📜 README.md
```

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Install required libraries:  
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
```
3. Open the Jupyter Notebook (`.ipynb`) and run through the cells.
4. Explore forecast outputs and inventory optimization strategies.

---

## 📌 Conclusion

This project demonstrates a practical approach to **forecasting product demand** and **optimizing inventory** based on statistical modeling techniques. By applying SARIMA for demand prediction and EOQ models for inventory decisions, businesses can balance costs with customer satisfaction efficiently.

---

## 👨‍💻 Author

- Dishant Gangwar

---
