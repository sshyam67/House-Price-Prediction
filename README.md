# 🏠 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange)
![License](https://img.shields.io/badge/license-MIT-green)

> A regression-based machine learning model to predict house prices based on key features like area, bedrooms, location, and amenities. The project focuses on data cleaning, feature engineering, model comparison, and visualization.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [What I Learned](#what-i-learned)
- [Author](#author)

---

## 📍 Project Overview

This project predicts housing prices using multiple regression models. It aims to help potential buyers, real estate investors, and agencies make data-driven decisions.

The model is trained on features like:
- Area (sq.ft)
- Bedrooms
- Bathrooms
- Location
- Amenities (balcony, parking, etc.)

---

## 🚀 Features

- 🧼 Data cleaning and outlier removal  
- 📊 Exploratory Data Analysis (EDA) with visualizations  
- 🧠 Trained multiple regression models  
- 🔍 Compared Linear Regression, Decision Trees, Random Forest  
- 📉 Evaluation using RMSE and R² metrics  
- 📈 Visualized predictions vs. actual prices

---

## 📁 Dataset

- Source: [Kaggle / UCI Repository / Custom]  
- Format: CSV  
- Size: ~1,300 rows × 9 columns  
- Target Variable: `price`  
- Feature Examples: `area`, `bedrooms`, `location`, `balcony`, `parking`

---

## 🛠 Technologies Used

- **Python 3.x**  
- **Pandas, NumPy** – for data preprocessing  
- **Matplotlib, Seaborn** – for visualization  
- **Scikit-learn** – for modeling and evaluation  
- **Jupyter Notebook** – for interactive development

---

## ▶️ How to Run

```bash
git clone https://github.com/sshyam67/house-price-prediction
cd house-price-prediction
pip install -r requirements.txt
jupyter notebook house_price_model.ipynb
📊 Results
Best Model: Random Forest Regressor

RMSE: [58,000]

R² Score: [0.88]

📷 Visuals coming soon

🧠 What I Learned
Building pipelines for regression problems

Feature scaling and encoding techniques

Tuning ML models using GridSearchCV

Communicating model results effectively using visuals

👨‍💻 Author
Shyam Krishna S – Data Analyst | Machine Learning Enthusiast
📧 shyamkrishna9848@gmail.com
🔗 LinkedIn | GitHub

