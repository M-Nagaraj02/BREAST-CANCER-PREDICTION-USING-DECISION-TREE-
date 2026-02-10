# 🩺 Breast Cancer Prediction Using Decision Tree

## Overview

This project predicts **breast cancer** using the **Decision Tree** algorithm, a supervised machine learning method. The model classifies tumors as **malignant (0)** or **benign (1)** using the **Wisconsin Breast Cancer Dataset**.

---

## Dataset

* Wisconsin Breast Cancer Dataset (scikit-learn)
* 30 numerical features
* Target labels: 0 (Malignant), 1 (Benign)

```python
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()
```

---

## Methodology

* Algorithm: Decision Tree Classifier
* Data split: 80% training, 20% testing
* Basic preprocessing and feature handling

---

## Results

* Achieved **91% accuracy** on test data
* Model evaluated using accuracy score, confusion matrix, and classification report

**Model Confusion Matrix Heatmap :**

<img width="640" height="547" alt="image" src="https://github.com/user-attachments/assets/b4654ae2-7723-4b51-b319-bb602950687f" />


---

## Author

**Nagaraj M**
GitHub: [https://github.com/M-Nagaraj02](https://github.com/M-Nagaraj02)



