# Linear Regression Projects

This repository showcases two end-to-end linear regression projects: one using **Simple Linear Regression** and the other using **Multiple Linear Regression**. Both projects demonstrate fundamental steps in exploratory data analysis (EDA), model building, evaluation, and visualization using real-world datasets.

---

## 📂 Repository Structure

```
linear-regression/
├── datasets/
│   ├── Fish.csv                  # Dataset for multiple linear regression
│   └── happyscore_income.csv     # Dataset for simple linear regression
│
├── multiple linear regression/
│   ├── fish-mlr.ipynb            # Jupyter Notebook for Fish Market regression
│   └── README.md                 # Project-specific documentation
│
├── simple linear regression/
│   ├── happyincome-slr.ipynb     # Jupyter Notebook for Income vs Happiness regression
│   └── README.md                 # Project-specific documentation
```

---

## 🔍 Projects Overview

### 🟩 Simple Linear Regression

- **Dataset**: `happyscore_income.csv`
- **Goal**: Predict a country's happiness score based on its average income
- **Model**: Single-feature linear regression
- **Output**: Regression line plot, error metrics (MAE, MSE, R²), coefficient interpretation

➡️ Details: [simple linear regression/README.md](simple%20linear%20regression/README.md)

---

### 🟦 Multiple Linear Regression

- **Dataset**: `Fish.csv`
- **Goal**: Predict the weight of a fish based on physical measurements (lengths, height, width)
- **Model**: Multiple linear regression with 5 features
- **Output**: Coefficient table, prediction vs actual plot, evaluation metrics

➡️ Details: [multiple linear regression/README.md](multiple%20linear%20regression/README.md)

---

## 📌 Technologies Used

- Python
- pandas
- matplotlib & seaborn
- scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/linear-regression.git](https://github.com/Vathsan18/linear-regression-income-insurance.git
   cd linear-regression-income-insurance
   ```

2. Open the notebooks:

   - For Simple Linear Regression: `simple linear regression/happyincome-slr.ipynb`
   - For Multiple Linear Regression: `multiple linear regression/fish-mlr.ipynb`

3. Run all cells and follow outputs for insights and evaluations.

---

## 📈 Learning Objectives

- Perform exploratory data analysis (EDA)
- Apply and interpret simple and multiple linear regression
- Evaluate regression model performance using MAE, MSE, and R²
- Visualize regression outputs
