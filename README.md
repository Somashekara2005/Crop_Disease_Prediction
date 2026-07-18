# 🌾 Smart Agriculture Assistant
### AI-Powered Crop Recommendation, Fertilizer Suggestion & Plant Disease Detection System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Flask](https://img.shields.io/badge/Flask-WebApp-black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Smart Agriculture Assistant is an AI-powered web application that assists farmers in making data-driven agricultural decisions. The system combines Machine Learning and Deep Learning techniques to provide intelligent recommendations for crop selection, fertilizer usage, and plant disease diagnosis.

The application analyzes soil nutrients, environmental conditions, and plant leaf images to help improve crop productivity while promoting sustainable farming practices.

---

## ✨ Key Features

### 🌾 Crop Recommendation

Predicts the most suitable crop based on soil nutrients and climatic conditions.

**Input Parameters**

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall

**Output**

- Recommended crop
- Prediction confidence (optional)
- Suitable growing conditions

---

### 🌿 Fertilizer Recommendation

Suggests fertilizers by comparing current soil nutrient levels with the ideal nutrient requirements of the selected crop.

**Input**

- Crop Name
- Nitrogen
- Phosphorus
- Potassium

**Output**

- Nutrient Deficiency/Excess
- Recommended Fertilizer
- Soil Improvement Suggestions

---

### 🍃 Plant Disease Detection

Uses a Convolutional Neural Network (CNN) model to identify plant diseases from uploaded leaf images.

**Input**

- Plant Leaf Image

**Output**

- Disease Name
- Disease Description
- Recommended Treatment
- Preventive Measures

---

## 🎯 Objectives

- Improve crop productivity
- Reduce fertilizer misuse
- Detect plant diseases at an early stage
- Promote precision agriculture
- Support sustainable farming using AI

---

## 🧠 Machine Learning Models

| Module | Algorithm |
|---------|-----------|
| Crop Recommendation | Random Forest Classifier |
| Fertilizer Recommendation | Rule-Based Recommendation System |
| Disease Detection | Convolutional Neural Network (TensorFlow/Keras) |

---

## 📊 Dataset Sources

### Crop Recommendation Dataset
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

### Fertilizer Recommendation Dataset
https://github.com/Gladiator07/Harvestify

### Plant Disease Dataset
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

---

## 🛠️ Technology Stack

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- TensorFlow
- Keras
- NumPy
- Pandas

### Computer Vision

- OpenCV

### Backend

- Flask

### Frontend

- HTML
- CSS
- JavaScript
- Bootstrap

---

## 📂 Project Structure

```
Smart-Agriculture-Assistant/
│
├── dataset/
│
├── models/
│   ├── crop_model.pkl
│   ├── fertilizer_model.pkl
│   └── disease_model.h5
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── crop.html
│   ├── fertilizer.html
│   └── disease.html
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📸 Application Screenshots

### 🏠 Home Page

![Home](images/Home.png)

---

### 🌾 Crop Recommendation

![Crop Recommendation](images/crop-result.png)

---

### 🌿 Fertilizer Recommendation

![Fertilizer Recommendation](images/fertilizer-result.png)

---

### 🍃 Plant Disease Detection

![Disease Detection](images/disease-result.png)

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Smart-Agriculture-Assistant.git
```

### Navigate

```bash
cd Smart-Agriculture-Assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 🔮 Future Enhancements

- Weather API Integration
- Real-time Soil Sensor Support (IoT)
- Multi-language Farmer Interface
- Voice Assistant Support
- Mobile Application
- Fertilizer Cost Optimization
- Market Price Prediction
- Crop Yield Prediction

---

## 👨‍💻 Author

**Somashekara G**

Computer Science Engineer

Skills:
- Python
- Machine Learning
- Deep Learning
- Flask
- TensorFlow
- OpenCV

---

