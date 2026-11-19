# 🎓 Student Performance Classification (GDGoC Weekly Class)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Syamil37/student-performance-ml-colab/blob/main/student_performance_classification.ipynb)

Welcome to the **Student Performance Classification** project, created for the Google Developer Groups on Campus (GDGoC) AI/ML Weekly Class. This project provides a complete, hands-on introduction to building end-to-end Machine Learning classification models using Python.

---

## 🚀 Project Overview

In this notebook, students learn how to predict whether a student will **pass** or **fail** based on key academic and behavioral indicators. The project covers the entire Machine Learning workflow:
1. **Synthetic Data Generation**: Simulating realistic student performance metrics using `pandas` and `numpy`.
2. **Exploratory Data Analysis (EDA)**: Visualizing feature correlations and distributions using `matplotlib` and `seaborn`.
3. **Data Preprocessing & Scaling**: Preparing features and applying `StandardScaler`.
4. **Model Training**: Training two popular classification algorithms:
   - **Logistic Regression** (Linear model)
   - **Random Forest Classifier** (Ensemble tree-based model)
5. **Model Evaluation & Comparison**: Evaluating performance using Accuracy, Classification Reports, Confusion Matrices, and Feature Importance analysis.

---

## 📂 Notebook Structure

The Jupyter Notebook (`student_performance_classification.ipynb`) is structured into the following step-by-step sections:
- **Step 1**: Import Libraries & Setup
- **Step 2**: Generate Synthetic Student Dataset
- **Step 3**: Exploratory Data Analysis (EDA)
- **Step 4**: Data Preprocessing & Train-Test Split
- **Step 5**: Model 1 - Logistic Regression
- **Step 6**: Model 2 - Random Forest Classifier
- **Step 7**: Feature Importance Analysis
- **Step 8**: Model Comparison & Conclusion

---

## 🛠️ How to Run

### Option 1: Run in Google Colab (Recommended)
Click the badge at the top of this README or click the link below to open and run the notebook directly in your browser with zero setup:
👉 [Open in Google Colab](https://colab.research.google.com/github/gdgoc/student-performance-ml-colab/blob/main/student_performance_classification.ipynb)

### Option 2: Run Locally
1. Clone or download this repository.
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook student_performance_classification.ipynb
   ```

---

## 🤝 Community & Support
Created with ❤️ for the GDGoC AI/ML Weekly Class mentees. Feel free to fork, experiment, and build upon this project!
