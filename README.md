# Simple Linear Regression - Salary Prediction

This repository contains a machine learning workflow implementing **Simple Linear Regression** to predict an employee's salary based on their years of experience using Python and `scikit-learn`.

---

## 📌 Project Overview & Pipeline

The project follows a standard end-to-end Machine Learning pipeline:

1. **Data Collection**: Loading dataset containing work experience and salary details.
2. **Data Cleaning & Preparation**: Handling missing values, checking duplicate records, and dropping unnecessary columns.
3. **Exploratory Data Analysis (EDA)**: Visualizing feature relationships using scatter plots.
4. **Data Splitting**: Partitioning features ($X$) and target ($y$) into Training and Testing sets.
5. **Model Building & Training**: Fitting a `LinearRegression` model from `scikit-learn`.
6. **Model Evaluation & Testing**: Predicting outcomes on unseen test data.

---

## 🛠️ Tech Stack & Dependencies

* **Python 3.x**
* **Pandas** (Data manipulation and analysis)
* **NumPy** (Numerical operations and array reshaping)
* **Matplotlib** (Data visualization)
* **Scikit-Learn** (Model building and train-test splitting)

To install all required packages:

```bash
pip install pandas numpy matplotlib scikit-learn
