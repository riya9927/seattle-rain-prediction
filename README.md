# 🌧️ Seattle Rain Prediction using Logistic Regression

This project builds a predictive model to detect the possibility of rain on a given day using historical weather data from Seattle (1948–2017). The model is based on Logistic Regression and trained on temperature and precipitation data.

---

## 📌 Objective

Predict whether it will rain on a given day in Seattle based on:
- **Precipitation (PRCP)**
- **Maximum Temperature (TMAX)**
- **Minimum Temperature (TMIN)**

---

## 🗃️ Dataset Overview

The dataset contains weather records from **January 1, 1948** to **December 12, 2017**.

### 📑 Features

| Column | Description |
|--------|-------------|
| `DATE` | Date of the observation |
| `PRCP` | Precipitation in inches |
| `TMAX` | Maximum temperature (°F) |
| `TMIN` | Minimum temperature (°F) |
| `RAIN` | Target column: `True` if it rained, else `False` |

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Visualizations

Histograms and KDE plots for TMAX, TMIN, PRCP
Boxplots to detect and visualize outliers

---

## Accuracy

~90.5%
