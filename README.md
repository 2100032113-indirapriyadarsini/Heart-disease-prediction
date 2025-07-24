# Heart-disease-prediction
# ❤️ Heart Disease Prediction Using Machine Learning

This project predicts whether a person is likely to have heart disease using a Logistic Regression model trained on a structured medical dataset. The model was developed and evaluated in **Google Colab** and later tested in **Spyder IDE via Anaconda Navigator**.

---

## 📁 Project Overview

- Built a binary classification model using **Logistic Regression**.
- Performed exploratory data analysis (EDA), cleaned missing values, and verified dataset balance.
- Trained the model with a clean and preprocessed dataset using `train_test_split`.
- Deployed a predictive system for real-time diagnosis using new input data.

---

## 📊 Dataset Info

- **Features**:
  - age, sex, cp (chest pain), trestbps (resting BP), chol (cholesterol), fbs (fasting blood sugar), restecg, thalach, exang, oldpeak, slope, ca, thal
- **Target**:  
  - `0` – No heart disease  
  - `1` – Presence of heart disease
- **Shape**: 303 rows × 14 columns  
- **No missing values**

---

## 🛠️ Tools & Technologies

- **Language**: Python  
- **IDE/Platform**:  
  - [x] **Google Colab** (for model training)  
  - [x] **Spyder via Anaconda Navigator** (for local testing and execution)  
- **Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn (LogisticRegression, accuracy_score, train_test_split)

---

## 🧪 How It Works

1. Load and explore the dataset.
2. Clean and validate the data.
3. Split into training and test sets.
4. Train the model using `LogisticRegression()`.
5. Test model accuracy.
6. Build a system to input new patient data and return prediction.

---

## 🎯 Accuracy

- **Training Accuracy**: ~85.5%  
- **Testing Accuracy**: ~81.9%

---

## ▶️ How to Run

1. **Clone the repository** or download the `.ipynb` and `.py` files.
2. **Install required libraries**:
   ```bash
   pip install numpy pandas scikit-learn
