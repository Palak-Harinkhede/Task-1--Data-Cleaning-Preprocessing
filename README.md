# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 🎯 Objective
Clean and preprocess the Titanic dataset to make it ready for machine learning. 
This includes handling missing values, encoding categorical data, scaling numerical features, and removing outliers.

---

## 🛠️ Tools Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Dataset Info
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Format: CSV
- Key columns: `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🧼 Steps Performed

### 1. Import and Explore
- Loaded data using `pandas`
- Viewed shape, column names, datatypes, and null values

### 2. Handle Missing Values
- `Age`: Filled using **median**
- `Embarked`: Filled using **mode**
- `Cabin`: Dropped due to too many missing values

### 3. Encode Categorical Variables
- Applied **One-Hot Encoding** to `Sex` and `Embarked`

### 4. Scale Numerical Features
- Standardized `Age` and `Fare` using **StandardScaler**

### 5. Outlier Detection and Removal
- Used **boxplots** to visualize outliers
- Removed outliers in `Fare` using **IQR method**

---

## 💾 Output
Final cleaned dataset saved as: Cleaned_Titanic

---

## 💡 What I Learned
- Data cleaning techniques for ML
- Handling nulls, categorical encoding, and outlier treatment
- Difference between normalization and standardization
- Impact of preprocessing on model accuracy


