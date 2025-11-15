# ❤️ End-to-End Heart Disease Classification

This project contains an end-to-end machine learning pipeline to classify the presence of heart disease using structured medical data.

The entire workflow is implemented in:

- `end-to-end-heart-disease-classification-checkpoint.ipynb`

---

## 🎯 Objective  
Predict whether a patient is likely to have heart disease based on clinical features such as:

- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Serum cholesterol  
- Fasting blood sugar  
- Resting ECG  
- Maximum heart rate  
- Exercise-induced angina  
- Oldpeak  
- ST slope  
- And more…

---

## 🧠 What This Notebook Includes  
- Data loading & EDA  
- Feature engineering  
- Train/validation split  
- Model training (Logistic Regression / Random Forest / others)  
- Evaluation using accuracy, precision, recall, F1-score  
- Confusion matrix & ROC curve  
- End-to-end pipeline + model serialization  

---

## ▶️ How to Run

1. **Install dependencies**
```bash
pip install -r requirements.txt
```

2. **Launch Jupyter Notebook**
```bash
jupyter notebook end-to-end-heart-disease-classification-checkpoint.ipynb
```

3. Run the cells in order.

---

## 📂 Recommended Project Structure

```text
.
├── end-to-end-heart-disease-classification-checkpoint.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── models/
    └── (saved models go here)
```

---

## 📊 Dataset  
Commonly used dataset: **UCI Heart Disease Dataset**  
You may place your dataset inside a `data/` folder (ignored by Git).

---

## 📝 Ideas for Improvement  
- Try hyperparameter tuning (GridSearchCV / Optuna)  
- Use XGBoost / LightGBM  
- Deploy model using Streamlit or FastAPI  
- Add SHAP interpretability  

---

## 📜 License  
This project is licensed under the MIT License.

