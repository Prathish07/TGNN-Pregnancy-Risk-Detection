# Explainable Temporal Graph Neural Networks for High-Risk Pregnancy Detection

## Overview

Maternal health complications remain a significant global health challenge. Early prediction of high-risk pregnancies enables timely medical intervention and reduces maternal mortality.

This project proposes an **Explainable Temporal Graph Neural Network (TGNN)** framework that models temporal health records and relational dependencies between patients to predict pregnancy risk levels.

Unlike traditional machine learning models, the TGNN architecture captures complex interactions between clinical features over time while providing interpretable predictions.

---

## Problem Statement

Traditional models such as Logistic Regression and Random Forest struggle to capture:

- Temporal dependencies in patient health data
- Relationships between patients with similar health profiles
- Interpretability for clinical decision-making

This project addresses these limitations using **Temporal Graph Neural Networks combined with explainability techniques**.

---

## Key Features

- Temporal Graph Neural Network for risk prediction
- Patient similarity graph construction
- Feature normalization and preprocessing
- Comparative evaluation with traditional ML models
- Explainability using **GNNExplainer** and **SHAP**

---

## Model Architecture

The system constructs a temporal graph where:

- **Nodes:** Patients
- **Features:** Health indicators such as blood pressure, glucose, BMI
- **Edges:** Similarity relationships between patients

The TGNN learns embeddings that capture both temporal and relational dependencies for accurate risk prediction.

---

## Algorithms Compared

The TGNN model is evaluated against:

### Supervised Models
- Logistic Regression
- Decision Tree
- Random Forest

### Unsupervised Models
- K-Means
- Agglomerative Clustering
- DBSCAN

### Ensemble Methods
- Bagging
- Boosting
- Stacking

---

## Explainability

To ensure transparency in predictions:

- **GNNExplainer** identifies important nodes and edges
- **SHAP** highlights influential health features

This enables clinicians to understand why a pregnancy is classified as high risk.

---

## Tech Stack

- Python
- PyTorch
- PyTorch Geometric
- Scikit-learn
- SHAP
- Pandas
- NumPy
- Matplotlib

---

## Workflow

1. Data preprocessing
2. Graph construction
3. Temporal feature modeling
4. TGNN model training
5. Evaluation with ML baselines
6. Explainability analysis

---

## Results

The TGNN model demonstrates improved performance in:

- Precision
- Recall
- F1-score

while maintaining interpretability through explainability techniques.

---

## Future Work

- Integration with hospital EHR systems
- Real-time pregnancy monitoring
- Larger clinical datasets
- Deployment as a clinical decision support system

---

## Author

Prathish A   
