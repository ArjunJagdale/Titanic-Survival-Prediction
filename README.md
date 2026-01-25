# 🎯 End-to-End ML Project: Titanic Survival Prediction - IBM SKILLSBUILD SUMMER INTERNSHIP PROJECT

This project builds an **end-to-end machine learning pipeline** to predict passenger survival on the Titanic using classical ML techniques and best practices.
The focus is on **clean preprocessing, reliable evaluation, and deployable inference**, rather than leaderboard hacking.
The model is trained using a **Random Forest classifier** with a full scikit-learn pipeline and deployed using a **Gradio web interface** for interactive predictions.

## My internship completion certificate - 
![image](https://github.com/user-attachments/assets/4a718209-491a-42cb-908d-62a6ad398ecf)

## 📚 Dataset
* [Titanic Survival Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
* Source: Titanic dataset (Kaggle / DataScienceDojo)
* Records: 891 passengers
* Target: `Survived` (binary classification)
* Selected features:

  * `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## Approach

* Performed **data cleaning and exploratory analysis**
* Used **stratified train–test split** to preserve class distribution
* Built a **ColumnTransformer-based preprocessing pipeline**:

  * Numerical: median imputation + standard scaling
  * Categorical: mode imputation + one-hot encoding
* Trained a **Random Forest classifier** with balanced class weights
* Evaluated using **classification metrics and ROC-AUC**
* Deployed the trained model with **Gradio** for real-time inference

---

## Results

### Classification Report

```
                 precision    recall  f1-score   support

Did not survive       0.86      0.86      0.86       110
Survived              0.78      0.78      0.78        68

accuracy                                   0.83       178
macro avg             0.82      0.82      0.82       178
weighted avg          0.83      0.83      0.83       178
```

* **Accuracy:** 83%
* **Macro F1-score:** 0.82 (balanced performance across classes)
* **ROC-AUC:** 0.83 (strong class separability)

These results indicate a **robust and well-balanced classifier**, avoiding overfitting and biased predictions.

---

## Model Deployment

An interactive **Gradio web interface** is provided where users can input passenger details and receive:

* Survival prediction
* Survival probability score

This demonstrates the complete ML lifecycle from training to deployment.

---

## Tech Stack

* Python
* Pandas, NumPy
* scikit-learn
* Matplotlib
* Gradio
* Joblib

---

## How to Run

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. The Gradio interface will launch at the end for live predictions

---

## Notes

* The project emphasizes **ML fundamentals, evaluation rigor, and clean pipelines**
* Results are realistic and reproducible, suitable for academic and entry-level industry use
