# 🚦 AI-Powered Traffic Demand Forecasting System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-orange)
![CatBoost](https://img.shields.io/badge/CatBoost-Boosting-yellow)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter%20Optimization-red)

An end-to-end machine learning system developed for an inter-college ML competition to forecast urban traffic demand using advanced spatiotemporal feature engineering and ensemble learning techniques.

---

## 🎯 Project Summary

- Dataset: 77,299 training records and 41,778 test records
- Geographic Coverage: 1,249 locations
- Competition Scale: 600 competing teams
- Best Competition Score: **91.47 R²**
- Ensemble Models: CatBoost, LightGBM, XGBoost

---

## 🚀 Highlights

- Built an end-to-end traffic demand forecasting pipeline.
- Engineered 35+ spatial and temporal features.
- Implemented leakage-free OOF target encoding.
- Tuned multiple gradient boosting models using Optuna.
- Developed stacking and weighted ensemble strategies.
- Performed residual analysis to guide feature engineering.

---

## 📊 Feature Engineering

Features included:

- Cyclical hour encoding using sine/cosine transforms
- Quarter-hour temporal features
- Geohash decoding into latitude and longitude
- Road-weather interaction features
- Missing value indicators
- Highway peak interaction flags
- OOF target encodings

---

## 🧠 Modeling Pipeline

Dataset
↓
Feature Engineering
↓
5-Fold Cross Validation
↓
OOF Target Encoding
↓
CatBoost / LightGBM / XGBoost
↓
Optuna Hyperparameter Optimization
↓
Stacking Ensemble
↓
Weighted Blending
↓
Traffic Demand Prediction

---

## 📈 Performance

| Metric | Value |
|----------|---------|
| Competition Score | 91.47 R² |
| Training Rows | 77,299 |
| Test Rows | 41,778 |
| Geographic Locations | 1,249 |
| Competition Teams | 600 |

---

## 🛠 Tech Stack

Python • Pandas • NumPy • Scikit-learn • CatBoost • LightGBM • XGBoost • Optuna • Google Colab • geohash2

---

## 👨‍💻 Author

Rajanya Ganguli
B.Tech, Electrical Engineering
National Institute of Technology Agartala
