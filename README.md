# Gradient Descent Visualization & Experiment

This notebook implements and visualizes Gradient Descent optimization across multiple settings. I experiment with learning rates, convergence behavior, and loss landscapes for convex functions. The aim is to understand the algorithmic behavior of first-order optimization at a fundamental level.

## 🧠 Objectives

- Implement vanilla gradient descent from scratch.
- Tune hyperparameters such as step size (`alpha`) and convergence thresholds.
- Visualize convergence paths on 2D loss surfaces.
- Observe divergence and oscillation at extreme learning rates.

## 🧪 Methods

- Defined a quadratic convex function as the optimization target.
- Tracked function value and parameter updates at each iteration.
- Plotted loss vs iteration and vector field trajectories.
- Compared convergence under various learning rate schedules.

## 🔍 Key Takeaways

- Learning rate choice is critical — too large leads to instability or divergence.
- Small learning rates converge reliably but very slowly.
- Visualizing vector fields and loss over time builds deep understanding of descent dynamics.

## 🚀 Technologies

- Python
- NumPy
- Matplotlib
