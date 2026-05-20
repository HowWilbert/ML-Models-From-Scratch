# Linear Regression From Scratch 📈

A complete implementation of **Linear Regression from scratch using NumPy**, without relying on machine learning libraries like Scikit-Learn for model training.

This project demonstrates the core mathematics behind:

- Simple Linear Regression
- Multiple Linear Regression
- Gradient Descent Optimization
- Cost Function Minimization
- Model Evaluation
- Performance Benchmarking

---

# 🚀 Project Overview

This repository focuses on implementing Linear Regression completely from scratch using only:

- NumPy
- Pandas
- Matplotlib

The notebook walks through the entire Machine Learning pipeline:

1. Data Loading
2. Data Preprocessing
3. Model Building
4. Gradient Descent Optimization
5. Predictions
6. Performance Evaluation
7. Benchmarking with Scikit-Learn
8. Visualization of Results

---

# 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Python | Programming Language |
| NumPy | Numerical Computation |
| Pandas | Data Handling |
| Matplotlib | Data Visualization |
| Scikit-Learn | Benchmark Comparison |

---

# 📂 Repository Structure

```bash
Linear Regression/
│
├── Linear Regression_FS.ipynb
├── salary_data.csv
├── cardekho_imputated.csv
├── README.md
└── assets/
    ├── regression_fit.png
    ├── dataset_distribution.png
    └── cost_reduction.png
```

---

# ⚙️ Features Implemented

## ✅ Custom Linear Regression Class

The model includes:

- Weight Initialization
- Bias Initialization
- Forward Propagation
- Cost Calculation
- Gradient Computation
- Gradient Descent Updates
- Prediction Function
- R² Score Evaluation

---

# 📉 Gradient Descent Optimization

The model minimizes the Mean Squared Error (MSE) cost function using Gradient Descent.

## Cost Function

\[
J(w,b) = \frac{1}{2m}\sum_{i=1}^{m}(y^{(i)} - \hat{y}^{(i)})^2
\]

## Gradient Descent Update Rule

\[
w := w - \alpha \frac{\partial J}{\partial w}
\]

\[
b := b - \alpha \frac{\partial J}{\partial b}
\]

Where:

- \( \alpha \) = Learning Rate
- \( m \) = Number of Training Examples

---

# 📊 Performance Benchmark & Results

# 🔹 Simple Linear Regression Results

## Dataset Information

| Attribute | Value |
|---|---|
| Dataset | Salary Dataset |
| Records | 30 |
| Features | 1 |
| Target Variable | Salary |

---

## 🚀 Custom Linear Regression Performance

| Metric | Value |
|---|---|
| Training R² Score | **0.9137** |
| Testing R² Score | **0.9265** |
| Learning Rate | `0.0005` |
| Iterations | `4000` |
| Final Cost | `60,485,113.93` |

---

## 🤖 Scikit-Learn Comparison

| Model | R² Score |
|---|---|
| Custom Linear Regression | **0.9265** |
| Scikit-Learn LinearRegression | **0.9517** |

### 📌 Observation

The custom implementation achieved approximately **97.3% of Scikit-Learn’s performance**, demonstrating that the model successfully replicates industrial-grade Linear Regression behavior using only NumPy.

---

# 📊 Multiple Linear Regression Results

## Dataset Information

| Attribute | Value |
|---|---|
| Dataset | CarDekho Dataset |
| Records | 15,000+ |
| Features | 15 |
| Problem Type | Multiple Linear Regression |

---

## 🚀 Custom Multiple Linear Regression Performance

| Metric | Value |
|---|---|
| Training R² Score | **0.6204** |
| Testing R² Score | **0.6627** |
| Final Cost | `307,859,784,387.85` |

---

## 🤖 Scikit-Learn Benchmark Comparison

| Model | R² Score |
|---|---|
| Custom Multiple Linear Regression | **0.6627** |
| Scikit-Learn LinearRegression | **0.6645** |

### 📌 Observation

The custom implementation achieved approximately **99.7% parity with Scikit-Learn**, validating the correctness of the Gradient Descent optimization and matrix-based parameter learning.

---

# 📈 Model Visualizations

## 🔹 Regression Fit Visualization

Shows the regression line fitted on the salary dataset.

![Regression Fit](<img width="578" height="413" alt="image" src="https://github.com/user-attachments/assets/2764c9da-67f8-4f45-aa6b-a285f5101cfe" />
)

---

## 🔹 Dataset Distribution

Visual representation of salary variation with experience.

![Dataset Distribution](<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/d05a6972-6471-4691-8d88-ff5df6322a2b" />
)

---

## 🔹 Cost Reduction Curve

Demonstrates successful Gradient Descent convergence.

![Cost Reduction](<img width="554" height="455" alt="image" src="https://github.com/user-attachments/assets/3e9c129b-fcac-4932-a8ef-e7581df3d45f" />
)

---

# 📉 Cost Function Convergence

The Gradient Descent optimization successfully minimized the cost function over iterations, showing stable convergence behavior.

## Key Observations

- Rapid cost reduction during initial iterations
- Smooth convergence afterward
- No divergence observed during training
- Stable learning achieved using optimized learning rate

---

# 🧠 Key Learnings

Through this project, the following concepts were implemented completely from scratch:

- Gradient Descent Optimization
- Cost Function Minimization
- Weight & Bias Updates
- Matrix-Based Multiple Linear Regression
- Feature Handling
- Performance Evaluation
- Model Benchmarking Against Scikit-Learn

---

# 🏆 Key Achievements

✅ Built Linear Regression completely from scratch using NumPy  
✅ Achieved **97%+ performance parity** with Scikit-Learn on Simple Linear Regression  
✅ Achieved **99.7% parity** with Scikit-Learn on Multiple Linear Regression  
✅ Successfully trained on **15,000+ records with 15 features**  
✅ Implemented custom Gradient Descent optimization  
✅ Visualized convergence and prediction performance  
✅ Built both Simple & Multiple Linear Regression pipelines  

---

# 🔥 Conclusion

This project demonstrates a complete mathematical and programmatic understanding of Linear Regression without relying on machine learning frameworks for training.

The custom implementation successfully reproduced the behavior of Scikit-Learn’s `LinearRegression` model with extremely close performance metrics, validating the correctness of:

- Gradient computations
- Parameter optimization
- Cost minimization
- Prediction pipeline

The project also showcases practical experience in:

- Numerical Computing
- Optimization Algorithms
- Machine Learning Fundamentals
- Data Visualization
- Performance Benchmarking
- Model Evaluation

Overall, this repository highlights the ability to implement Machine Learning algorithms from first principles while achieving near-production-level performance.

---

# ▶️ How to Run

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/HowWilbert/ML-Models-From-Scratch.git
```

---

## 2️⃣ Navigate to the Project

```bash
cd ML-Models-From-Scratch/Linear\ Regression
```

---

## 3️⃣ Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 4️⃣ Run the Notebook

```bash
jupyter notebook
```

Open:

```bash
Linear Regression_FS.ipynb
```

---

# 📌 Future Improvements

- Add Regularization (L1/L2)
- Add Polynomial Regression
- Add Feature Scaling Module
- Add Mini-Batch Gradient Descent
- Add Stochastic Gradient Descent
- Create Modular Python Package
- Add Model Serialization

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve the implementation or add more ML algorithms from scratch:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

# ⭐ Support

If you found this project useful:

- Star the repository ⭐
- Share it with others 🚀
- Follow for more ML-from-scratch projects 📚

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

## Ansh Bire

B.Tech Smart Manufacturing  
PDPM IIITDM Jabalpur  
Machine Learning Enthusiast 🚀
