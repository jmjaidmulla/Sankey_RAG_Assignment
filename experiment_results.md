# Experiment Results – CS229 ML Implementation

Author: Jaid Mulla  
Course Reference: Stanford CS229 (Andrew Ng)

---

## 1. Linear Regression Results

### Dataset
Synthetic regression dataset:
y = 4 + 3x + noise

### Parameters Learned

#### Gradient Descent:
Theta ≈ [4.0, 3.0]

#### Normal Equation:
Theta ≈ [4.0, 3.0]

### Mean Squared Error (MSE)
MSE ≈ Low value (close to 1 depending on noise)

### Observations
- Both Gradient Descent and Normal Equation converge to similar parameters.
- Cost function is convex → guaranteed global minimum.
- Vectorization improves computational speed significantly.

---

## 2. Stochastic Gradient Descent (SGD)

### Observations
- Converges faster initially.
- Oscillates near global minimum.
- Suitable for large datasets.

---

## 3. Logistic Regression Results

### Dataset
Synthetic binary classification dataset (2 features).

### Final Accuracy
Accuracy ≈ 90–98% (depending on random seed)

### Classification Report
- Precision: High
- Recall: High
- F1-score: Balanced

### Observations
- Sigmoid correctly models probability.
- Cross-entropy loss ensures proper gradient behavior.
- Decision boundary is linear.

---

## 4. Generative Model – Gaussian Discriminant Analysis (GDA)

### Estimated Parameters
- φ (class prior)
- μ₀ and μ₁ (class means)
- Σ (shared covariance)

### Observations
- GDA models p(x|y) directly.
- Logistic Regression models p(y|x).
- When Gaussian assumption holds, GDA performs competitively.

---

## Final Conclusion

This project demonstrates:

✔ Mathematical understanding  
✔ Optimization techniques  
✔ Discriminative vs Generative models  
✔ Vectorized implementations  
✔ Professional ML experimentation  

Aligned with Stanford CS229 standards.