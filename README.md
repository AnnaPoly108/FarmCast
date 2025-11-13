# 🌾 FarmCast – AI Powered Milk Analysis System

FarmCast is an AI-driven web application that predicts **Milk Price**, **Milk Quality**, and **Cow Breed Type** using Machine Learning models trained on real-world MILMA dairy datasets.

It helps dairy farmers and collection centers make **fast, accurate, and data-driven decisions** based on milk composition.

---

## 📌 Features

### 🧠 Machine Learning Predictions
- 💰 **Price Prediction** (Random Forest Regressor)
- 🧪 **Quality Prediction** (KMeans Clustering → 0 = Low, 1 = Medium, 2 = High)
- 🐄 **Breed Prediction** (Random Forest Classifier)

### 🎨 Modern UI (Frontend)
- Transparent navbar with animated underline
- Glassmorphism-style cards
- 4-image background slideshow
- Clean, responsive Bootstrap design
- Interactive feature cards on homepage

### 🔐 Authentication System
- User Registration
- User Login
- Sessions & Access Control

### 📊 Input Parameters
Users provide:
- **SNF**
- **CLR**
- **Temperature**
- **FAT**

Output includes:
- Predicted Price  
- Predicted Quality (0/1/2 + Text)  
- Predicted Breed  

---

## 🛠️ Tech Stack

### **Backend**
- Python  
- Flask  
- Joblib  
- Scikit-Learn  

### **Frontend**
- HTML  
- CSS  
- Bootstrap  
- Custom Animations  

### **Machine Learning**
- RandomForestRegressor  
- RandomForestClassifier  
- KMeans Clustering  

