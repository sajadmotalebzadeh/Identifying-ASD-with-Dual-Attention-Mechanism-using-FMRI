# ASD Detection with Dual Attention Mechanism using fMRI

This project implements a **deep learning model** for **Autism Spectrum Disorder (ASD) detection** using **phenotypic fMRI dataset (ABIDE)**.  
The model leverages:
- A **Dual Attention Mechanism** for feature refinement.
- **Residual CNN + BiLSTM** backbone.
- Data preprocessing with **SMOTE** to handle class imbalance.
- Deterministic training for reproducibility.

---

##  Features
-  Preprocessing pipeline with scaling, imputation, and one-hot encoding.
-  SMOTE oversampling to balance ASD vs. Control groups.
-  Dual Attention Layer for better representation learning.
-  Residual Conv1D blocks with dropout & batch norm.
-  Evaluation using **Accuracy, Precision, Recall, F1-score** and confusion matrix.
-  Visualization of training history.
