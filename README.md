# Neural Network from Scratch using NumPy

This repository contains a fully implemented neural network from scratch using **NumPy**.  
It includes **layer classes, activation functions, loss functions, and optimizers**.  
Regularization techniques like **L2 regularization** and **dropout** are also implemented to improve generalization.

## Features
- Implemented fully in **NumPy**, without using deep learning libraries.
- Supports **multiple layers** and **activation functions**.
- Includes different **optimizers**:
  - **Adam**
  - **RMSprop**
  - **Adagrad**
  - **Gradient Descent with Momentum**
- Implements **regularization techniques**:
  - **L2 regularization** to prevent overfitting.
  - **Dropout** to improve generalization.

## Results
- **Adam optimizer (no regularization)** → **Training:** 94.5%, **Testing:** 83.2% _(Overfitting)_  
- **Added L2 regularization** → **Testing accuracy improved to 89.3%**  
- **Added Dropout** → **Training:** 69%, **Testing:** 73% _(Better generalization)_   

