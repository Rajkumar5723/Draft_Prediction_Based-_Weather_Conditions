# 🌬️ Draft Prediction using Weather Data and Regression

This project predicts air draft (wind draft in m/s) based on weather conditions such as temperature, humidity, pressure, wind speed, and wind direction using regression techniques.

---

## 📌 Problem Statement

Given a dataset of weather parameters, the goal is to build a regression model to accurately predict the **draft (m/s)**.

---

## 📊 Dataset

The dataset (`prediction.xlsx`) includes:

- Temperature (°C)
- Humidity (%)
- Pressure (hPa)
- Wind Speed (m/s)
- Wind Direction (°)
- Draft (m/s) — **target/output**

---

## 🧠 Technologies Used

- Python 🐍
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 🚀 Workflow

1. Load and preprocess the weather dataset.
2. Visualize data distributions and correlations.
3. Split into training and test sets.
4. Train a regression model (e.g., Linear Regression).
5. Evaluate the model using R² Score and MAE.
6. Predict draft values for new inputs.

---

## 📂 File Structure

```
📁 Weather-Draft-Prediction
│
├── new.ipynb              # Main notebook with model implementation
├── prediction.xlsx        # Weather dataset
├── README.md              # Project overview and instructions
```

---

## 📈 Sample Output

```python
Input: Temp=28°C, Humidity=60%, Pressure=980hPa...
Predicted Draft: 19.75 m/s
```

---


⭐ Star this repo if you found it useful!
