# AI_ML_Internship-Task3_Linear_Regression.ipynb

## 📌 Objective
Implement and understand **simple and multiple linear regression** using Python.

## 🛠 Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- scikit-learn

## 📊 Dataset
A sample **House Price Dataset** was used with the following features:
- `Size_sqft` – Size of the house in square feet
- `Num_Rooms` – Number of rooms
- `Age_Years` – Age of the house in years
- `Price` – Target variable (House Price)

> The dataset was generated randomly for demonstration purposes.

## 📝 Steps Performed
1. Imported libraries and created sample dataset.
2. Preprocessed the dataset (features & target separation).
3. Split data into **train and test sets**.
4. Fit a **Linear Regression model** using scikit-learn.
5. Evaluated the model using:
   - **MAE** (Mean Absolute Error)
   - **MSE** (Mean Squared Error)
   - **R² Score** (Coefficient of Determination)
6. Interpreted model coefficients.
7. Plotted regression line (Price vs Size) & correlation heatmap.
8. Saved output plots in `outputs/figures/`.

## 📈 Model Evaluation
- **MAE:** 14,000 (example value – replace with your result)
- **MSE:** 270,000,000 (example value – replace with your result)
- **R² Score:** 0.95 (example value – replace with your result)

## 📂 Folder Structure

AI_ML_Internship/
├── Task3_Linear_Regression.ipynb # Jupyter Notebook
├── outputs/
│ └── figures/ # Contains saved plots
└── README.md


## 🎯 Learning Outcomes
- Understanding **linear regression assumptions**.
- Interpreting **coefficients** and **R² score**.
- Evaluating model performance using **MAE** and **MSE**.
- Visualizing relationships between features and target.

## 🖼 Outputs
- `outputs/figures/price_vs_size.png` – Regression line
- `outputs/figures/correlation_heatmap.png` – Feature correlation heatmap

---

## ❓ Interview Questions & Answers

**1. What assumptions does linear regression make?**  
- Linearity: Relationship between features and target is linear.  
- Independence: Observations are independent of each other.  
- Homoscedasticity: Constant variance of residuals.  
- Normality: Residuals are normally distributed.  
- No multicollinearity: Features are not highly correlated.

**2. How do you interpret the coefficients?**  
- Each coefficient represents the expected change in the target variable for a **one-unit change in the feature**, keeping all other features constant.

**3. What is R² score and its significance?**  
- R² (coefficient of determination) indicates how much variance in the target is explained by the model.  
- Ranges from 0 to 1; higher is better.

**4. When would you prefer MSE over MAE?**  
- MSE penalizes larger errors more heavily than MAE, so it’s preferred when large errors are particularly undesirable.

**5. How do you detect multicollinearity?**  
- Use **correlation matrices** or **Variance Inflation Factor (VIF)**.  
- High correlation (close to ±1) or high VIF (>10) indicates multicollinearity.

**6. What is the difference between simple and multiple regression?**  
- Simple regression: Only **one independent variable**.  
- Multiple regression: **Two or more independent variables**.

**7. Can linear regression be used for classification?**  
- No, linear regression predicts continuous values. Classification requires models like **Logistic Regression**, Decision Trees, etc.

**8. What happens if you violate regression assumptions?**  
- Predictions may be biased or inefficient.  
- Standard errors, confidence intervals, and p-values may be incorrect, leading to unreliable conclusions.

