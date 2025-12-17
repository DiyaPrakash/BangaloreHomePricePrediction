# 🏠 Bangalore Home Price Prediction – End-to-End ML Project

This repository contains an **end-to-end Machine Learning project** that predicts house prices in Bangalore based on **location, total square feet, BHK, and number of bathrooms**.

✅ **Developed on Windows OS**  
✅ **Deployed on AWS using Flask + Nginx**

---

## 🚀 Project Overview

This project demonstrates the **complete Machine Learning lifecycle**, including:

- Data preprocessing and feature engineering  
- Model training and evaluation  
- Backend API development using Flask  
- Frontend integration using HTML, CSS, and JavaScript  
- Production deployment on **AWS EC2**

Users can interact with the web application to obtain **real-time house price predictions**.

---

## 🧠 Machine Learning Pipeline

### 1. Data Preprocessing
- Cleaning Bangalore housing data  
- Handling missing values and outliers  
- Feature engineering  

### 2. Model Training
- Regression-based Machine Learning model  
- Implemented using NumPy, Pandas, and Scikit-learn  
- Model serialized using Pickle  

### 3. Model Artifacts
- `bangalore_home_prices_model.pickle` – trained model  
- `columns.json` – feature metadata  

---

## 🖥️ Development Environment

- **Operating System:** Windows  
- **IDE / Tools:** VS Code, Jupyter Notebook  
- **Programming Language:** Python  

> All model development, experimentation, and local testing were performed on **Windows OS**.

---

## 🧩 Tech Stack

### Backend
- Python  
- Flask  
- NumPy  
- Pickle  

### Frontend
- HTML  
- CSS  
- JavaScript  
- jQuery  

### Deployment
- AWS EC2   
- Nginx  
- Flask API Server  

---

## 📂 Project Structure

```text
├── client/
│   ├── app.html        # Frontend UI
│   ├── app.css         # Styling
│   └── app.js          # Client-side logic
│
├── server/
│   ├── server.py       # Flask backend server
│   └── util.py         # Model loading & prediction logic
|   ├── artifacts/
│       ├── bangalore_home_prices_model.pickle
│       └── columns.json
├── nginx.conf          # Nginx reverse proxy configuration
├── Prediction.ipynb   # Model training & experimentation notebook
└── README.md
