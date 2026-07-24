
---

# 🧠 Alzheimer’s Disease Detection from Handwriting Data

This repository contains our solution for a **Kaggle competition** focused on developing a predictive model capable of distinguishing between **Alzheimer’s Disease (AD) patients and healthy individuals** using **handwriting-based features**.

The project explores the use of data analysis and machine learning techniques to identify patterns in handwriting that may be associated with early signs of Alzheimer’s disease.

---

## 📊 Project Objective

The goal is to build a **classification model** that can accurately predict whether a person has Alzheimer’s disease based on structured handwriting-related data.

This is a **binary classification problem**:

* `1` → Alzheimer’s Disease (AD)
* `0` → Healthy individual

---

## 📁 Repository Structure

```
├── main_code.ipynb        # Main notebook (EDA, preprocessing, modeling)
├── data.csv               # Training dataset
├── test.csv               # Test dataset (for prediction)
├── summary_stats.csv      # Statistical summary of dataset features
├── EDA_report.html        # Exploratory Data Analysis report (interactive HTML)
```

---

## 🔍 Workflow Overview

The notebook (`main_code.ipynb`) includes the full pipeline:

1. **Exploratory Data Analysis (EDA)**

   * Distribution analysis
   * Feature correlation study
   * Outlier detection

2. **Data Preprocessing**

   * Handling missing values
   * Feature scaling and transformation

3. **Feature Engineering**

   * Selection of relevant handwriting-based features

4. **Model Training**

   * Training classification models (e.g., Logistic Regression, Random Forest, etc.)
   * Hyperparameter tuning

5. **Evaluation**

   * Accuracy, precision, recall, and F1-score
   * Cross-validation performance

6. **Prediction**

   * Generating predictions on `test.csv`

---

## 📈 Key Insights

* Handwriting features contain meaningful patterns that help distinguish AD patients from healthy individuals.
* Proper feature engineering significantly improves model performance.
* Tree-based models generally perform better on this dataset.

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Jupyter Notebook

---

## 📌 Results

The final model achieves competitive performance on the validation set and demonstrates the potential of **non-invasive handwriting analysis** for Alzheimer’s detection.

---

## 🚀 How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/alzheimer-handwriting-detection.git
cd alzheimer-handwriting-detection
```

2. Open the notebook:

```bash
jupyter notebook main_code.ipynb
```

3. Run all cells to reproduce the analysis and predictions.

---

## 📚 Context

This project was developed as part of a **Kaggle competition**, aiming to apply machine learning techniques in the field of **medical data analysis and neurodegenerative disease detection**.

---



