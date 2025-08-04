# 🚗 Car Price Prediction

A Machine Learning project to predict the selling price of used cars based on key features like fuel type, transmission, kilometers driven, etc. The project compares **Linear Regression** and **Lasso Regression** models using Python and Scikit-learn.

---

## 📁 Dataset

- Source: [Kaggle Car Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- Format: CSV (`car_data.csv`)
- Target: `Selling_Price`

---

## 📌 Features Used

- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner
- Year (converted to age)

> 🔸 `Car_Name` is excluded from features.  
> 🔸 Categorical features are encoded using `.replace()`.

---

## 🧰 Tools and Technologies Used

| Category         | Tools/Technologies |
|------------------|-------------------|
| Programming Language | Python 3 |
| Data Analysis        | Pandas |
| Data Visualization   | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn (LinearRegression, Lasso, train_test_split, r2_score) |
| IDE/Environment      | Google Colaboratory (Colab) |
| Dataset Source       | Kaggle - Car Data CSV |

---


## 🧠 Model Workflow

1. Import and preprocess data
2. Encode categorical variables
3. Train/test split (90/10)
4. Train & evaluate:
   - Linear Regression
   - Lasso Regression
5. Visualize predictions using scatter plots

---

## 📈 Evaluation Metric

- **R² Score** (Higher = Better)

Both models are evaluated on:
- Training Data
- Testing Data

---

## 📈 Visualizations

The project includes scatter plots of:
- Actual vs Predicted Selling Prices (for both train and test sets)
- Helps understand how well the model is performing.

---

## 💡 Key Learnings

- How to handle categorical data via encoding
- Difference between Linear and Lasso Regression
- Visualizing performance using scatter plots
- Evaluating models with R-squared error

---

## ✅ Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Deploy the model using Flask or Streamlit
- Add GUI to make it interactive
- Try other regression models (Ridge, Decision Tree, XGBoost)

---

## ✅ Conclusion

This project builds and compares Linear and Lasso Regression models to predict used car prices. Both models perform well, with Lasso slightly outperforming in some cases. The workflow highlights data preprocessing, encoding, and evaluation using R² score.
