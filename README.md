# Spec2Price 💻📊

**Spec2Price** is a machine learning-powered web application that predicts laptop prices based on their specifications such as processor type, RAM size, storage capacity, GPU, and display features. Built with Python and Streamlit, the app aims to assist users in estimating fair laptop prices based on market data.

---

## 🚀 Features

- Predicts laptop prices using trained ML regression models.
- Supports multiple models: Linear Regression, Random Forest, etc.
- Clean and responsive UI powered by Streamlit.
- Real-time predictions with R² score up to **92%** on test data.
- Interactive dropdowns and sliders for user input.
- Supports over **1000+ laptop entries** from curated datasets.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit (Python)
- **Backend / ML**: Scikit-learn, Pandas, NumPy
- **Deployment**: Streamlit Cloud / Vercel
- **Data Visualization**: Matplotlib, Seaborn

---

## 📸 Demo

👉 [Live Demo](https://laptop-price-predictor-apaajym5lvjohinfp8uacw.streamlit.app/)



## 📁 Dataset

- Contains 1000+ labeled laptop records scraped from e-commerce sites.
- Features include: brand, processor, RAM, SSD/HDD, GPU, screen size, and OS.
- Data cleaned and preprocessed using pandas.

---

## 🧠 Machine Learning

- Compared multiple models:
  - 🔹 Linear Regression
  - 🔹 Random Forest Regressor
  - 🔹 Decision Tree
- Evaluated using R² Score, MAE, and RMSE.
- Best model: **Random Forest** with ~92% R² on test set.

---
