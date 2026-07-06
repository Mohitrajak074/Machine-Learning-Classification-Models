# 🩺 Breast Cancer Classification using Logistic Regression & Decision Tree

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Task](https://img.shields.io/badge/AI%20%26%20ML%20Internship-Task%204-blue)

## 📌 Overview

This project is part of my **Artificial Intelligence & Machine Learning Internship (Task 4)**.

The objective of this project is to build and evaluate a **Binary Classification Model** for predicting whether a tumor is **Benign** or **Malignant** using the **Breast Cancer Wisconsin Dataset**.

The project includes complete data preprocessing, visualization, model training, evaluation, and comparison using industry-standard machine learning techniques.

---

# 🎯 Project Objectives

- Load and explore the Breast Cancer Wisconsin Dataset
- Perform Exploratory Data Analysis (EDA)
- Preprocess and scale the dataset
- Train a Logistic Regression model
- Evaluate model performance using multiple classification metrics
- Visualize ROC Curve and Precision-Recall Curve
- Compare Logistic Regression with Decision Tree Classifier
- Identify the best-performing classification model

---

# 📂 Dataset

**Dataset Used**

Breast Cancer Wisconsin Dataset (Scikit-Learn)

### Dataset Features

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry
- Mean Fractal Dimension
- And many more...

### Target Classes

| Value | Meaning |
|-------|---------|
| 0 | Malignant |
| 1 | Benign |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# ⚙️ Machine Learning Workflow

## Step 1
Import Required Libraries

## Step 2
Load Breast Cancer Dataset

## Step 3
Explore Dataset

- Dataset Preview
- Dataset Information
- Statistical Summary
- Missing Values

## Step 4
Exploratory Data Analysis

- Target Distribution
- Correlation Heatmap

## Step 5
Data Preprocessing

- Feature Selection
- Train-Test Split
- Feature Scaling using StandardScaler

## Step 6
Model Training

### Logistic Regression

A Logistic Regression model was trained to perform binary classification.

### Decision Tree Classifier

A Decision Tree model was also trained to compare classification performance.

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Precision-Recall Curve

---

# 📈 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score | AUC |
|---------------------|----------|-----------|---------|----------|------|
| Logistic Regression |0.99737962659679 |  0.98    |0.95   |  0.96| 43 |
| Decision Tree       |0.9473684210526315 |0.97    | 0.99  | 0.98 |  71|

---

# 📸 Project Screenshots

## Dataset Preview

<img width="1533" height="340" alt="image" src="https://github.com/user-attachments/assets/bed721e7-3f35-4ddb-82ee-f4b9e55b83f7" />

---

## Target Distribution

<img width="823" height="650" alt="image" src="https://github.com/user-attachments/assets/63828f35-7dc6-4786-8844-b2a57707135f" />

---

## Correlation Heatmap

<img width="920" height="796" alt="image" src="https://github.com/user-attachments/assets/59814a8d-8359-485a-8c5d-6d3ccaa049a7" />

---

## Confusion Matrix (Logistic Regression)

<img width="432" height="400" alt="image" src="https://github.com/user-attachments/assets/f75769a4-4ecf-412c-824e-ff7b53980b61" />

---

## ROC Curve

![ROC](screenshots/roc_curve.png)

---

## Precision-Recall Curve

![PR Curve](screenshots/precision_recall_curve.png)

---

## Feature Importance

![Feature Importance](screenshots/feature_importance.png)

---

## Accuracy Comparison

![Accuracy Comparison](screenshots/accuracy_comparison.png)

---

## ROC Comparison

![ROC Comparison](screenshots/roc_comparison.png)

---

## Model Comparison

![Comparison](screenshots/model_comparison.png)

---

# 📁 Project Structure

```
Breast-Cancer-Prediction-using-Logistic-Regression

│── task4_logistic_regression.ipynb
│── README.md
│── report.pdf
│── requirements.txt
│── LICENSE
│
├── screenshots
│      ├── dataset_preview.png
│      ├── target_distribution.png
│      ├── heatmap.png
│      ├── confusion_matrix_lr.png
│      ├── roc_curve.png
│      ├── precision_recall_curve.png
│      ├── feature_importance.png
│      ├── accuracy_comparison.png
│      ├── roc_comparison.png
│      └── model_comparison.png
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction-using-Logistic-Regression.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 💡 Key Learning Outcomes

✔ Binary Classification

✔ Logistic Regression

✔ Decision Tree Classification

✔ Data Preprocessing

✔ Feature Scaling

✔ Classification Metrics

✔ ROC & AUC Analysis

✔ Precision-Recall Analysis

✔ Model Comparison

✔ Machine Learning Workflow

---

# 🔮 Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Support Vector Machine (SVM)
- Hyperparameter Tuning
- Cross Validation
- Feature Selection
- PCA for Dimensionality Reduction
- Streamlit Web App Deployment

---

# 👨‍💻 Author

**Mohit Rajak**

🎓 B.Tech – Computer Science & Engineering

🤖 Artificial Intelligence & Machine Learning Intern

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates me to build more Machine Learning and AI projects.
