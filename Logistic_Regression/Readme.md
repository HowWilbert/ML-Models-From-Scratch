# Logistic Regression From Scratch 📉

A complete implementation of **Logistic Regression from scratch using NumPy**, without relying on machine learning libraries like Scikit-Learn for model training.

This project demonstrates the mathematical foundations behind:

- Binary Classification
- Sigmoid Activation Function
- Gradient Descent Optimization
- Cost Function Minimization
- Probability Prediction
- Model Evaluation
- Benchmarking Against Scikit-Learn

---

# 🚀 Project Overview

This repository focuses on implementing Logistic Regression completely from scratch using only:

- NumPy
- Pandas
- Matplotlib

The notebook walks through the entire Machine Learning pipeline:

1. Data Loading
2. Data Preprocessing
3. Train-Test Split
4. Model Building
5. Gradient Descent Optimization
6. Prediction & Classification
7. Model Evaluation
8. Benchmarking with Scikit-Learn
9. Visualization of Results

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
Logistic Regression/
│
├── Logistic_regression_FS.ipynb
├── README.md
└── assets/
    ├── accuracy_comparison.png
    ├── confusion_matrix.png
    ├── roc_curve.png
    └── probability_distribution.png
```

---

# ⚙️ Features Implemented

## ✅ Custom Logistic Regression Class

The model includes:

- Weight Initialization
- Bias Initialization
- Sigmoid Activation Function
- Binary Cross Entropy Cost Function
- Gradient Computation
- Gradient Descent Optimization
- Probability Prediction
- Binary Classification
- Accuracy Evaluation

---

# 📉 Logistic Regression Mathematics

## 🔹 Sigmoid Function

The sigmoid function converts linear outputs into probabilities between 0 and 1.

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

Where:

- \( z = Xw + b \)

---

## 🔹 Cost Function

Binary Cross Entropy Loss:

\[
J(w,b) = -\frac{1}{m}\sum_{i=1}^{m}
\left[
y^{(i)}\log(\hat{y}^{(i)})
+
(1-y^{(i)})\log(1-\hat{y}^{(i)})
\right]
\]

---

## 🔹 Gradient Descent Update Rule

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

# 📊 Dataset Information

| Attribute | Value |
|---|---|
| Dataset Type | Binary Classification |
| Features | Multiple |
| Target Classes | 0 and 1 |
| Problem Type | Logistic Regression |

---

# 🚀 Custom Logistic Regression Performance

| Metric | Value |
|---|---|
| Training Accuracy | **90%+** |
| Testing Accuracy | **90.35%** |
| Learning Rate | `0.001` |
| Iterations | `10000` |

---

# 🤖 Scikit-Learn Benchmark Comparison

| Model | Accuracy |
|---|---|
| Custom Logistic Regression | **0.9035** |
| Scikit-Learn LogisticRegression | **0.9298** |

### 📌 Observation

The custom implementation achieved approximately **97% of Scikit-Learn’s performance**, validating the correctness of:

- Sigmoid Activation
- Gradient Descent Optimization
- Cost Minimization
- Binary Classification Pipeline

---

# 📈 Model Visualizations

## 🔹 Accuracy Comparison

Compares the performance of the custom implementation against Scikit-Learn.

```python
plt.bar(models, scores)
```

---

## 🔹 Confusion Matrix

Visualizes classification performance for both models.

```python
confusion_matrix(y_test, y_pred)
```

---

## 🔹 ROC Curve Comparison

Compares classification capability using Area Under Curve (AUC).

```python
roc_curve(y_test, probabilities)
```

---

## 🔹 Probability Distribution

Displays predicted probability distributions for both models.

```python
plt.hist(probabilities)
```

---

# 📉 Gradient Descent Convergence

The Gradient Descent optimization successfully minimized the Binary Cross Entropy loss over iterations.

## Key Observations

- Stable convergence achieved
- No exploding gradients observed
- Smooth loss reduction
- Efficient parameter optimization

---

# 🧠 Key Learnings

Through this project, the following concepts were implemented completely from scratch:

- Logistic Regression Mathematics
- Sigmoid Activation Function
- Binary Classification
- Gradient Descent Optimization
- Binary Cross Entropy Loss
- Probability-Based Predictions
- Decision Thresholding
- Model Benchmarking Against Scikit-Learn

---

# 🏆 Key Achievements

✅ Built Logistic Regression completely from scratch using NumPy  
✅ Implemented Sigmoid Activation Function manually  
✅ Implemented Binary Cross Entropy Loss from scratch  
✅ Achieved **90%+ classification accuracy**  
✅ Achieved near Scikit-Learn level performance  
✅ Visualized classification metrics and ROC curves  
✅ Built a complete binary classification pipeline  

---

# 🔥 Conclusion

This project demonstrates a complete mathematical and programmatic understanding of Logistic Regression without relying on machine learning frameworks for training.

The custom implementation successfully reproduced the behavior of Scikit-Learn’s `LogisticRegression` model with closely matching performance metrics, validating the correctness of:

- Sigmoid computations
- Probability estimation
- Gradient computations
- Parameter optimization
- Binary classification pipeline

The project also showcases practical experience in:

- Numerical Computing
- Optimization Algorithms
- Machine Learning Fundamentals
- Classification Techniques
- Data Visualization
- Performance Benchmarking

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
cd ML-Models-From-Scratch/Logistic\ Regression
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
Logistic_regression_FS.ipynb
```

---

# 📌 Future Improvements

- Add Regularization (L1/L2)
- Add Multi-Class Logistic Regression
- Add Feature Scaling Module
- Add Mini-Batch Gradient Descent
- Add Stochastic Gradient Descent
- Add Model Serialization
- Add Precision, Recall & F1 Score Metrics

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
