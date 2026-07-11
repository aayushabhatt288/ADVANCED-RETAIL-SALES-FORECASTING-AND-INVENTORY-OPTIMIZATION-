# ADVANCED-RETAIL-SALES-FORECASTING-AND-INVENTORY-OPTIMIZATION


### 📌 Overview

This project develops a machine learning-based retail sales forecasting system that predicts future sales using historical retail data and key outlet features. It also supports inventory optimization by recommending reorder quantities, safety stock and reorder points to improve inventory management and reduce overstocking and stockouts.

---
## ✨ Features

* 📊 **Interactive Dashboard** for visualizing retail sales insights.
* 🔍 **Data Preprocessing** with missing value handling, feature engineering, and categorical encoding.
* 📈 **Sales Forecasting** using multiple machine learning models with XGBRFRegressor as the final model.
* 📉 **Exploratory Data Analysis (EDA)** including distribution plots, boxplots, heatmaps, and sales analysis.
* 🤖 **Model Comparison and Evaluation** using R² score and Mean Absolute Error (MAE).
* 📦 **Inventory Optimization** with Economic Order Quantity (EOQ), Safety Stock, and Reorder Point calculations.
* 🌐 **Interactive Streamlit Web Application** for real-time sales prediction and inventory recommendations.
* 💾 **Model Serialization** using Joblib for easy deployment and future use.
* 📄 **CSV Upload Support** for batch sales prediction and inventory optimization.
* 📥 **Downloadable Prediction Reports** in CSV format for business analysis and decision-making.
---
## 🧠 Machine Learning Model

* **Algorithm:** XGBRFRegressor (XGBoost Random Forest)
* **Input Features:** Item_MRP, Outlet_Identifier, Outlet_Size, Outlet_Type, Outlet_Age
* **Performance Metrics:** R² Score, MAE (Mean Absolute Error)
* **Model Selection:** Chosen as the best-performing model after benchmarking six regression algorithms
* **Deployment:** Saved using Joblib and integrated into the Streamlit web application for real-time sales forecasting and inventory optimization.






