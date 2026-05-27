# Bluetab Fraud Detection (Machine Learning)

A predictive Machine Learning model designed to detect fraudulent transactions in highly imbalanced financial datasets.

## 🎯 Objective
The objective of this project was to tackle a classic, real-world data science problem: fraud detection. Since fraudulent transactions represent a tiny fraction of total transactions, the primary challenge was to correctly identify fraud without overwhelming the system with false positives, requiring advanced data sampling and classification techniques.

## 🚀 What is Achieved
- **Handling Imbalanced Data:** Successfully implemented SMOTE (Synthetic Minority Over-sampling Technique) to synthetically balance the dataset, preventing the model from simply predicting the majority class (non-fraud) every time.
- **Algorithm Evaluation:** Trained and evaluated multiple classification algorithms, including Logistic Regression, Random Forests, and Gradient Boosting (XGBoost/LightGBM).
- **Feature Engineering:** Analyzed feature importance and performed dimensionality reduction to optimize model training speed and accuracy.
- **Business Metrics:** Focused on optimizing the F1-Score and Recall rather than pure Accuracy, ensuring that actual fraud cases were caught effectively, which is critical for financial institutions.

## 🛠️ Tools & Technologies
- **Language:** Python
- **Libraries:** `scikit-learn`, `pandas`, `numpy`, `imbalanced-learn` (SMOTE).
- **Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook

## 📖 Usage Guide

### Prerequisites
You will need Python 3 and the standard data science stack.

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn jupyter
```

### Exploring the Project
1. Clone the repository.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the main analysis notebook to view the step-by-step pipeline: Exploratory Data Analysis (EDA), SMOTE application, model training, and the final confusion matrices.
