# heart-disease-prediction-ml
“To install dependencies: pip install -r requirements.txt”
# 🧠 Heart Disease Prediction using Machine Learning

## 📌 Overview

This project predicts the presence of heart disease using machine learning techniques based on patient medical data. It applies multiple models and compares their performance to provide accurate predictions.

---

## 🚀 Features

* Uses real-world heart disease dataset
* Implements two machine learning models:

  * SGDClassifier (iterative training with epochs)
  * Random Forest Classifier (high accuracy)
* Feature scaling for improved performance
* Displays training time and accuracy
* Provides prediction for new patient data

---

## 📊 Dataset Features

The model uses the following medical attributes:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise-Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-learn

---

## ▶️ How to Run

### 1. Install dependencies

```bash
pip install pandas scikit-learn
```

### 2. Run the project

```bash
python main.py
```

---

## 📈 Output

* Epoch-wise training details (SGDClassifier)
* Accuracy of both models
* Final prediction result (Heart Disease / No Disease)

---

## 🎯 Results

* SGDClassifier Accuracy: ~70–80%
* Random Forest Accuracy: ~85–90%

---

## 🔍 Sample Prediction

The system predicts whether a patient has heart disease based on input values.

---

## 💡 Conclusion

This project demonstrates how machine learning can be used to analyze medical data and assist in early detection of heart disease.

---

## 📂 Project Structure

```
├── main.py
├── heart_data.csv
├── README.md
```

---

## 👨‍💻 Author

* Your Name

---
