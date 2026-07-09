# 📊 Cross-Validation Techniques Comparison in Machine Learning

## 📌 Project Overview

Model evaluation is one of the most important steps in Machine Learning. Instead of relying on a single train-test split, this project compares multiple cross-validation techniques using the Iris dataset and Logistic Regression.

The goal is to understand how different validation strategies affect model performance, stability, and computational cost.

---

## 🎯 Objectives

- Compare popular cross-validation techniques.
- Analyze model accuracy and stability.
- Measure execution time.
- Visualize performance using professional graphs.

---

## 🛠️ Cross-Validation Methods Compared

- Train/Test Split
- KFold
- StratifiedKFold
- ShuffleSplit
- RepeatedKFold
- LeaveOneOut

---

## 🤖 Machine Learning Model

- Logistic Regression

---

## 📂 Dataset

- Iris Dataset
- Number of Samples: 150
- Number of Features: 4
- Number of Classes: 3

---

## 📊 Evaluation Metrics

- Mean Accuracy
- Standard Deviation
- Minimum Accuracy
- Maximum Accuracy
- Execution Time

---

## 📈 Visualizations

- Mean Accuracy Comparison
- Standard Deviation Comparison
- Execution Time Comparison
- Fold Accuracy Comparison
- Accuracy Distribution (Box Plot)

---

## 🏆 Key Findings

- StratifiedKFold achieved the highest average accuracy.
- RepeatedKFold provided stable performance.
- LeaveOneOut produced competitive results but required the highest execution time.
- ShuffleSplit performed well while using random sampling.
- KFold worked effectively but does not preserve class distribution.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Project Structure

Cross Validation Techniques Comparison/

├── dataset/

├── images/

├── cross_validation_comparison.ipynb

├── README.md

├── requirements.txt


---

## 🚀 Future Improvements

- Compare additional machine learning algorithms.
- Apply GridSearchCV and RandomizedSearchCV.
- Test on larger and imbalanced datasets.
- Include Precision, Recall, and F1-score comparisons.

---

## ⭐ Conclusion

Cross-validation provides a more reliable estimate of model performance than a single train-test split. This project demonstrates how different validation strategies impact accuracy, stability, and computational efficiency.
