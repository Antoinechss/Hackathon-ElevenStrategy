<h1 align="center">Hackathon Eleven Strategy — Theme Park Waiting Time Prediction</h1>

<p align="center">
  <em>
    Machine learning models to predict attraction waiting times at t+2h during an academic hackathon.
  </em>
</p>

<p align="center">
  <img width="650" alt="Theme Park Waiting Time Prediction" src="https://github.com/user-attachments/assets/f65309af-9270-4ffc-bf0e-1f6800c93685" />
</p>

---

## Overview

This project was developed during the **M1 Introduction Week Hackathon**, organized by
**Eleven Strategy**.

The objective was to use historical data to **predict waiting times two hours ahead (t+2h)**
for three attractions in a theme park, using supervised machine learning techniques.

---

## Methodology

### Feature Engineering

- Raw data preprocessing and feature construction implemented in  
  [`feature_engineering.py`](feature_engineering.py)

---

### Models

Two approaches were explored:

- **Linear Regression**
  - Implemented in [`theme_park_linear.py`](theme_park_linear.py)
  - Achieved an RMSE of **9.54**

- **XGBoost Regressor**
  - Implemented in [`theme_park_xgb.py`](theme_park_xgb.py)
  - Improved performance with an RMSE of **8.81**

---

## Submission Format

Predictions were submitted as a CSV file with the following structure:

DATETIME | ENTITY_DESCRIPTION_SHORT | y_pred | KEY


---

## Context

This project focuses on:
- Feature engineering
- Model comparison
- Regression performance optimization under time constraints

It was completed in a **hackathon setting**, emphasizing rapid experimentation and iteration.
