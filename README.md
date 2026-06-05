# Decision Tree Classification with Pruning (UCI Datasets)

## 📖 Overview

This project implements a Decision Tree classifier (ID3-like) from scratch and compares it with Scikit-learn’s implementation. The model is trained and evaluated on well-known UCI datasets including **Car Evaluation** and **Nursery**.

The project focuses on:

* Handling categorical data
* Training decision trees
* Model evaluation (accuracy & confusion matrix)
* Model optimization using **Reduced Error Pruning**
* Hyperparameter tuning using **Grid Search**

---

## 📂 Datasets

The following datasets are used:

* Car Evaluation Dataset (UCI)
* Nursery Dataset (UCI)

All datasets contain categorical features, making them suitable for decision tree learning.

---

## ⚙️ Features

### ✅ Data Preprocessing

* Label Encoding for categorical features
* Train/Test splitting with multiple ratios (80/20, 60/40, 40/60)

### 🌳 Model Implementation

* Custom ID3-like Decision Tree implementation
* Scikit-learn DecisionTreeClassifier for comparison

### 📊 Evaluation

* Accuracy calculation
* Confusion Matrix analysis

### ✂️ Pruning

* Reduced Error Pruning implemented for model simplification
* Helps reduce overfitting

### 🔍 Hyperparameter Tuning

* GridSearchCV with 5-fold cross-validation
* Optimization of parameters like:

  * max_depth
  * min_samples_split

---

## 🧪 Experiments

* Comparison between custom and sklearn models
* Performance evaluation under different train/test splits
* Impact of pruning on model performance

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install numpy pandas scikit-learn
```

2. Run the notebook:

```bash
jupyter notebook
```

3. Open:

```
ML_DTC.ipynb
```

---

## 📈 Results

* Decision Trees perform well on categorical datasets
* Pruning improves generalization
* Grid Search helps find optimal tree depth

---

## 🧠 Key Learnings

* Understanding ID3 algorithm fundamentals
* Handling categorical data in ML pipelines
* Trade-off between overfitting and model complexity
* Practical use of pruning techniques

---

## 📌 Future Improvements

* Add visualization of decision trees
* Implement other algorithms (C4.5, CART)
* Use more datasets for benchmarking

---

## 👨‍💻 Author

Alireza Pazooki

