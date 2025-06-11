# Multi-Class AdaBoost with Perceptron Weak Learners

## 📌 Overview
Implementation of a multi-class AdaBoost algorithm using perceptron weak learners for handwritten digit recognition on the Digits dataset (scikit-learn). Achieves **92.78% accuracy** with dynamic sample weighting and early stopping.

---

## 🚀 Key Features
- **Custom Multi-Class Perceptron**: One-vs-rest classification with weight updates.
- **AdaBoost Framework**: Combines weak learners into a strong ensemble.
- **Weighted Training**: Focuses on misclassified samples in subsequent iterations.
- **Early Stopping**: Discards weak learners with >50% error.
- **Metrics**: Accuracy, classification report (precision/recall/F1), and confusion matrix.

---

## 📊 Results
| Metric          | Score       |
|-----------------|-------------|
| **Accuracy**    | 92.78%      |
| **Avg F1-Score**| 0.93        |

**Common Misclassifications**:  
- 1 ↔ 8, 3 ↔ 8, 9 ↔ 4 (visually similar digits).

---

## 🛠️ Usage

### Prerequisites
```bash
pip install numpy scikit-learn matplotlib jupyter
