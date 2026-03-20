# Deep Learning Based Intrusion Detection System (IDS)

This project implements a Deep Learning-based Intrusion Detection System (IDS) using the KDD Cup dataset. The model is designed to classify network traffic as **normal** or **malicious** using a neural network.

---

## 🚀 Run the Project

👉 Open in Google Colab:  
https://colab.research.google.com/drive/1JYrtDgYdDlDwIWfxOxDE5_dzmjB4b_Rw?usp=sharing

---

## 📊 Dataset

- KDD Cup 1999 Intrusion Detection Dataset
- Contains network traffic features and attack labels
- Preprocessed using:
  - One-hot encoding (categorical features)
  - Z-score normalization (numerical features)

---

## ⚙️ Model Details

- Feedforward Neural Network (Keras)
- Layers:
  - Dense (ReLU)
  - Output layer (Sigmoid for binary classification)
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- EarlyStopping used to prevent overfitting

---

## 📈 Results

- High classification accuracy achieved on test dataset (~99%)
- Effective detection of normal vs attack traffic
- Performance evaluated using:
  - Accuracy score
  - Confusion Matrix
  - Classification Report

---

## 📌 Features

- Binary Classification (Normal vs Attack)
- Deep Learning-based approach
- Visualization of training (Accuracy & Loss graphs)
- Confusion Matrix Heatmap

---

## 👨‍💻 Author

**N Sai Mukesh**  
Enrollment No: 23STUCHH010520  

**D Satish**  
Enrollment No: 23STUCHH010519  

---

## 📎 Note

The dataset is accessed directly from this repository and used in the Colab notebook for training and evaluation.

---

## ✅ Submission

- GitHub repository contains code and dataset
- Colab notebook provided for execution
- Model demonstration will be shown in person
