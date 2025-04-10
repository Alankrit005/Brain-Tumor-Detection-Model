# Brain-Tumor-Detection-Model
A deep learning model for detecting brain tumors from MRI images using Convolutional Neural Networks (CNNs). 
# 🧠 Brain Tumor Detection Model

This repository contains a trained deep learning model for detecting brain tumors from medical imaging data. The model is built using [TensorFlow/Keras] and saved in `.h5` format (`BTM.h5`).

## 📂 Files

- `BTM.h5` – The pre-trained brain tumor detection model.

## 🚀 Model Overview

This model was developed as part of a research/academic project to classify brain MRI images into tumor vs. no-tumor categories. It is trained on a labeled dataset of MRI scans using a Convolutional Neural Network (CNN).

## 🧠 Model Architecture

- Input Layer: 128x128 grayscale MRI images  
- Conv2D → ReLU → MaxPooling  
- Dropout for regularization  
- Fully Connected Dense Layers  
- Sigmoid / Softmax activation for binary/multi-class classification

## 📊 Dataset

The model was trained on a publicly available dataset of brain MRI images (e.g., from [Kaggle](https://www.kaggle.com)) labeled with tumor presence. All images were preprocessed (resized, normalized) before training.
