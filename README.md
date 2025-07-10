# Early Detection of Heart Disease – ML Models from Scratch

This project focuses on predicting heart disease from clinical data by implementing core machine learning models **from scratch in Python**, without relying on high-level libraries like `scikit-learn`. It demonstrates a deep understanding of each model's mathematical foundations, learning algorithms, and performance evaluation.

---

## 🩺 Project Overview

The goal of this project is to build and evaluate classifiers that can identify the presence of heart disease based on patient data such as age, cholesterol, resting blood pressure, chest pain type, and other features.

Rather than using prebuilt ML libraries, all models were implemented manually using core Python and numerical packages like `NumPy`.

---

## 🧠 Models Implemented

- **Naïve Bayes**
- **Perceptron**
- **Fisher’s Linear Discriminant**
- **Artificial Neural Network (ANN)**

Each model includes:
- Manual weight initialization and parameter updates
- Custom training loops
- Numerical stability considerations
- Evaluation metrics and visualization of results

---

## ⚙️ Technologies Used

- **Python**
- **NumPy** – for numerical operations and matrix computations
- **Pandas** – for data loading, preprocessing, and transformation
- **Matplotlib** and **Seaborn** – for visualizing feature distributions, model outputs, and evaluation metrics

---

## 📊 Results

After training and testing on the heart disease dataset:
- Models were compared based on classification accuracy.
- ANN and Naïve Bayes showed the highest predictive performance.
- See the full notebook for implementation details and inline results:
[heart_disease_prediction.ipynb](./heart_disease_prediction.ipynb)

---

📁 Files Included
- `heart_disease_prediction.ipynb` – main notebook with model implementations, analysis, and results  
- `Heart_Disease_dataset.csv` – dataset used
