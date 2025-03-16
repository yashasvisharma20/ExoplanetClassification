# 🔭 Exoplanet Classification using Random Forest 🌌  

## 🚀 Project Overview  
This project builds a **Random Forest classification model** to detect exoplanets using **light curve data** from space telescopes like Kepler and TESS. The goal is to classify whether a given light curve corresponds to a **confirmed exoplanet** or a **false positive** using machine learning techniques.  

## 📂 Dataset  
The dataset contains **flux variations over time** (light curves) from stars, labeled as either **exoplanet candidate** or **non-exoplanet**. Data sources include:  
- **NASA Exoplanet Archive**  
- **Kepler & TESS mission datasets**  

📌 **Features include:**  
- Telescope
- Instrument 
- Pixel Scale
- PSF
- Image Type  

---

## 🔬 Methodology  
1. **Data Preprocessing**  
   - Handling missing values and outliers  
   - Normalizing flux intensity  
   - Feature engineering from time-series data  

2. **Feature Selection**  
   - Identifying key attributes for classification  
   - Dimensionality reduction (PCA, feature importance)  

3. **Model Training**  
   - Implemented **Random Forest Classifier**  
   - Tuned hyperparameters using **CalibratedClassifierCV**  
   - Evaluated  

4. **Results & Interpretation**  
   - Achieved high classification accuracy (~99%)  
   - Visualized feature importance  
  
---

## 📊 Results  
🔹 **Accuracy:** 99%  

---

## 🚀 How to Use  
### 🔹 Clone Repository  
```bash
git clone https://github.com/yashasvisharma20/ExoplanetClassification/edit/main/README.md
