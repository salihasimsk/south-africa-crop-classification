# Satellite-Based Crop Classification

## Overview
This project investigates satellite-based crop classification using multi-sensor data fusion and machine learning. Sentinel-1 SAR and Sentinel-2 optical satellite data are combined through an early fusion approach to improve classification performance in heterogeneous agricultural areas.

The study is conducted on the Western Cape region of South Africa using 2017 growing season data.

---

## Objectives
- Evaluate the impact of multi-sensor data fusion on crop classification  
- Compare Random Forest and XGBoost models  
- Analyze the contribution of temporal features and per-class performance  

---

## Data & Features
- **Satellite Data:** Sentinel-1 (SAR), Sentinel-2 (Optical)  
- **Features:** Spectral indices (NDVI, EVI), temporal features, SAR polarization statistics  
- **Samples:** 5,419 balanced agricultural parcels  

---

## Methodology
- Feature engineering and early fusion of Sentinel-1 and Sentinel-2 data  
- Machine learning models: Random Forest, XGBoost  
- Evaluation using accuracy and F1-score  

---

## Key Results
- Multi-sensor fusion outperforms single-sensor approaches  
- Temporal features significantly improve classification performance  
- XGBoost consistently achieves better results than Random Forest  
- Perennial crops remain challenging due to spectral and phenological similarity  

---


