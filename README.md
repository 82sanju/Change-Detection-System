# Change-Detection-System

# 🌍 Integrated Framework for Accurate Change Detection and Deforestation Identification in Satellite Imagery

Official repository for the IEEE conference paper:

**Integrated Framework for Accurate Change Detection and Deforestation Identification in Satellite Imagery**  
*Prabu M, Simhachalam Sanju Preetham, Devakrishnan TU*  
Published March 2024 in the 2024 IEEE International Conference on Contemporary Computing and Communications (InC4), DOI: 10.1109/InC460750.2024.10649388 :contentReference[oaicite:1]{index=1}.

📄 [Published in IEEE Conference 2024 — Click Here to View](#) *(https://ieeexplore.ieee.org/document/10649388)*

---

## 📚 Abstract

This work presents a hybrid machine‑learning framework combining deep learning, image preprocessing, and vegetation indexing (NDVI) to accurately detect land cover change and identify deforestation from multi‑temporal satellite imagery.

---

## 🎯 Objectives

- Build a pipeline for detecting land cover changes, with emphasis on deforestation.
- Use combined optical and SAR imagery.
- Leverage state-of-the-art deep architectures (UNet/Siamese) with vegetation indices.
- Evaluate performance using Accuracy, Precision, Recall, F1-score, and Kappa coefficient.

---

## 🧠 Methodology

1. **Data Preprocessing**  
   - Cloud filtering, normalization, image registration (e.g. Sentinel-2 optical, Sentinel-1 SAR)
2. **Change Detection Module**  
   - Siamese UNet-style deep network to classify pixel-level change
3. **Deforestation Identification**  
   - Post-classification using NDVI thresholds and morphological filters
4. **Model Evaluation Metrics**  
   - Computed metrics: Accuracy, Precision, Recall, F1-score, Kappa coefficient

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / PyTorch  
- OpenCV, NumPy  
- Rasterio, GDAL  
- Matplotlib, Seaborn  
- QGIS for geospatial validation

---


## 📊 Expected Results

- Our experiments yielded:
- Accuracy: ~94–95%
- Precision: ~93%
- Recall: ~92–93%
- F1‑Score: ~92–93%

---
