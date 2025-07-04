# Multiple Linear Regression on Fish Market Dataset

This project uses the Fish Market dataset to build a multiple linear regression model that predicts the **Weight** of a fish based on various physical measurements.

---

## 📊 Dataset

**Features used**:
- `Length1`, `Length2`, `Length3`: Different measurements of fish length
- `Height`: Height of the fish
- `Width`: Width of the fish  
**Target**:
- `Weight`: Fish weight in grams

---

## 🧪 Steps Performed

1. **Data Import and Cleaning**
   - Removed categorical column `Species`
   - Dropped missing values if any

2. **Train-Test Split**
   - Split dataset into 80% training and 20% testing sets

3. **Model Training**
   - Used `LinearRegression()` from scikit-learn

4. **Model Evaluation**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² score

5. **Visualization**
   - Scatter plot of actual vs predicted weights

---

## 📈 Results

- **Intercept**: -515.3056513384324
- **Coefficients**: Each feature's contribution to predicting `Weight`
- **R² Score**: Indicates how much variance in fish weight is explained
- **MAE/MSE**: Represents average prediction error

---

## 📌 Interpretation

> The model accurately predicts fish weight using physical features like length, height, and width. The closer the predicted values are to actual weights, the better the model performance (as seen in the scatter plot).

---

## 💻 Technologies Used

- Python
- pandas
- seaborn, matplotlib
- scikit-learn

---

## 🧠 Conclusion

This multiple linear regression model provides an effective way to estimate fish weight using physical dimensions. The approach can be extended or improved using polynomial regression or feature scaling if needed.
