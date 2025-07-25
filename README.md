# 🧬 Breast Cancer Prediction using Logistic Regression

Hey there! 👋  
This is a simple yet powerful machine learning project where we predict whether a tumor is **malignant** or **benign** using **Logistic Regression**.

The goal is to support early breast cancer detection using machine learning techniques. As a B.Tech student specializing in Artificial Intelligence & Machine Learning, I built this as part of my hands-on learning journey.

---

## 📚 Project Overview

- **Algorithm**: Logistic Regression  
- **Dataset**: Breast Cancer Dataset (CSV format)  
- **Language**: Python  
- **Tools Used**: Google Colab, Pandas, NumPy, Matplotlib, scikit-learn  

---

## 📌 Problem Statement

Breast cancer is one of the most common types of cancer among women worldwide. Early detection is critical for effective treatment.  
In this project, we use machine learning to build a binary classification model that predicts if a tumor is **malignant** or **benign** based on cell features.

---

## 📂 Dataset Details

- Columns include measurements like:
  - Radius
  - Texture
  - Smoothness
  - Compactness
  - Symmetry, etc.
- The **target variable** (`y`) is:
  - `1`: Malignant
  - `0`: Benign

> Make sure the dataset file is named **`breast_cancer.csv`** and is uploaded in your Google Colab session.

---

## 🚀 How to Run this Project on Google Colab

1. **Open this notebook in Google Colab**  
   > Upload the `.ipynb` file or create a new one.

2. **Upload your CSV file**  
   Add the dataset to Colab using:
   ```python
   from google.colab import files
   uploaded = files.upload()
