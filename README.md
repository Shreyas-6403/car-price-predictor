# 🚗 Car Price Predictor

## 📌 Overview  
The **Car Price Predictor** is a machine learning-based web application that estimates the selling price of a used car based on various factors such as brand, model, purchase year, fuel type, kilometers driven, transmission mode, and more. The project is built using **Flask**, **Machine Learning**, and **Streamlit** to provide an interactive and user-friendly interface.  

---

## 🏗 Features  
### ✅ Predicts the price of a used car based on user inputs  
### ✅ Supports multiple car brands and models  
### ✅ Interactive web interface for easy input and results display  
### ✅ Machine learning model trained on real-world data  
### ✅ Flask-based backend for processing user input and predictions  

---

## ⚙️ Technologies Used  

### - **Machine Learning** (Linear Regression)  
### - **Flask** (Backend Framework)  
### - **Streamlit** (Web Interface)  
### - **Pandas** (Data Handling)  
### - **Scikit-learn** (ML Model Training)  
### - **Numpy** (Numerical Computation)  
### - **Matplotlib & Seaborn** (Data Visualization)  

---

## 🚀 How the Project Works  

### 1️⃣ **Data Collection & Preprocessing**  
   - A dataset containing used car details is cleaned and preprocessed.  
   - Categorical features (Fuel Type, Transmission, etc.) are encoded into numerical values.  

### 2️⃣ **Model Training**  
   - A **Linear Regression Model** is trained using the dataset.  
   - The trained model is saved as `LinearRegressionModel.pkl`.  

### 3️⃣ **Web Application Development**  
   - **Flask** is used to build the web server.  
   - **HTML, CSS, and Streamlit** create the interactive interface.  

### 4️⃣ **Prediction Process**  
   - User inputs car details in the web app.  
   - The trained model predicts the price based on inputs.  
   - The predicted price is displayed on the web interface.
---

