# 🧠 Adult Income Classification Using Machine Learning

This project is focused on building and evaluating multiple machine learning models to predict whether an individual's annual income exceeds $50K, based on demographic and employment-related attributes from the **Adult Census Income Dataset**.

## 📌 Project Highlights

- ✅ 91.39% Accuracy Achieved using **Gradient Boosting**
- ✅ Compared 4 algorithms: Logistic Regression, Random Forest, Gradient Boosting, XGBoost
- ✅ Used **Optuna** for hyperparameter optimization
- ✅ Applied **SMOTE** for class balancing
- ✅ Performed detailed **data cleaning**, **encoding**, and **scaling**
- ✅ Real-world dataset: Adult Census Income Dataset (large, noisy & imbalanced)

## 📂 Dataset Info

- **Source**: Kaggle (UCI Adult Dataset based, Pakistan-based version)
- **Target Column**: `income` (<=50K or >50K)

### Example Row:
```csv
age,workclass,education,marital.status,occupation,relationship,race,sex,capital.gain,hours.per.week,native.country,income
41,Private,Bachelors,Married,Exec-managerial,Husband,White,Male,0,40,United-States,>50K
