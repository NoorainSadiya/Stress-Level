
# 😰 Stress Level Prediction from Smartphone Behavior

## 🔍 Overview
This project uses behavioral smartphone signals to predict **daily stress levels** in students. It emphasizes explainability using **SHAP**, making results interpretable and human-centric.

---

## 📌 Problem Statement
How accurately can we classify stress levels using features like screen unlocks, ambient light, and conversation frequency?

---

## 🛠 Tools & Technologies
- Python  
- Scikit-learn  
- Pandas, NumPy  
- SHAP  
- StudentLife Dataset

---

## 📈 Approach
1. **Data Preprocessing**
   - Extracted behavioral features from phone logs (e.g., night-time usage, sound level)
2. **Model Training**
   - Trained multiple models; selected best based on accuracy and interpretability
3. **Feature Selection**
   - Applied SHAP to reduce feature space to 7 key predictors
4. **Interpretation**
   - Used SHAP plots to explain individual and overall feature contributions

---

## ✅ Results
- Achieved **75% accuracy**
- Key features: night-time phone use, light levels, reduced social interaction
- Human-centric insights: aligned with psychological findings on stress

---

## 📂 Dataset
- **StudentLife Dataset**: Rich behavioral dataset from Dartmouth students
  - Includes phone, audio, light, GPS, and survey data  
  - Details: [StudentLife Dataset](https://studentlife.cs.dartmouth.edu/dataset.html)

---
