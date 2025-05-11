# Churn_Prediction
Predict whether a customer will churn based on service usage data and customer attributes.

---

## 📊 Customer Churn Prediction

This project focuses on predicting customer churn using various machine learning models. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering (including PCA), and the application of classification models such as SVM, Decision Tree, Random Forest, and Neural Networks.

---

### 📁 Project Structure

* `Churn_Prediction.ipynb`: Jupyter notebook containing the full analysis and model evaluation.
* `README.md`: Project overview and instructions.
* `data/`: Directory where the raw dataset is stored.

---

### 🔍 Problem Statement

**Goal**: Predict whether a customer will churn based on service usage data and customer attributes.

Churn is a major issue in subscription-based businesses. Accurately identifying potential churners allows companies to proactively engage with at-risk customers.

---

### ⚙️ Workflow Overview

1. **Exploratory Data Analysis (EDA)**:

   * Visualized customer behavior and service usage.
   * Analyzed correlations and distributions.

2. **Feature Engineering**:

   * Applied **Principal Component Analysis (PCA)** to reduce dimensionality of categorical variables.
   * Created a `combined_cat_pca` feature from encoded categorical data.

3. **Modeling & Evaluation**:

   * Trained and compared models:

     * **Support Vector Machine (SVM)** with polynomial kernel
     * **Decision Tree**
     * **Random Forest**
     * **Neural Network(MLP Classifier)**
   * Evaluated using **accuracy score** and other relevant metrics.

---

### 📈 Results

The SVM and MLP Classifier achieved an accuracy of approximately **80%** (replace with actual), and performance comparisons between models were discussed in the notebook.

---

### 🧪 Requirements

Install dependencies using:

```bash
pip install pandas scikit-learn matplotlib seaborn
```


---

### 🧠 Future Improvements

* Hyperparameter tuning with GridSearchCV
* Deployment with a Flask API
* Real-time prediction dashboard

---

