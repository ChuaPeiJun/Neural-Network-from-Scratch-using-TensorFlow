# Neural-Network-from-Scratch-using-TensorFlow

## 🧠 Project Overview

In this assignment, we are given a dataset that does not represent any specific domain, it is a general dataset used for training and classification purposes. The goal is to train a neural network to classify the data correctly using a custom-built **gradient descent optimization algorithm**.


## ⚙️ Implementation Details

The notebook demonstrates the following concepts:

1. **Data Loading & Preprocessing**
   - Import and clean the dataset.
   - Split the dataset into training, validation, and testing sets.
   - Normalize or standardize input features.

2. **Model Architecture**
   - Define a simple feedforward neural network using low-level TensorFlow operations.
   - Use **ReLU** and **Sigmoid** activation functions.

3. **Training (Gradient Descent)**
   - Implement forward propagation manually.
   - Compute the **loss function** (Mean Squared Error or Cross Entropy).
   - Perform **backward propagation** to calculate gradients.
   - Update the weights and biases using gradient descent.

4. **Model Evaluation**
   - Evaluate the trained model using validation and testing datasets.
   - Measure accuracy, loss, and other relevant metrics.
   - Visualize the learning curve (loss vs. epochs).


## 📊 Key Learning Outcomes

By completing this assignment, we learned how to:
- Implement a neural network from scratch using **TensorFlow low-level APIs**.
- Understand the mathematical intuition behind **gradient descent**.
- Manage **forward and backward propagation** manually.
- Evaluate and interpret model performance.
