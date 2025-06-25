# house-prices-prediction
Predicting house prices using regression models
# 🏡 Boston Housing Price Prediction

This project focuses on predicting housing prices in Boston using regression models. The goal is to analyze the features affecting house prices and build a model that can accurately estimate property value based on those features.

---

## 📊 Dataset Description

The dataset contains information collected by the U.S Census Service concerning housing in the Boston area. It includes 13 numerical features such as:

- `CRIM`: Crime rate per capita
- `ZN`: Proportion of residential land zoned for large lots
- `INDUS`: Proportion of non-retail business acres
- `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `NOX`: Nitric oxide concentration
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built before 1940
- `DIS`: Distance to employment centers
- `RAD`: Accessibility to radial highways
- `TAX`: Property tax rate
- `PTRATIO`: Pupil-teacher ratio
- `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents
- `LSTAT`: % lower status of the population
- `PRICE`: Median house price (target)

---

 🧠 Workflow Summary

1. Data Loading & Cleaning  
   - Loaded from `sklearn.datasets`
   - Converted into a pandas DataFrame

2. Exploratory Data Analysis (EDA)  
   - Correlation matrix
   - Feature relationships with target (`PRICE`)

3.  Modeling 
   - Applied Linear Regression model  
   - Achieved ~70% R² Score  
   - Feature importance visualized

---

 ⚙️ Technologies Used

- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn (LinearRegression)

---

 📈 Future Improvements

- Try alternative models (Ridge, Lasso, Random Forest)
- Perform hyperparameter tuning
- Apply feature scaling
- Handle outliers for better generalization

---

 💡 Notes

This is a basic implementation intended to demonstrate understanding of regression modeling and the ML pipeline. The current model serves as a baseline and can be improved for higher performance.

---

 👩‍💻 Author

- **Bushra Fayeza Aburas**  
  Data Science Student at JUST  


