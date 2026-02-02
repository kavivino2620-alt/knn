# knn
# Implementing and Evaluating K-Nearest Neighbors (KNN) from Scratch

## Project Overview
This project implements the K-Nearest Neighbors (KNN) classification algorithm from scratch using NumPy. The objective is to understand the internal working of KNN by manually computing distances, selecting neighbors, and performing majority voting.

The custom implementation is evaluated and compared with Scikit-learn’s built-in KNN classifier.

---

## Tasks Completed
- Generated a synthetic 2D dataset using `make_blobs`
- Split data into training (70%) and testing (30%)
- Implemented KNN from scratch using NumPy only
- Evaluated performance for K = 3, 5, and 10
- Compared results with Scikit-learn KNN
- Visualized the decision boundary

---

## Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn

---

## How to Run the Project
1. Install required libraries:

---

## Results
The custom KNN implementation achieved accuracy comparable to Scikit-learn’s KNN. The optimal K value was selected based on test accuracy.

---

## Effect of K Value
- Small K values lead to complex decision boundaries (risk of overfitting)
- Large K values smooth decision boundaries (risk of underfitting)
- Optimal K balances bias and variance

---

## Conclusion
The project demonstrates that a NumPy-based implementation of KNN can perform similarly to a standard library implementation, reinforcing understanding of distance-based learning algorithms.

---

