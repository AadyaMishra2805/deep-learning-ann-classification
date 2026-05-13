# Deep Learning ANN Classification Project

## Overview
This project implements an Artificial Neural Network (ANN) using TensorFlow for Breast Cancer classification. The project covers neural network fundamentals, preprocessing, ANN training, evaluation, visualization, and comparison with traditional Machine Learning models.

---

# Objectives
- Understand deep learning fundamentals
- Learn neural network concepts
- Build an ANN using TensorFlow
- Train and evaluate the model
- Visualize loss and accuracy
- Compare ANN with Logistic Regression

---

# Dataset
Dataset used:
- Breast Cancer Dataset (`breast-cancer.csv`)

Target column:
- `diagnosis`

Classification:
- Malignant (M)
- Benign (B)

---

# Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# Project Workflow

## 1. Data Preprocessing
- Load dataset
- Handle features and labels
- Label encoding
- Train-test split
- Feature scaling

## 2. ANN Model Building
- Dense hidden layers
- ReLU activation
- Sigmoid output layer

## 3. Model Training
- Forward propagation
- Backpropagation
- Loss optimization

## 4. Evaluation
- Accuracy score
- Loss analysis
- Validation metrics

## 5. Visualization
- Accuracy vs Epochs
- Loss vs Epochs

## 6. Traditional ML Comparison
- Logistic Regression

---

# ANN Architecture

Input Layer:
- Dataset features

Hidden Layers:
- Dense(16, ReLU)
- Dense(8, ReLU)

Output Layer:
- Dense(1, Sigmoid)

---

# Results
- High classification accuracy achieved
- Loss decreased across epochs
- ANN performed competitively with traditional ML models

---

# Key Deep Learning Concepts Covered
- Neural Networks
- Perceptrons
- Weights and Bias
- Activation Functions
- Forward Propagation
- Backpropagation
- Gradient Descent
- Loss Functions

---

# Visualizations
The notebook includes:
- Training loss graph
- Validation loss graph
- Training accuracy graph
- Validation accuracy graph

---

# Future Improvements
- Add Dropout layers
- Hyperparameter tuning
- Try deeper neural networks
- Use additional datasets
- Compare with Random Forest and SVM

---

# Conclusion
This project demonstrates the implementation of an ANN for classification using TensorFlow and highlights important deep learning concepts along with practical experimentation and performance analysis.
