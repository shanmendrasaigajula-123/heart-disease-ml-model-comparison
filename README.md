# Heart Disease Classification — Machine Learning Model Comparison

## 📌 Overview

This project focuses on building and comparing multiple machine learning classification models for predicting the presence of heart disease.

The main objective was to gain hands-on experience with the complete machine learning workflow, from data preprocessing and feature scaling to model training, evaluation, hyperparameter experimentation, and final model comparison.

Rather than selecting a single algorithm beforehand, multiple classification algorithms were implemented and evaluated on the same dataset.

---

## 🎯 Objective

The objective of this project is to develop a binary classification system that predicts whether a patient has heart disease based on the available features.

The project also aims to determine which machine learning algorithm performs best according to the selected evaluation metrics.

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- Support Vector Machine (SVM)

---

## ⚙️ Machine Learning Workflow

The project follows an end-to-end machine learning workflow:

1. Data loading and inspection
2. Data understanding
3. Data preprocessing
4. Feature and target separation
5. Train-test splitting
6. Feature scaling
7. Model training
8. Model evaluation
9. Hyperparameter experimentation
10. Model comparison
11. Final model selection

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

### Why ROC-AUC?

ROC-AUC was selected as the primary metric for the final model comparison because it evaluates how well a classification model can distinguish between the two classes across different classification thresholds.

The ROC-AUC calculation was corrected to use the models' predicted probability scores or decision scores rather than the final predicted class labels. This provides a more meaningful measure of the model's ability to separate positive and negative classes.

Accuracy, precision, recall, F1-score, and confusion matrices were used as supporting metrics to provide a broader view of model performance.

---

## 🧪 Hyperparameter Experimentation

Hyperparameter experimentation was performed to understand how model parameters affect performance.

### K-Nearest Neighbors

Different values of `k` were tested to determine a suitable number of neighbors.

### Random Forest

Different tree-depth configurations were investigated to understand their effect on model performance and generalization.

---

## 📈 Final Model Comparison

The final ROC-AUC results were:

| Rank | Model | ROC-AUC |
|---:|---|---:|
| 🥇 1 | **Random Forest** | **0.902406** |
| 🥈 2 | AdaBoost | 0.890374 |
| 🥉 3 | Logistic Regression | 0.882353 |
| 4 | KNN | 0.879011 |
| 5 | XGBoost | 0.878342 |
| 6 | SVM | 0.862299 |
| 7 | Decision Tree | 0.626337 |

### 🏆 Final Model

Based on the selected primary metric, **Random Forest achieved the highest ROC-AUC score of 0.902406** and was therefore selected as the best-performing model according to ROC-AUC.

However, XGBoost achieved higher accuracy in the earlier evaluation. This demonstrates that model performance can vary depending on the evaluation metric used.

---

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience in:

- Implementing supervised machine learning algorithms
- Data preprocessing
- Feature scaling
- Binary classification
- Model evaluation
- Hyperparameter experimentation
- ROC-AUC analysis
- Model comparison
- Understanding model generalization
- Selecting a model based on an appropriate evaluation metric

One of the major takeaways from this project was that **model selection should not rely on accuracy alone**. Different evaluation metrics can provide different perspectives on model performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```text
heart-disease-ml-model-comparison/
│
├── README.md
└── Heart_Disease_Classification_ML.ipynb
```

## 🚀 Future Improvements

Some possible improvements for this project include:

More extensive hyperparameter tuning
Cross-validation for model selection
Feature importance analysis
Explainable AI techniques such as SHAP
Model deployment using Flask, FastAPI, or Streamlit

## 👨‍💻 About

This project was developed as a hands-on Machine Learning project to strengthen my practical understanding of model training, evaluation, hyperparameter experimentation, and model selection.

It represents my continued journey toward becoming an AI Engineer and Generative AI Developer.
