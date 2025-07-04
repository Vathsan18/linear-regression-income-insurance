# Simple Linear Regression on Income vs Happiness

This project performs a simple linear regression analysis using the "Income Happiness" dataset to explore the relationship between a country's average income and its happiness score.

---

## 📊 Dataset

**Fields used**:
- `avg_income`: Average income of each country (independent variable)
- `happyScore`: Happiness score of each country (dependent variable)

---

## 🧪 Steps Performed

1. **Import and Clean Data**
   - Loaded CSV dataset using pandas
   - Checked for null values and basic statistics

2. **Train-Test Split**
   - Used 80% of data for training and 20% for testing

3. **Model Fitting**
   - Applied `LinearRegression()` from `sklearn.linear_model`

4. **Model Evaluation**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² score

5. **Visualization**
   - Plotted regression line over scatter plot of income vs happiness

---

## 📈 Results

- **Intercept**: 4.507458808084176
- **Coefficient**: 0.00013889578601260978
- **R² Score**: Indicates how well avg_income explains variations in happiness
- **MAE/MSE**: Measures average prediction error

---

## 📌 Interpretation

> An increase in average income is positively associated with an increase in the happiness score. However, the strength of this relationship should be evaluated by the R² score.

---

## 💻 Technologies Used

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## 🧠 Conclusion

This simple linear regression model demonstrates how a single economic factor like income can be linked to national happiness, though additional features may improve prediction accuracy.

