 🌾 Smart Agriculture - Crop and Fertilizer Recommendation System

🔍 **Project Overview**

This Smart Agriculture project leverages various machine learning models to:
- Recommend the most suitable **crop** to cultivate.
- Suggest the ideal **fertilizer** to use.

The recommendations are generated based on environmental and soil parameters, enhancing yield, reducing waste, and promoting sustainable farming practices.

---

📊 **Dataset**

The dataset includes sensor data on:
- Temperature
- Humidity
- pH Level
- NPK (Nitrogen, Phosphorus, Potassium)
- Rainfall

**Target Labels:**
- Crop Type
- Fertilizer Type

---

🧠 **Model Structure & Performance**

 🔹 `model` and `model_faulty`
These directories contain:
- **Decision Tree**
- **Random Forest**
- **Naive Bayes**

 🔹 `pnn` and `pnn_faulty`
These contain :
**Probabilistic Neural Network (PNN)** 

 🔹 `new_model` and `new_model_faulty`
These directories feature:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **XGBoost**

Note: Detailed accuracy metrics for Decision Tree, Random Forest, Naive Bayes, KNN, SVM, and XGBoost can be found in the individual model logs.

---

✅ **Best Performing Models**

**XGBoost** models showed the highest performance, particularly in crop prediction, with superior precision, recall, and F1 scores.

---

🔧 **Next Steps – Fault Detection Pipeline**

We are building a robust pipeline to detect sensor faults using:

1. **Abnormality Detection via PNN**
   - Classifies sensor readings as Normal or Faulty.

2. **Time-Aware Pattern Detection**
   - Models to analyze PNN outputs over time:
     - 🧠 LSTM (Long Short-Term Memory)
     - 📉 HMM (Hidden Markov Model)

---

👨‍💻 **Project Contributors**

- Somen Senapati (Leader)  
- Anurag Singh  
- Abhijit Sengupta  
- Srishti Kumari  
- Swarnim Kushwaha  
- Faiza Arfin  

**Supervised by:**  
Dr. Rakesh R. Swain (Faculty, ITER)
