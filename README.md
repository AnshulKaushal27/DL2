# Activation Functions and Their Derivatives Visualization

This project demonstrates the implementation and visualization of commonly used **activation functions in deep learning** along with their **derivatives**.

The program generates **100 random input values between -10000 and 10000**, applies different activation functions, computes their derivatives, and visualizes the results using plots.

---

# Activation Functions Implemented

The following activation functions are implemented in this project:

1. Sigmoid
2. Tanh
3. ReLU (Rectified Linear Unit)
4. Leaky ReLU
5. Softplus
6. ELU (Exponential Linear Unit)

Each function also includes its corresponding **derivative**, which is essential for training neural networks using **backpropagation**.

---

# Why Activation Functions are Important

Activation functions introduce **non-linearity** into neural networks, allowing them to learn complex patterns and relationships in data.

Without activation functions, neural networks would behave like simple **linear models**, limiting their ability to solve complex problems such as image recognition or natural language processing.

---

# Activation Functions Overview

### 1. Sigmoid
- Output range: **0 to 1**
- Commonly used in binary classification

### 2. Tanh
- Output range: **-1 to 1**
- Zero-centered compared to sigmoid

### 3. ReLU
- Output: **max(0, x)**
- Most widely used activation in deep learning

### 4. Leaky ReLU
- Variant of ReLU that avoids the **dying ReLU problem**

### 5. Softplus
- Smooth approximation of ReLU

### 6. ELU
- Helps improve learning by allowing negative outputs

---

# Program Workflow

1. Generate **100 random input values** between **-10000 and 10000**
2. Sort values for smoother plotting
3. Apply activation functions
4. Compute derivatives
5. Plot results using **Matplotlib**

Two graphs are produced:

- Activation Functions
- Derivatives of Activation Functions

---

# Technologies Used

- Python
- NumPy
- Matplotlib

---

# Example Output

The program produces two plots:

- **Activation Functions Plot**
- **Derivatives Plot**

These graphs help analyze how each activation function behaves and how its derivative affects learning during backpropagation.

---

# How to Run

Install required libraries:

```bash
pip install numpy matplotlib
