# Neural Networks (MLP for MNIST Classification)

This project implements a **Multi-Layer Perceptron (MLP)** neural network from scratch using Python and NumPy to classify handwritten digits from the **MNIST dataset**. The model is trained using **mini-batch stochastic gradient descent with momentum** and evaluated using classification accuracy.

---

## Project Overview
- Implements a fully connected neural network (MLP)
- Trains and evaluates the model on MNIST (digits 0–9)
- Supports multiple activation functions and dropout
- Uses mini-batch SGD with optional momentum
- Designed for multi-class classification

---

## Network Architecture
- Linear layer  
- Tanh / ReLU activation  
- Dropout (optional)  
- Linear layer  
- Softmax output  

---

## Implementation Details
All implementation is done in:
- `neural_networks.py`

Only this file is modified and graded.

---

## Features Implemented
- Linear layer (forward & backward)
- Activation functions:
  - ReLU
  - Tanh
- Dropout (forward & backward)
- Softmax classification
- Mini-batch SGD with momentum
- End-to-end backpropagation

---

## How to Run
```bash
python neural_networks.py
