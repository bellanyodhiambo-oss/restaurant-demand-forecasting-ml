# 🍽️ AI-Powered Restaurant Demand Forecasting System

## 📌 Overview

This project implements a production-oriented machine learning pipeline designed to forecast daily restaurant demand. The objective is to help hospitality businesses optimize staffing, inventory management, revenue forecasting, and reduce operational waste.

The system combines time-series forecasting techniques with ensemble regression models to generate accurate, business-ready demand predictions.

---

## 🎯 Business Objective

Restaurants frequently face operational inefficiencies due to inaccurate demand estimation, resulting in:

- Food waste from overstocking  
- Revenue loss from stockouts  
- Inefficient labor scheduling  
- Poor peak-hour planning  

This project delivers a predictive analytics framework that supports data-driven operational decision-making.

---

## 🧠 Machine Learning Architecture

### Models Implemented

- Prophet – Time-series forecasting with seasonality modeling  
- Random Forest Regressor – Non-linear regression baseline  
- XGBoost Regressor – Gradient boosting performance model  

### Feature Engineering

- Day-of-week encoding  
- Weekend indicator  
- Lag features (t-1, t-7)  
- Rolling averages (7-day window)  
- Holiday indicators  
- Seasonal decomposition components  

---

## 📊 Model Performance

- Improved forecasting accuracy over naive baseline models  
- Reduced simulated demand prediction error  
- Enhanced labor allocation alignment  
- Operational efficiency improvement simulation  

(Model metrics such as MAE, RMSE, and MAPE can be added in future iterations.)

---

## 🏗️ Project Structure

