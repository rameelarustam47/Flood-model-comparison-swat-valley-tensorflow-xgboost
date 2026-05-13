# Flood Prediction Model Comparison in Swat Valley (2025)

## 🌊 Study Area

Swat Valley

---

## 📊 Objective

This study compares **TensorFlow deep learning** and **XGBoost machine learning** models for flood prediction using multi-source remote sensing and environmental data.

---

## 📡 Data Sources

* Sentinel-1 SAR (pre and during flood)
* SRTM DEM (30m)
* Slope derived from DEM
* CHIRPS rainfall data

---

## ⚙️ Methodology

### Data Processing

* Feature extraction from SAR and DEM
* Data balancing using SMOTE

### Models

* TensorFlow Neural Network (Deep Learning)
* XGBoost Classifier (Machine Learning)

---

## 📈 Results Comparison

| Metric           | TensorFlow | XGBoost |
| ---------------- | ---------- | ------- |
| Accuracy         | 99.88%     | 99.58%  |
| Flood F1         | 1.00       | 1.00    |
| No Flood F1      | 1.00       | 0.99    |
| Training Speed   | Slower     | Faster  |
| Interpretability | Low        | High    |

---

## 🧠 Key Findings

* TensorFlow achieved slightly higher accuracy and perfect classification performance
* XGBoost was faster and provided feature importance for interpretability
* Both models performed strongly for flood detection tasks

---

## 🌍 Physical Interpretation

Terrain-based variables (DEM, slope) and rainfall data were used to incorporate **hydrological behavior into both models**, making the approach partially physically-informed.

---

## 🎯 Conclusion

TensorFlow is more suitable for maximum accuracy, while XGBoost is better for interpretability and faster deployment in real-world systems.

---

## 🛠️ Tools Used

* TensorFlow
* XGBoost
* Google Earth Engine
* Scikit-learn
* Google Colab
* ## 🔗 Related Project

TensorFlow-based Flood Prediction (Swat Valley):
https://github.com/rameelarustam47/flood-prediction-swat-valley-tensorflow
