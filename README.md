# 🔧 Back EMF Based Motor Fault Detection using Machine Learning

This project was developed during my research internship at **IDEAS - Institute of Data Engineering, Analytics, and Science Foundation**, Indian Statistical Institute, Kolkata (May–July 2025).

The objective was to detect fault conditions in electric motors using **back EMF signals**, applying **signal processing** techniques and **machine learning** for classification.

---

## 🧠 Objectives
- Extract statistical and spectral features from back EMF signals.
- Perform signal cleaning, FFT analysis, and harmonic distortion computation.
- Train ML models (Random Forest, SVM) to classify healthy vs faulty motor states.
- Reduce dimensionality using PCA for visualization and performance improvement.

---

## 🛠️ Technologies Used
- Python (pandas, NumPy, scikit-learn, matplotlib, seaborn)
- FFT, THD, Crest Factor, RMS
- PCA for feature reduction
- Jupyter Notebooks
- Streamlit (for prototype dashboard - optional)

---

## 📊 Key Features Extracted
- **RMS**
- **Crest Factor**
- **Total Harmonic Distortion (THD)**
- **FFT Harmonics (up to 19th)**
- **Peak-to-Peak, Skewness, Kurtosis**

---

## 📈 Model Performance
- **Random Forest** classifier achieved high accuracy (>90%) on test data.
- Evaluated using **confusion matrix**, **precision-recall**, and **feature importance**.

> 📌 All results are visualized inside the Jupyter notebook.

---

## 📂 Project Structure

