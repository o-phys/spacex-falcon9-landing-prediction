# 🚀 SpaceX Falcon 9 Landing Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Data Science](https://img.shields.io/badge/Data%20Science-Project-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Project Overview

This project analyzes **SpaceX Falcon 9 launch data** to predict whether the **first stage of the rocket will successfully land**.  
Reusable rocket technology is essential for **reducing launch costs and improving mission efficiency**.

The project follows a **complete data science workflow**, including data collection, data wrangling, exploratory data analysis, interactive visualizations, and machine learning modeling.

---

## 📡 Data Collection

Launch data was collected using the **public SpaceX API** through Python HTTP requests.

The retrieved data was returned in **JSON format** and converted into a **pandas DataFrame** for analysis.

The dataset was filtered to include only **Falcon 9 launches**, which are relevant for landing prediction analysis.

---

## 🧹 Data Preparation

The dataset was cleaned and processed by:

- Removing irrelevant records (Falcon 1 launches)
- Handling missing values
- Selecting relevant features for analysis and modeling

Key variables include:

- Launch Site
- Payload Mass
- Orbit Type
- Booster Version
- Flight Number
- Landing Outcome

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand how different variables affect landing success.

Several visualizations were used to analyze relationships between:

- Payload mass and landing success
- Launch site performance
- Orbit type and landing outcome
- Flight number and mission success

---

## 🗺️ Interactive Visualizations

Interactive maps were created to visualize **SpaceX launch sites and landing outcomes**.

These visual tools allow users to explore:

- Launch site locations
- Payload ranges
- Mission success distribution

---

## 🤖 Machine Learning Models

Several classification models were trained to predict Falcon 9 landing success:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using **GridSearchCV with cross-validation**.

---

## 📈 Results

All models achieved similar predictive performance with an average **test accuracy of approximately 83%**.

This shows that machine learning models can effectively predict Falcon 9 landing outcomes using historical launch data.

---
## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Folium  
- Plotly  

---

## 🎯 Conclusion

This project demonstrates how **data science and machine learning techniques** can be applied to analyze **space mission data** and predict rocket landing success.

Reusable launch systems such as **Falcon 9** represent a major advancement in reducing space mission costs and improving launch efficiency.

---

⭐ If you found this project interesting, feel free to **star the repository!**
