# Task 1: Image Classification using Convolutional Neural Networks (CNN)

## Overview

This project was completed as part of the **iNeuBytes AI Internship**.

The objective of this task was to design, implement, and compare two Convolutional Neural Network (CNN) models for image classification using the **CIFAR-10** dataset.

The project consists of two parts:

- **Part A:** Traditional/Baseline CNN
- **Part B:** Customized CNN with architectural improvements

The customized CNN incorporates several deep learning techniques to improve classification performance while maintaining the same training configuration for a fair comparison.

---

# Dataset

The project uses the **CIFAR-10** dataset, a widely used benchmark dataset for image classification.

### Dataset Details

- Total Images: **60,000**
- Training Images: **50,000**
- Testing Images: **10,000**
- Image Size: **32 × 32 RGB**
- Number of Classes: **10**

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

Images were normalized by scaling pixel values between **0 and 1** before training.

---

# Project Structure

```
Task1/
│
├── Task1_PartA_BaselineCNN.ipynb
├── Task1_PartB_ImprovedCNN.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── baseline_architecture.png
│   ├── improved_architecture.png
│   ├── baseline_training_curves.png
│   ├── improved_training_curves.png
│   ├── baseline_confusion_matrix.png
│   └── improved_confusion_matrix.png
│
└── report/
    └── Task1_Report.pdf
```

---

# Part A – Baseline CNN

The baseline model implements a traditional CNN architecture consisting of:

- Convolutional Layers
- ReLU Activation
- Max Pooling
- Flatten Layer
- Fully Connected Dense Layers
- Dropout
- Adam Optimizer

The model was trained for **12 epochs** using the CIFAR-10 dataset.

Evaluation included:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Confusion Matrix
- Classification Report

---

# Part B – Customized CNN

The customized CNN was designed to improve the baseline model by introducing several architectural enhancements.

### Improvements Implemented

- Additional Convolutional Layers
- Batch Normalization
- Data Augmentation
- Dropout Regularization
- Optimized CNN Architecture
- Adam Optimizer
- Learning Rate Scheduling

To ensure a fair comparison, the following settings remained unchanged:

- Same training dataset
- Same validation dataset
- Same testing dataset
- Same random seed
- Same batch size
- Same number of training epochs (12)

---

# Results

| Metric | Baseline CNN | Customized CNN |
|---------|-------------:|---------------:|
| Test Accuracy | **72.14%** | **84.94%** |
| Training Time | 138.94 sec | 335.43 sec |
| Epochs | 12 | 12 |
| Parameters | 5,870,666 | 5,874,250 |
| Accuracy Improvement | — | **+12.80 percentage points** |

The customized CNN exceeded the internship target of improving the baseline accuracy by at least **3 percentage points**, achieving an improvement of **12.80 percentage points**.

---

# Key Enhancements

The customized CNN achieved better performance due to the following improvements:

- **Additional Convolutional Layers** for richer feature extraction.
- **Batch Normalization** to stabilize training and improve convergence.
- **Data Augmentation** to improve model generalization by exposing the network to transformed images.
- **Dropout Regularization** to reduce overfitting.
- **Learning Rate Scheduling** to optimize training performance.
- **Optimizer Tuning** using the Adam optimizer.

These improvements enabled the model to learn more robust image representations, resulting in significantly higher classification accuracy.

---

# Performance Evaluation

The models were evaluated using:

- Test Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- Training Time

Training and validation accuracy/loss curves were also generated to analyze the learning behavior of both models.

---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Hugging Face Datasets

---

# Installation

Clone the repository:

```bash
git clone <repository-link>
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

# How to Run

1. Open the notebooks in Google Colab or Jupyter Notebook.
2. Install the required dependencies.
3. Run all cells sequentially.
4. The notebooks will:
   - Load the dataset
   - Preprocess the images
   - Train the CNN model
   - Evaluate performance
   - Generate training curves
   - Generate confusion matrices
   - Display the final comparison between Part A and Part B

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Image preprocessing
- Convolutional Neural Networks
- Feature extraction
- Batch Normalization
- Dropout Regularization
- Data Augmentation
- Hyperparameter tuning
- Model evaluation
- Performance comparison

---

# Author

**Poorva Singh**

AI Internship Project – Task 1
