# Decision Tree Splitting Visualized

This repository explains how Decision Trees split data using:

- Gini Impurity
- Entropy (Information Gain)

All implementations are done from scratch before comparing with sklearn.

---

## Gini Impurity

Gini = 1 - Σ p_i²

Measures class purity after a split.

---

## Entropy

Entropy = -Σ p_i log₂(p_i)

Measures information uncertainty.

---

## What This Repo Shows

- How trees evaluate every possible threshold
- Why certain splits are selected
- Visual explanation of impurity reduction
- Comparison between manual and sklearn implementation

---

## Key Insight

Decision trees don’t “understand” data.

They brute-force evaluate impurity reduction across features and thresholds.

---

## Technologies

- Python
- NumPy
- Matplotlib
- scikit-learn
