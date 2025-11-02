# 🐾 Cat vs Dog Image Classification using SVM

This project demonstrates an image classification pipeline that distinguishes **cats** from **dogs** using a **Support Vector Machine (SVM)** with **Principal Component Analysis (PCA)** for dimensionality reduction.  
It showcases how traditional machine learning techniques can perform effectively on image data when combined with proper preprocessing.

---

## 📘 Project Overview

The goal of this project is to classify pet images into two categories — *Cat* or *Dog* — using classical ML algorithms instead of deep learning models.  
Images are resized, normalized, flattened, and transformed using PCA before being trained on an SVM classifier.

---

## 🎯 Objectives
- Preprocess image data efficiently for classical ML.
- Apply PCA to reduce high-dimensional feature space.
- Train and evaluate an SVM model for binary classification.
- Visualize sample predictions.

---

## 📂 Dataset

**Dataset:** [Microsoft Cats vs Dogs Dataset (787 MB)](https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip)  
**Source:** Microsoft Research / Kaggle

> ⚠️ **Note:** The dataset exceeds GitHub’s 25 MB limit and is **not included** in this repository.  
> Please download it manually using the above link or let the notebook handle it automatically through the provided `wget` command.

---

## ⚙️ Technologies Used
- **Python 3**
- **TensorFlow** – image loading & preprocessing  
- **NumPy** – numerical operations  
- **Matplotlib** – visualization  
- **scikit-learn** – SVM, PCA, evaluation metrics

---

## 🧾 Project Workflow
1. **Data Loading** – Download and extract dataset  
2. **Preprocessing** – Resize, normalize, and flatten images  
3. **Feature Reduction** – Apply PCA for dimensionality reduction  
4. **Model Training** – Train an SVM classifier with a linear kernel  
5. **Evaluation** – Generate accuracy and classification report  
6. **Visualization** – Display sample predictions

---

## 📊 Results
- The SVM model achieves strong accuracy on unseen test data.  
- PCA significantly improves computation speed and memory efficiency.  
- Visual outputs show clear distinction between cat and dog images.

---



