
# 🌱 Climate Analyzer  
**AI-Based Vegetation Stress Detection and Climate Risk Prediction**

---

## 📌 Overview
Climate Analyzer is a deep learning-based system that detects vegetation stress using satellite imagery and predicts future climate conditions to generate actionable risk insights. The system combines spatial analysis (CNN) with temporal forecasting (LSTM) to produce an integrated risk assessment.

---

## 🚀 Features
- NDVI-based vegetation stress detection  
- CNN (TinyUNet) for pixel-level stress mapping  
- LSTM for rainfall and temperature forecasting  
- Risk classification (Low / Medium / High)  
- Visual outputs: NDVI maps, stress maps, risk maps, trend charts  

---

## 🧠 Methodology
1. **Data Collection**
   - Sentinel-2 satellite imagery  
   - ERA5 climate data  

2. **Preprocessing**
   - Cloud masking  
   - NDVI computation  
   - Time alignment  

3. **Modeling**
   - CNN → Spatial stress detection  
   - LSTM → Climate forecasting  

4. **Fusion**
   - Combine stress + climate anomalies  
   - Generate final risk level  

---

## 📊 Results
- CNN: F1 Score ≈ 0.71, IoU ≈ 0.56  
- LSTM: MAE ≈ 35.88, RMSE ≈ 46.45  
- Fusion: Hit Rate ≈ 83%, False High Rate ≈ 8%  

---

## 📷 Outputs
- NDVI Comparison (Baseline vs Current)  
- Stress Detection Map  
- Risk Classification Map  
- Rainfall & Temperature Forecast Graphs  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib  
- OpenCV  
- Google Colab  

---


## 🎯 Applications

* Agriculture monitoring
* Drought early warning systems
* Climate risk assessment
* Decision support for farmers

---

## 📌 Future Work

* Real-time deployment
* Mobile/web dashboard
* Multi-region scalability
* Improved model accuracy

---

## 👩‍💻 Authors

* Sabreen Ashika. M
* Monikka. B



```
```
