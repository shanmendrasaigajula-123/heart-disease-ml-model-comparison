# Heart Disease Classification — Machine Learning Model Comparison

## 📌 Overview

This project focuses on building and comparing multiple machine learning
classification models for predicting the presence of heart disease.

Rather than relying on a single algorithm, I implemented several supervised
learning algorithms and evaluated their performance using multiple evaluation
metrics.

The main goal of this project was to gain practical experience with the
complete machine learning workflow and understand how different algorithms
perform on the same classification problem.

---

## 🎯 Objective

The objective is to develop a binary classification model that can predict
whether a patient is likely to have heart disease based on the available
features in the dataset.

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

1. Data loading
2. Data inspection and understanding
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

ROC-AUC was selected as the primary metric for the final model comparison
because it evaluates how well a classifier distinguishes between the two
classes across different classification thresholds.

Unlike accuracy, which evaluates predictions at a particular threshold,
ROC-AUC provides a broader view of the model's ability to separate positive
and negative classes.

Accuracy, precision, recall, F1-score and confusion matrices were also used
as supporting metrics to understand the models from different perspectives.

---

## 🔍 Hyperparameter Experimentation

Hyperparameter experimentation was performed to understand how model
parameters affect performance.

For KNN, different values of `k` were evaluated to identify a suitable
number of neighbors.

For Random Forest, different tree depths were investigated to understand
their effect on model performance and generalization.

---

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience in:

- Implementing supervised machine learning algorithms
- Preparing and preprocessing datasets
- Applying feature scaling
- Comparing multiple classification algorithms
- Evaluating models using multiple metrics
- Understanding hyperparameters
- Investigating model generalization
- Identifying potential overfitting
- Selecting a model based on evaluation results

---

## 📈 Results

| Model | ROC-AUC |
|------|--------:|
| XGBoost | 0.87 |
| SVM | 0.86 |
| Random Forest | 0.90 |
| AdaBoost | 0.89 |
| Logistic Regression | 0.88 |
| KNN | 0.87 |
| Decision Tree | 0.64 |


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

## 📁 Project Structure

```text
heart-disease-ml-model-comparison/
│
├── README.md
└── heart-disease-classification.ipynb
