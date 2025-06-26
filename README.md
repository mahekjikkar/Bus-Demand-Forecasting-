# 🚌 Bus Demand Forecasting – RedBus Data Hackathon

This project involves predicting future seat demand on bus routes using historical booking and search data provided by RedBus. The goal was to build a model that forecasts demand 15 days in advance to help with capacity planning and optimization.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- LightGBM
- Scikit-learn
- Matplotlib, Seaborn

---

## 📌 Problem Statement
Predict the number of seats likely to be booked on specific bus routes 15 days ahead of the journey date, using search and booking history, route details, and calendar features.

---

## 📊 Approach

- **Data Exploration**: Analyzed trends in bookings and searches by date, route, and region.
- **Feature Engineering**: Created time-based, region-wise, and event-related features (e.g., holidays, weekends, school vacations).
- **Modeling**: Trained a LightGBM regression model with cross-validation and custom tuning.
- **Evaluation**: Assessed using RMSE on validation set (internal evaluation).

---

## 🚀 Key Learnings

- Worked on real-world demand forecasting using time series and tabular data.
- Improved skills in feature engineering and model tuning.
- Gained practical experience with regression modeling in a business context.

---

## 📌 Note

This project was done as part of a RedBus Data Hackathon for learning and skill-building purposes. Data is anonymized or simulated for public sharing.


