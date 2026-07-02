# Task 1 – Image Classification using CNN (CIFAR-10)

## Overview

This project was completed as part of the AI Internship.

The objective was to build and compare two Convolutional Neural Network (CNN) models for image classification on the CIFAR-10 dataset.

- **Part A:** Baseline CNN
- **Part B:** Improved CNN with architectural enhancements

---

## Dataset

**Dataset:** CIFAR-10

- 60,000 RGB images
- Image size: 32 × 32
- 10 classes
- 50,000 training images
- 10,000 testing images

Classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Part A – Baseline CNN

Implemented a traditional CNN consisting of:

- Convolution Layers
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Adam Optimizer

Evaluation included:

- Training and Validation Curves
- Classification Report
- Confusion Matrix

---

## Part B – Improved CNN

The improved model introduced:

- Additional Convolutional Layers
- Batch Normalization
- Dropout Regularization
- Improved CNN Architecture
- Adam Optimizer

The same train-validation split and number of epochs were maintained to ensure a fair comparison.

---

## Evaluation Metrics

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Classification Report
- Confusion Matrix
- Training Time

---

## Repository Structure

```
Task1_PartA_BaselineCNN.ipynb
Task1_PartB_ImprovedCNN.ipynb
README.md
```

---

## Author

Poorva Singh
