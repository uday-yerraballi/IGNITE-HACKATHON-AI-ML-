# ⚡ Electricity Bill Price Predictor

A machine learning–powered web app that predicts your **monthly electricity bill** based on appliance usage and tariff rate. Built with `scikit-learn`, `Streamlit`, and hosted on Streamlit Cloud.

> 🔗 **Live App**: [Click here to try it out 🚀](https://4lapp4bqtrwbkwxjwewkvfz.streamlit.app/)

---

## 📌 Overview

This project helps users estimate their electricity bills by inputting usage details of common household appliances and the current electricity tariff rate. The model was trained on a simulated dataset of over 45,000 electricity usage records.

---

## 🎯 Features

- 🔢 Input fields for:
  - Fan, Refrigerator, AC, TV, Monitor, Motor Pump usage
  - Monthly total appliance usage (in hours)
  - Tariff rate (₹/unit)
- 📈 Correlation graph showing feature impact
- 🧠 Trained `LinearRegression` model for predictions
- ✅ Clean and responsive Streamlit frontend

---

## 📊 Sample Input Features

| Feature          | Description                                 |
|------------------|---------------------------------------------|
| Fan              | Fan usage (in kWh)                          |
| Refrigerator     | Refrigerator usage (in kWh)                 |
| AirConditioner   | AC usage (in kWh)                           |
| Television       | TV usage (in kWh)                           |
| Monitor          | Monitor usage (in kWh)                      |
| MotorPump        | Motor pump usage (in kWh)                   |
| MonthlyHours     | Total monthly usage hours                   |
| TariffRate       | ₹ per unit electricity cost                 |

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- NumPy, Pandas
- Matplotlib, Seaborn
- Streamlit
- GitHub + Streamlit Cloud for deployment

---

## 🚀 Deployment

The app is deployed on **Streamlit Cloud** and accessible via:

> 🌐 [https://4lapp4bqtrwbkwxjwewkvfz.streamlit.app/](https://4lapp4bqtrwbkwxjwewkvfz.streamlit.app/)

No installation required — open the link and start predicting bills!

---



