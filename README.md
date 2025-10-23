# Gradient Descent with Momentum (Python + NumPy)

This project demonstrates how **gradient descent with momentum** works in optimizing a simple quadratic function.  
The example uses NumPy for computation and Matplotlib for visualization, showing how momentum helps accelerate convergence and reduce oscillation.

---

## 🚀 Overview
Gradient descent is an optimization algorithm that adjusts parameters to minimize a given objective function.  
By adding **momentum**, the algorithm builds up velocity in directions with consistent gradients, allowing faster convergence.

In this example, we minimize:
\[
f(x) = x^2
\]
with its derivative:
\[
f'(x) = 2x
\]

---

## 🧮 Implementation Details
- Objective function: `f(x) = x²`
- Derivative: `f'(x) = 2x`
- Gradient descent parameters:
  - Iterations: 30  
  - Step size (learning rate): 0.1  
  - Momentum: 0.3  

---

## 🧰 Requirements
Install dependencies (if running locally):

```bash
pip install numpy matplotlib
▶️ Run the Code
---
python gradient_descent_momentum.py
---

📊 Output
>0 f([0.466]) = 0.217
>1 f([0.343]) = 0.118
...
## 🔗 Links
- [**View Notebook on Google Colab**](https://colab.research.google.com/drive/1ngFY94Hm5vMemtPXnZp_qSYOHULZjdiO?usp=sharing)
