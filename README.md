# 🌱 Sustainable Air Quality Estimation using CNN and Cigarette Equivalent Visualization  

## 📘 Overview
This project aims to develop a **Sustainability-focused AI System** that predicts **Air Quality Index (AQI)** levels directly from **images** of the environment using **Convolutional Neural Networks (CNN)**.

The application also translates the predicted AQI into an **equivalent number of cigarettes smoked**, providing a powerful way to communicate health risks associated with poor air quality.

---

## 🧠 Core Idea
> “See the air, understand the risk.”

Instead of relying on expensive sensors, we use deep learning and open datasets to visually assess air quality.  
The model classifies input images into **six AQI categories** (Good → Hazardous) and maps them to cigarette equivalents for easy interpretation.

---

## 🧾 Dataset Information
**Dataset Name:** [Air Pollution Image Dataset from India and Nepal](https://www.kaggle.com/datasets/adarshrouniyar/air-pollution-image-dataset-from-india-and-nepal)  
**Total Images:** 12,240  
**Image Size:** 224×224  
**Classes:**
1. Good (0–50)  
2. Moderate (51–100)  
3. Unhealthy for Sensitive Groups (101–150)  
4. Unhealthy (151–200)  
5. Very Unhealthy (201–300)  
6. Hazardous (301–500)

Each image is labeled with **location, AQI value, and pollutants (PM2.5, PM10, CO, NO2, SO2, O3)**.

---

## ⚙️ Technical Stack
| Component | Technology |
|------------|-------------|
| **Modeling** | TensorFlow / Keras (CNN Transfer Learning - EfficientNet / ResNet) |
| **Backend API** | Flask |
| **Frontend UI** | Streamlit |
| **Visualization** | Matplotlib, Plotly |
| **Deployment** | Streamlit Cloud / Render / Docker |
| **Dataset Source** | Kaggle |

---

## 🚀 Features
- 🧩 **CNN-based AQI Classifier** trained on real-world environmental images  
- 📈 **PM2.5 → Cigarette Equivalent** calculator (based on Berkeley Earth research)  
- 🎨 **Interactive Streamlit Dashboard**  
- 🌓 Dark/Light mode support  
- 📊 Visual indicators (color-coded AQI scale)  
- 🧠 Explainable AI with Grad-CAM visualizations  

---

## 🔬 Project Architecture
