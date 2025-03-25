# Gradient Descent Experiment: Visualization and Analysis of Optimization Dynamics

## Overview
This project is an in-depth exploration of gradient descent, a foundational optimization algorithm. I implemented and visualized the gradient descent process on convex functions, focusing on how hyperparameters—especially the learning rate—affect convergence. The work is both theoretical and experimental, revealing the delicate interplay between optimization dynamics and algorithmic performance.

## Mathematical Framework
For a differentiable function \(f(\theta)\), gradient descent updates the parameters as:
\[
\theta^{(t+1)} = \theta^{(t)} - \alpha \nabla f(\theta^{(t)}),
\]
where \(\alpha\) is the learning rate. I particularly focused on quadratic functions:
\[
f(\theta) = \frac{1}{2}\theta^T A \theta - b^T \theta,
\]
which offer an analytical gradient \(\nabla f(\theta) = A \theta - b\). This setup provided a clear mathematical foundation to study convergence behavior.

## Implementation & Experimentation
- **Algorithm Implementation:** I developed the gradient descent algorithm from scratch in Python.
- **Visualization:** I plotted loss curves, parameter trajectories, and vector fields to illustrate the optimization process.
- **Parameter Tuning:** Various learning rates were tested, revealing critical trade-offs between convergence speed and stability.
- **Analysis:** The experiments highlight the importance of step-size selection and how it influences the descent path in high-dimensional spaces.

## Usage
- **Prerequisites:** Python, NumPy, Matplotlib.
- **Run the Notebook:** Open `Gradient_Descent_Experiment.ipynb` in your preferred environment.
- **Customization:** Experiment with different convex functions and learning rate schedules to further understand optimization dynamics.

---
