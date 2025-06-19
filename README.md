# 🛡️ fake-aadhar-detection

A machine learning project for detecting **fake Aadhar cards** and **credit cards** using deep learning and ensemble techniques. This repository includes modular Jupyter notebooks leveraging models like **VGG16**, **MobileNetV2**, and **ResNet50**, combined with **XGBoost**, to classify and verify the authenticity of document images.

---

## 🧠 Overview

This project aims to develop robust models for detecting **fake Aadhar cards and credit cards**. By combining deep learning feature extractors with **XGBoost** classifiers, the system can efficiently distinguish between genuine and fake documents. Both **Aadhar** and **credit card** classification tasks are supported.

---

## ✨ Features

- 🔍 Deep learning feature extraction using:
  - VGG16
  - MobileNetV2
  - ResNet50
- 🎯 Ensemble classification with **XGBoost**
- 🆔 Support for both **Aadhar** and **credit card** datasets
- 🧪 Modular, reproducible **Jupyter notebooks**

---

## 📁 Folder Structure
├── E_Gov_Project_VGG16_+_XG_Boost.ipynb
├── e-gov-project-mobilenetv2-xg-boost.ipynb
├── e-gov-project-resnet50-xg-boost.ipynb
├── resnet50-xgboost-creditcards.ipynb
└── README.md

---

## 📦 Datasets

### 🆔 **Synthetic Aadhar Card Dataset**  
**Source:** [Mendeley Data](https://data.mendeley.com/datasets/wk6n8fhx3c/1)  
- 1000 synthetic Aadhar images (front and back)
- Transformed using hue shifts, blurring, scaling, and more
- Suitable for OCR, face recognition, and fake detection

### 💳 **SuperCardSet Credit Card Dataset**  
**Source:** [GitHub](https://github.com/OttomanZ/SuperCardSet)  
- 10,000 randomized credit card images (Visa & MasterCard)
- Features fake names, card types, and numbers
- Ideal for training card detection & classification models

---

## 🚀 Getting Started

### 1. Clone this repository:
git clone https://github.com/<your-username>/fake-aadhar-detection.git
cd fake-aadhar-detection

### 2. Download the Datasets

### 3. Setup the Python Environment
