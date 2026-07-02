# Task 1: Image Classification using Convolutional Neural Networks (CNN)

## Overview

This project was completed as part of the **iNeuBytes AI Internship**.

The objective of this task was to build and compare two Convolutional Neural Network (CNN) models for image classification using the **CIFAR-10** dataset.

The project consists of two parts:

- **Part A:** Baseline CNN
- **Part B:** Customized CNN

The customized CNN introduces several architectural improvements to enhance image classification performance while maintaining the same training setup for a fair comparison.

---

## Dataset

The project uses the **CIFAR-10** dataset.

### Dataset Details

- **Total Images:** 60,000
- **Training Images:** 50,000
- **Testing Images:** 10,000
- **Image Size:** 32 × 32 RGB
- **Number of Classes:** 10

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

Before training, all images were normalized by scaling pixel values to the range **0–1**.

---

## Files Included

- `Task1_PartA_BaselineCNN.ipynb`
- `Task1_PartB_CustomizedCNN.ipynb`
- `README.md`
- `requirements.txt`

---

## Part A – Baseline CNN

The baseline CNN was implemented using:

- Convolutional Layers
- ReLU Activation
- Max Pooling
- Flatten Layer
- Fully Connected Dense Layers
- Dropout
- Adam Optimizer

The model was trained for **12 epochs** and evaluated using standard classification metrics.

---

## Part B – Customized CNN

The customized CNN improves the baseline architecture by introducing:

- Additional Convolutional Layers
- Batch Normalization
- Data Augmentation
- Dropout Regularization
- Learning Rate Scheduling
- Adam Optimizer

The same training, validation, and testing split was maintained to ensure a fair comparison with the baseline model.

---

## Results

| Metric | Baseline CNN | Customized CNN |
|---------|-------------:|---------------:|
| Test Accuracy | **72.14%** | **84.94%** |
| Training Time | 138.94 sec | 335.43 sec |
| Epochs | 12 | 12 |
| Parameters | 5,870,666 | 5,874,250 |
| Accuracy Improvement | **+12.80 percentage points** |

The customized CNN successfully exceeded the internship target of improving the baseline model by at least **3 percentage points**, achieving an improvement of **12.80 percentage points**.

---

## Key Improvements

The customized CNN achieved better performance by incorporating:

- Additional convolutional layers for better feature extraction.
- Batch Normalization to stabilize and accelerate training.
- Data Augmentation to improve generalization.
- Dropout Regularization to reduce overfitting.
- Learning Rate Scheduling for improved optimization.

These enhancements significantly improved the model's ability to classify images, resulting in higher test accuracy.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Hugging Face Datasets

---

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Open the notebooks in Google Colab or Jupyter Notebook.
2. Install the required dependencies.
3. Run all notebook cells sequentially.
4. The notebooks will:
   - Load and preprocess the dataset
   - Train the CNN model
   - Evaluate model performance
   - Generate training and validation graphs
   - Display confusion matrices
   - Compare the baseline and customized CNN models

---

## Learning Outcomes

This project provided hands-on experience with:

- Image preprocessing
- Convolutional Neural Networks (CNNs)
- Batch Normalization
- Dropout Regularization
- Data Augmentation
- Hyperparameter tuning
- Model evaluation
- Performance comparison

---

## Author

**Poorva Singh**

AI Internship – Task 1
