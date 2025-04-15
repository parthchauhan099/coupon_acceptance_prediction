# 🎯 Coupon Acceptance Prediction

This project predicts whether a customer will accept a coupon offer based on demographic and behavioral attributes using machine learning techniques and statistical analysis.

## 📌 Project Description
The objective is to build a classification model that predicts the likelihood of a customer accepting a coupon. The dataset includes customer profile data such as age, gender, marital status, income, education level, and previous coupon usage.

## 📊 Exploratory Data Analysis (EDA)
- Analyzed categorical features like `age`, `gender`, `education`, and `marital status` using count plots and pie charts.
- Explored numerical variables such as `income` and `distance` using boxplots and histograms.
- Identified imbalance in coupon acceptance classes.
- Detected key influencing factors such as coupon type, weather, and time of day on acceptance behavior.

## 🧪 Statistical Tests
- **Chi-square test**: Assessed the relationship between categorical variables (e.g., education vs. coupon acceptance).
- **ANOVA test**: Evaluated if means of numerical variables like distance differ significantly across acceptance groups.

## 🧹 Data Preprocessing
- Handled missing values
- Encoded categorical variables using Label Encoding
- Scaled numerical features using StandardScaler
- Performed feature selection based on statistical significance and model importance

## 🤖 Machine Learning Models
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier

## 📈 Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-Score  
- ROC-AUC Curve  
- Confusion Matrix for model comparison

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- SciPy (for statistical tests)

---

✅ **Results**: The Random Forest Classifier achieved the highest performance, effectively identifying patterns in customer coupon acceptance.
