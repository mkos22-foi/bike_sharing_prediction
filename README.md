# 🚲 Bike Sharing Prediction – Challenge 365

Project for the course **Knowledge Discovery in Data** & **Artificial Intelligence in Business Practice**  
The goal of this project is to analyze and predict public bike usage using historical data

---

## 📌 Project Overview

This project is based on the dataset **bikesharing_daily.csv** (2011–2012).  
We analyze usage patterns and build machine learning models to predict:

- casual users  
- registered users  

---

## 📊 Dataset

The dataset contains 731 records and 16 features, including:

- weekday  
- month  
- temperature  
- weather conditions  
- humidity  
- wind speed  
- user type  

Unnecessary attributes (ID, date, season) were removed for better analysis.

---

## ⚙️ Machine Learning Models

Tested models:

- Linear Regression  
- Support Vector Regression (SVR)  
- Random Forest  
- Gradient Boosting Regressor (GBR)

👉 Best performance achieved by **Gradient Boosting Regressor**

---

## 📈 Results

- Most important feature: **temperature**
- Models predict casual users more accurately
- Clear growth trend over the years
- Casual users dominate on weekends, registered users on weekdays

---

## 🛠️ Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 👨‍🎓 Authors

- Petar Perenčević ([GitHub](https://github.com/Petarper))
- Maksim Kos
