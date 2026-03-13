# Lung Cancer Histopathological Image Classification using CNN

This project implements a Deep Learning model to classify lung cancer histopathological images into three categories: **Adenocarcinoma**, **Squamous Cell Carcinoma**, and **Benign tissue**.

## 📌 Project Overview
The goal is to assist in the automated detection of lung cancer types using Convolutional Neural Networks (CNN). Early and accurate classification is critical for determining the correct treatment path for patients.

## 📊 Dataset
The dataset consists of 15,000 color images (processed down to a smaller subset for this specific notebook) across 3 classes:
* **Bengin**
* **Adenocarcinoma**
* **Squamous Cell Carcinoma**

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Image Processing:** OpenCV (cv2)

## 🏗️ Model Architecture
The CNN model follows this structure:
1. **Convolutional Layers:** To extract spatial features from the lung tissue images.
2. **MaxPooling:** To reduce dimensionality and computational load.
3. **Flatten Layer:** To convert 2D features into a 1D vector.
4. **Dense Layers:** Fully connected layers for final classification.
5. **Softmax Output:** Provides probabilities for the three classes.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Ranju-09/Lung-Cancer-Detection.git](https://github.com/YOUR_USERNAME/Lung-Cancer-Detection.git)
