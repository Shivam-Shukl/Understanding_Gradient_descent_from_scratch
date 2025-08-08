# Understanding Gradient Descent from Scratch

This repository aims to **intuitively explain Gradient Descent (GD)** and then implement it from scratch in Python.  
It consists of two Jupyter notebooks:
1. **Building an intuition for Gradient Descent** with a simple dataset.
2. **Implementing Gradient Descent as a reusable class** based on the earlier intuition.

---

## 📂 Project Structure

```
Understanding_Gradient_descent_from_scratch/
│
├── 1_intuition_of_gd.ipynb           # Step-by-step intuition-building for GD
├── 2_gradient_descent_class.ipynb    # GD implemented as a reusable Python class
└── README.md                         # Project documentation
```

---

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

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/Understanding_Gradient_descent_from_scratch.git
cd Understanding_Gradient_descent_from_scratch
```

### 2. Install Dependencies
```bash
pip install numpy matplotlib jupyter
```

### 3. Run the Notebooks
Open Jupyter Notebook or Jupyter Lab:
```bash
jupyter notebook
```

Then explore:
1. `1_intuition_of_gd.ipynb`
2. `2_gradient_descent_class.ipynb`

---

## 📊 Example Outputs

- **Loss curve** showing convergence over iterations.
- **Parameter updates** (`m` and `b`) converging to optimal values.
- **Visual fit line** over dataset points.

### Sample Visualization
The notebooks include interactive plots showing:
- How the regression line changes as parameters are updated
- Cost function decreasing over iterations
- Comparison between initial random line and final fitted line

---

## 🛠️ Technologies Used

- **Python 3** – Core programming language
- **NumPy** – For numerical computations and array operations
- **Matplotlib** – For creating visualizations and plots
- **Jupyter Notebook** – For interactive exploration and documentation

---

## 📈 Learning Outcomes

After completing this project, you will understand:

1. **Conceptual Understanding:**
   - How gradient descent works at an intuitive level
   - Why we need optimization algorithms in machine learning
   - The relationship between cost functions and parameter updates

2. **Technical Skills:**
   - Implementing gradient descent from scratch
   - Creating reusable Python classes for ML algorithms
   - Visualizing optimization processes
   - Understanding hyperparameter effects (learning rate, iterations)

3. **Practical Applications:**
   - Linear regression using gradient descent
   - Parameter initialization strategies
   - Convergence criteria and stopping conditions

---

## 🎯 Key Features

- **Step-by-step approach**: From basic intuition to complete implementation
- **Visual learning**: Rich plots and animations to understand the process
- **Clean code structure**: Well-organized, commented, and reusable code
- **Educational focus**: Emphasis on understanding rather than just implementation
- **Interactive notebooks**: Hands-on learning with immediate feedback

---

## 📚 Mathematica
