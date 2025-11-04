# 🦟 Insect Bite Classification using CNN (DENSENET 121)

A Convolutional Neural Network (CNN)-based system for detecting and classifying **insect bites on human skin images**.  
This project uses **DENSENET 121** architecture trained on a custom dataset to classify the **severity** of bites (Mild, Moderate, Severe).  
Developed using **TensorFlow** and **Google Colab** as part of the **EARIST Extension Research Project**.

---

## 📘 Overview
The system aims to assist in the **early identification and classification** of insect bites based on skin appearance.  
By analyzing redness, inflammation, and lesion texture, the model predicts the severity level to support dermatological assessment and dataset generation.

---

## 🚀 Features
- 🧠 **DENSENET 121 ** deep learning architecture  
- 🧩 Data augmentation for better generalization  
- ⚖️ Class weighting for imbalanced dataset  
- 📊 Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- ☁️ Fully compatible with **Google Colab**  
- 🔍 Synthetic dataset generation for training and testing

---

## 🧠 Model Performance
| Metric | Value |
|--------|--------|
| Accuracy | **0.9129** |
| Precision | **0.9129** |
| Recall | **0.9129** |
| ROC AUC | **0.9660** |
| PR AUC | **0.9670** |

---

## 💻 How to Run the Project

1. **Open in Google Colab**
   ```bash
   https://colab.research.google.com/github/<your-username>/<repo-name>/blob/main/insectbite_model.ipynb
