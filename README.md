# Understanding Gradient Descent from Scratch

A hands-on approach to learning gradient descent by building intuition first, then implementing it from scratch in Python.

## 📂 Project Structure

```
Understanding_Gradient_descent_from_scratch/
│
├── 1_intuition_of_gd.ipynb           # Building intuition with manual parameter updates
├── 2_gradient_descent_class.ipynb    # Complete GD implementation as reusable class
└── README.md                         # Project documentation
```
## 🧠 1. Intuition of Gradient Descent

In the **first notebook**, we break down GD in the simplest possible way:
- Start with a **random dataset**.
- Use the equation:

$$y = mx + b$$

- Fix `m` (slope) by **hand/assumption**.
- Focus only on updating `b` (intercept) **manually**.
- Observe how changing `b` step-by-step reduces the error.
- Understand the **direction** and **magnitude** of updates intuitively before diving into formulas.

**Key Concepts Covered:**
- What is gradient descent?
- Why does changing `b` affect the predictions?
- How step size (learning rate) changes convergence speed.
- Visualizing the loss curve.

---

## ⚙️ 2. Gradient Descent Class

In the **second notebook** (`2_gradient_descent_class.ipynb`):
- We take the concepts from the first notebook.
- Implement a **`GradientDescent` class** that:
  - Initializes parameters (`m`, `b`, learning rate, iterations).
  - Calculates gradients automatically.
  - Updates both `m` and `b` simultaneously.
  - Tracks and returns loss over iterations.
- Enables **reusability** and **clean code** for different datasets.

---

## 🔍 Why This Project?

Most tutorials jump straight into the math of GD without explaining *why* it works.  
This project:
- Builds **intuition first**, then moves to **formal implementation**.
- Uses **visuals and step-by-step reasoning**.
- Bridges the gap between **concept** and **code**.

---

## 🚀 Quick Start

```bash
# Clone and navigate
git clone https://github.com/<your-username>/Understanding_Gradient_descent_from_scratch.git
cd Understanding_Gradient_descent_from_scratch

# Install dependencies
pip install numpy matplotlib jupyter

# Run notebooks
jupyter notebook
```

## 🔍 Why This Approach?

Most tutorials jump straight into complex math. This project:
- **Builds intuition first** with visual, step-by-step examples
- **Shows the "why"** before the "how"
- **Bridges concept to code** with clean, reusable implementation

## 🛠️ Requirements

- Python 3
- NumPy (numerical computations)
- Matplotlib (visualizations)
- Jupyter Notebook

## ✨ Author

**Shivam Shukla** - Making ML concepts intuitive and accessible.
