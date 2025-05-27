# Air-Quality-Index-AQI-Prediction
# 🌫️ Air Quality Index (AQI) Prediction

This project predicts the Air Quality Index (AQI) of Indian cities using environmental features such as PM2.5, PM10, NO₂, CO, SO₂, and O₃. It employs machine learning regression models to forecast AQI and visualize pollution levels regionally. The goal is to support proactive pollution control and public health planning.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Model Evaluation](#model-evaluation)
- [Results and Visualizations](#results-and-visualizations)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Introduction

Air pollution is a serious public health issue in India. Monitoring and forecasting AQI can help citizens and authorities take preventive measures. This project uses machine learning techniques to build an AQI prediction model based on various pollutant levels.

---

## ❗ Problem Statement

While real-time AQI data is available, predictive tools are lacking. This project addresses the need for accurate AQI forecasting using environmental parameters, enabling smarter pollution management and early warnings.

---

## 🎯 Objectives

- Predict AQI using historical environmental data.
- Identify key pollutant contributors to AQI.
- Evaluate multiple regression models for prediction accuracy.
- Visualize AQI levels across different Indian cities.

---

## 📊 Dataset

- **Source**: [OpenAQ](https://openaq.org), [CPCB India](https://cpcb.nic.in)
- **Format**: CSV
- **Features**: 
  - PM2.5, PM10
  - NO₂, SO₂, CO, O₃
  - AQI values
  - City and Date

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Folium, Plotly (for AQI maps)
- Jupyter Notebook

---

## 🧪 Methodology

1. **Data Preprocessing**: Cleaning, handling missing values, normalization.
2. **Model Building**:
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
3. **Model Evaluation**:
   - R² (coefficient of determination)
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
4. **Visualization**: Heatmaps, feature importance, regional AQI maps

---

## 📈 Model Evaluation

| Model              | R² Score | MAE   | RMSE  |
|-------------------|----------|-------|-------|
| Linear Regression | 0.70     | 15.2  | 22.3  |
| Random Forest     | 0.89     | 9.1   | 14.7  |
| XGBoost           | 0.91     | 8.5   | 13.9  |

---

## 📊 Results and Visualizations

- **Feature Importance**: PM2.5 and PM10 are primary contributors.
- **Map Visualization**: Interactive AQI maps using `folium` to highlight city-level pollution.
- **Model Accuracy**: XGBoost performed best with highest R² and lowest error metrics.

---

## 💻 Installation

Clone the repository and install required libraries:

```bash
git clone https://github.com/yourusername/aqi-prediction.git
cd aqi-prediction
pip install -r requirements.txt
