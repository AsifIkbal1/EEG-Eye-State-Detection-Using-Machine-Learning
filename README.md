# EEG-Eye-State-Detection-Using-Machine-Learning
A complete machine learning project to detect human eye open/close state using EEG signals, featuring data analysis, model training, and a Streamlit web application.
# 👁️ EEG Eye State Detection using Machine Learning

This project predicts whether a human eye is **Open or Closed** using EEG sensor signals.
It uses supervised machine learning models and a Streamlit-based web application.

---

## 📊 Dataset
- EEG Eye State Dataset
- 14 EEG numerical features
- Target: `eyeDetection` (0 = Open, 1 = Closed)

---

## 🧠 Models Used
- Logistic Regression
- Random Forest (Best)
- Gradient Boosting

---

## 🚀 Streamlit Web App
- Interactive UI
- Real-time EEG input
- Eye state prediction with confidence

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- Streamlit

---

## ▶️ Run the App
```bash
pip install -r requirements.txt
streamlit run app.py
