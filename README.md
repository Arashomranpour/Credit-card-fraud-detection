<div align="center">

# 💳 Credit Card Fraud Detection

**Detect fraudulent transactions in a highly unbalanced dataset using under-sampling and logistic regression.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

Fraud is rare, so the data in `creditcard.csv` is **highly unbalanced**. The notebook (`app.ipynb`):

1. Explores the class distribution.
2. **Under-samples** the legitimate transactions to create a balanced training set.
3. Trains a **Logistic Regression** classifier.
4. Reports precision, recall, F1 and accuracy (about **96 %** on the evaluation split).

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/Credit-card-fraud-detection.git
cd Credit-card-fraud-detection
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook app.ipynb
```

Download `creditcard.csv` (Kaggle: *Credit Card Fraud Detection*) and put it next to the notebook.

## 📁 Project Structure

```
.
└── app.ipynb     # EDA, under-sampling, model and evaluation
```

## 🛠️ Tech Stack

`scikit-learn` · `pandas` · `NumPy` · `Matplotlib`
