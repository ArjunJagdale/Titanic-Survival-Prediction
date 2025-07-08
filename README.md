# 🎯 End-to-End ML Project: Titanic Survival Prediction - IBM SKILLSBUILD SUMMER INTERNSHIP PROJECT

This project demonstrates a **complete machine learning pipeline** tailored to reflect industry-level Experience in manipulating/transforming data, model selection, model training, and cross-validation.

## My internship completion certificate - 
![image](https://github.com/user-attachments/assets/4a718209-491a-42cb-908d-62a6ad398ecf)

---

## 📌 Project Summary

We developed an end-to-end machine learning system that predicts **Titanic passenger survival**, simulating a real-world risk classification scenario. It covers every aspect of a production-ready ML pipeline — from data ingestion to real-time model inference — using Python, Scikit-learn, and Gradio.

---

## ✅ Skills Demonstrated

### 📊 Data Manipulation & Transformation
- Cleaned and preprocessed missing and categorical values
- Scaled numeric features and applied one-hot encoding to categorical data
- Built a modular preprocessing pipeline using `ColumnTransformer` and `Pipeline`

### 🤖 Model Training & Selection
- Trained a `RandomForestClassifier` within a pipeline
- Tuned hyperparameters using `GridSearchCV` over:
  - `n_estimators`
  - `max_depth`
- Applied **5-fold cross-validation** for model robustness
- Selected best-performing model based on **ROC AUC score**

### 📈 Evaluation Metrics
- Achieved strong results on holdout data:
  - **Accuracy**: 76%
  - **F1-score (class 1)**: 0.71
  - **ROC AUC**: 0.84
- Used `classification_report` and `RocCurveDisplay` for comprehensive evaluation

### 🚀 Scalable Deployment
- Exported the trained model using `joblib`
- Integrated a **Gradio UI** for real-time prediction interface
- Simulated live usage where a user can input features and get survival predictions

---

## 📁 Project Structure

| File / Folder               | Description                                         |
|-----------------------------|-----------------------------------------------------|
| `notebook.ipynb`            | Full pipeline with preprocessing, training, CV, and deployment |
| `loan_default_model.joblib` | Serialized best-performing model                   |
| `predictions.csv`           | Model output with probability scores               |
| `README.md`                 | Documentation (you’re here!)                       |

---

## 💻 Gradio Interface

A live, interactive UI is included using **Gradio**. It lets you:

- Input custom passenger details
- Get survival prediction + probability
- Test the model without needing to run Jupyter cells manually

### Example:
![Screenshot 2025-07-08 151515](https://github.com/user-attachments/assets/3905e638-810d-43e7-a992-bc8a45805903)
![Screenshot 2025-07-08 151456](https://github.com/user-attachments/assets/9cc8a027-928a-49c4-ac9e-b9009fb65b18)
![Screenshot 2025-07-08 151526](https://github.com/user-attachments/assets/59d5d683-9071-4363-bcbe-9ff4d8774d04)


---

## This project clearly maps to the following real-world expectations:

- ✅ **Data Manipulation** → via Scikit-learn pipelines & transformers  
- ✅ **Model Training & Cross-Validation** → with `GridSearchCV` and `RandomForest`  
- ✅ **Model Selection** → based on evaluation metrics like ROC AUC  
- ✅ **Scalable Deployment** → via serialized model + Gradio-based real-time API

---

## 📚 Dataset

- [Titanic Survival Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- Cleaned and minimally engineered for structured ML pipelines

---
