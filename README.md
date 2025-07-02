# Backpropagation_from_scratch

This repository contains a minimal and intuitive implementation of the backpropagation algorithm from scratch using Python, without relying on high-level deep learning libraries like TensorFlow or PyTorch.

📌 What’s Inside?

    -Manual construction of a simple feedforward neural network
    -Forward pass computation using basic linear algebra
    -Complete derivative calculations for backpropagation
    -Implementation of gradient descent for weight updates
    -Code annotated for educational clarity

✅ Goals

This notebook was created with the aim of:

    -Deepening understanding of how neural networks learn

    -Demystifying how gradients are computed and propagated backward

    -Providing a learning resource for beginners and students in machine learning

📓 Notebook Overview

    Data & Parameters Initialization: Inputs, weights, and targets are manually defined
    Forward Pass: Computes intermediate values like z, a, and loss
    Backward Pass: Derivatives of loss w.r.t. each parameter calculated manually
                   Chain rule applied step by step
                   Weight Update: Simple update using learning rate and computed gradients

🧮 Concepts Covered
    
    -Matrix multiplication in neural nets
    -Sigmoid activation function and its derivative
    -Mean squared error (MSE) loss function
    -Partial derivatives and the chain rule
    -Vectorized implementation using NumPy

📦 Requirements

    -Python 3.x
    -NumPy
    -Jupyter Notebook or any IDE

🚀 Getting Started
To try it out:
git clone https://github.com/nimxrah/Backpropagation_from_scratch.git
cd backprop-from-scratch
jupyter notebook
Open backpropagation_from_scratch.ipynb and run through the cells to explore how backpropagation works under the hood!

📚 Educational Use
This code is written for didactic purposes. Perfect for:
    -Students learning ML/DL basics
    -Those preparing for interviews or exams
    -Anyone wanting to understand how neural nets learn

🤝 Contributing
Contributions are welcome! Feel free to improve explanations, add new visualizations, or generalize the architecture.


