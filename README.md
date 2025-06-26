# 🧠 Illinois-Sandia Data Challenge 2024  
**UIUC x Sandia National Laboratories Datathon Project**  
**Title**: *Predicting Spanish Bilingualism from EEG Neural Signal Data*

---

### 📌 Overview  
This project was developed during a three-day datathon in collaboration with Sandia National Laboratories. Our goal was to build a machine learning model that predicts whether a participant is a Spanish-English bilingual based on EEG (electroencephalography) data collected during a language-processing task.

---

### 💡 Objective  
Design and evaluate a predictive model that classifies Spanish bilingual speakers by analyzing ERP (event-related potential) signal activity—specifically focusing on the N400 window (300–500ms), known to be relevant in language comprehension.

---

### 🛠️ What We Did  
- Processed raw EEG recordings from 10+ participants across translation and unrelated word pair conditions  
- Extracted average signal activity from the 300–500ms time window (N400 response)  
- Engineered participant-level features for classification  
- Built and evaluated Random Forest classifiers to predict bilingualism  
- Addressed class imbalance using SMOTE oversampling  
- Documented all preprocessing, modeling steps, and results clearly

---

### 🧰 Tech Stack  
**Language**: Python  
**Libraries**:
- `pandas`, `numpy` – data wrangling and numerical operations  
- `scikit-learn` – modeling, train-test splits, SMOTE, evaluation  
- `matplotlib`, `seaborn` – for potential future visualizations  

---

### 🧹 Recent Update  
I recently cleaned and reorganized the notebook to improve clarity and structure. This included adding markdown explanations for each section, modularizing the data pipeline, and preparing the code for future enhancements like visualizations or model comparisons.


