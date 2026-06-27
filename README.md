# 🖼️ Image Classification using CNN (CIFAR-10)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)
![Deep Learning](https://img.shields.io/badge/DeepLearning-CNN-red.svg)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen.svg)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow.svg)

---

## 📌 Project Overview

This project is a **Deep Learning-based Image Classification system** built using a **Convolutional Neural Network (CNN)**.

The model is trained on the **CIFAR-10 dataset**, which contains 10 different image categories. The goal is to classify images into their correct classes using deep learning techniques.

This project was developed as part of the **CodeAlpha Artificial Intelligence Internship**.

---

## 🎯 Objective

- Understand and implement CNN architecture  
- Work with image datasets using TensorFlow  
- Perform multi-class image classification  
- Learn deep learning workflow in Google Colab  

---

## 📊 Dataset Information

The **CIFAR-10 dataset** contains:

- ✈️ Airplane  
- 🚗 Automobile  
- 🐦 Bird  
- 🐱 Cat  
- 🦌 Deer  
- 🐶 Dog  
- 🐸 Frog  
- 🐴 Horse  
- 🚢 Ship  
- 🚚 Truck  

Each image is **32x32 pixels (RGB)**.

---

## 🏗️ Model Architecture

The CNN model consists of:

- Conv2D Layer (32 filters, 3x3 kernel)  
- MaxPooling Layer  
- Conv2D Layer (64 filters, 3x3 kernel)  
- MaxPooling Layer  
- Flatten Layer  
- Dense Layer (128 neurons, ReLU)  
- Output Layer (10 classes, Softmax)  

---

## ⚙️ Workflow

1. Load CIFAR-10 dataset  
2. Normalize pixel values (0–1 scaling)  
3. Build CNN model  
4. Train model on training data  
5. Evaluate model on test data  
6. Predict image classes  

---

## 📈 Model Performance

> ⚠️ Note: Accuracy depends on training epochs and tuning.

Example output:
Test Accuracy: 0.10 - 0.60 (depends on training)



## 💻 Example Output
Predicted Class: Cat  
Actual Class: Dog
