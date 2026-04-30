# 🫀 Heart Disease Prediction

A machine learning web app that predicts the risk of heart disease based on clinical parameters.

🔗 **Live App:** [heartdiseaseprediction0004.streamlit.app](https://heartdiseaseprediction0004.streamlit.app/)

---

## 📌 Overview

This project uses a **Logistic Regression** model trained on the [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) to classify whether a patient is at high or low risk of heart disease. The model is deployed as an interactive web app using **Streamlit**.

---

## 🚀 Features

- Interactive UI to input patient clinical data
- Instant High / Low risk prediction
- Trained on 918 real patient records
- Deployed live on Streamlit Community Cloud

---

## 🧠 Model Details

| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression ✅ | 86.96% | 88.46% |
| KNN | 86.41% | 88.15% |
| Naive Bayes | 84.78% | 86.14% |
| SVM | 84.78% | 86.67% |
| Decision Tree | 79.89% | 81.59% |

Logistic Regression was selected as the best performing model.

---

## 📊 Input Features

| Feature | Description |
|---|---|
| Age | Age of the patient |
| Sex | M / F |
| Chest Pain Type | ATA / NAP / TA / ASY |
| Resting BP | Resting blood pressure (mm Hg) |
| Cholesterol | Serum cholesterol (mg/dL) |
| Fasting Blood Sugar | > 120 mg/dL (1 = Yes, 0 = No) |
| Resting ECG | Normal / ST / LVH |
| Max Heart Rate | Maximum heart rate achieved |
| Exercise Angina | Y / N |
| Oldpeak | ST depression induced by exercise |
| ST Slope | Up / Flat / Down |

---

## 🛠️ Tech Stack

- **Python**
- **Scikit-learn** — model training
- **Pandas** — data processing
- **Streamlit** — web app frontend
- **Joblib** — model serialization

---

## 📁 Project Structure

```
HeartDiseasePrediction/
├── app.py                        # Streamlit app
├── model.ipynb                   # Model training notebook
├── LogisticRegression_heart.pkl  # Trained model
├── scaler.pkl                    # StandardScaler
├── columns.pkl                   # Expected input columns
├── heart.csv                     # Dataset
└── requirements.txt              # Dependencies
```

---

## ⚙️ Run Locally

```bash
git clone https://github.com/Harshit997/HeartDiseasePrediction
cd HeartDiseasePrediction
pip install -r requirements.txt
streamlit run app.py
```

---

## 👤 Author

**Harshit** — [GitHub](https://github.com/Harshit997)
