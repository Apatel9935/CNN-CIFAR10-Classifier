# 🧠 CNN CIFAR-10 Image Classifier 

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to perform multi-class image classification on the CIFAR-10 dataset. The model is designed to learn spatial features from images and classify them into 10 categories.

---

## 🚀 Features
- Built a custom CNN architecture (Conv → ReLU → MaxPool layers)
- Applied data preprocessing and normalization using torchvision
- Implemented efficient data loading with PyTorch DataLoader
- Trained using Adam optimizer and CrossEntropyLoss
- Achieved ~76% accuracy on test dataset

---

## 🗂️ Dataset
- **CIFAR-10**: 60,000 color images (32x32) across 10 classes:
  - Airplane, Car, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck
- Dataset is automatically downloaded using torchvision

---

## 🏗️ Model Architecture
The CNN model consists of:
- 3 Convolutional layers (32 → 64 → 128 filters)
- ReLU activation after each convolution
- MaxPooling for spatial downsampling
- Fully connected layers for classification

---

## ⚙️ Tech Stack
- Python
- PyTorch
- Torchvision

---

## 📊 Results
- **Test Accuracy:** ~76%
- Training loss decreases consistently across epochs, indicating proper learning

---
