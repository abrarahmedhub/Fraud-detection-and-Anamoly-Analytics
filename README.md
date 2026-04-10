
## 📌 Fraud Detection using Machine Learning & Autoencoders

### 🔍 Overview

This project focuses on detecting fraudulent credit card transactions using anomaly detection techniques and deep learning models. The goal is to accurately identify whether a given transaction is fraudulent while minimizing false negatives.

This implementation is **inspired by an existing project**, but significantly enhanced with additional features, performance improvements, and better usability.

---

## 🎯 Key Features & Improvements

* ✅ Rebuilt and improved core ML models from scratch
* ✅ Enhanced for better usability and readability
* ✅ Added new features for deeper analysis and model comparison
* ✅ Optimized performance for faster training and evaluation
* ✅ Fixed bugs and improved overall code stability
* ✅ Improved data visualization (graphs, confusion matrices, insights)

---

## 📊 Dataset

The dataset contains anonymized credit card transactions made over two days in 2013 by European cardholders, including both normal and fraudulent transactions.
 dataset url = https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

* Highly imbalanced dataset
* Fraud detection treated as an **anomaly detection problem**

---

## 🧠 Models Implemented

### 🔹 Machine Learning Models

* Isolation Forest
* Local Outlier Factor (LOF)
* One-Class Support Vector Machine (One-Class SVM)

### 🔹 Deep Learning Model

* Autoencoder (trained on normal transactions only)

---

## ⚙️ Project Structure

* `Fraud_detection.ipynb` → ML-based anomaly detection
* `Fraud_Autoencoder.ipynb` → Autoencoder-based fraud detection

---

## 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy Score
* Precision, Recall, F1-Score
* Confusion Matrix

### 🏆 Results

* **Best ML Model:** One-Class SVM

  * Recall: **84%**
  * Low false negatives (important for fraud detection)

* **Autoencoder Model:**

  * Recall: **83%**
  * Effective in capturing anomalous transactions using reconstruction error

---

## 🚀 Key Learnings

* Handling **imbalanced datasets** in real-world problems
* Importance of **recall in fraud detection systems**
* Applying **unsupervised learning techniques** for anomaly detection
* Building and evaluating **deep learning models (Autoencoders)**

---

## 🛠️ Technologies Used

* Python 3.9
* TensorFlow
* Scikit-learn
* Pandas, NumPy
* Matplotlib, Seaborn

---

## ▶️ How to Run

You can run this project using:

* Jupyter Notebook
* Google Colab

---

## 🙌 Acknowledgment

This project is **inspired by Ania Kubów (Aniass)** and other online learning resources.
Significant modifications, feature additions, UI/UX improvements, bug fixes, and performance optimizations have been implemented to enhance the original concept.

---

## 💡 Why This Project Stands Out

This project goes beyond a basic tutorial implementation by:

* Demonstrating strong understanding of anomaly detection
* Showcasing ability to improve and extend existing work
* Applying both machine learning and deep learning approaches

---

## 🔗 References

* Anomaly Detection Algorithms
* Credit Card Fraud Detection using Autoencoders
* Complete Guide to Anomaly Detection

---
