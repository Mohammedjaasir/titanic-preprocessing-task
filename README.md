# titanic-preprocessing-task
# 🚢 Titanic Data Preprocessing - Internship Task 1

## 📌 Objective
Clean and prepare the Titanic dataset for machine learning by handling missing values, encoding categorical features, normalizing data, and removing outliers — ensuring the data is analysis-ready.

---

## 📁 Dataset
[Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🔧 Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🧪 Steps Performed

### 1. **Data Inspection**
- Loaded the dataset and explored the shape, column types, and missing values.
- Checked class imbalance and feature distributions.

### 2. **Handling Missing Values**
- Filled `Age` using **median** to avoid skew.
- Filled `Embarked` using **mode** (most frequent).
- Dropped `Cabin` due to high null count.

### 3. **Encoding Categorical Data**
- Converted `Sex` to numerical using **label encoding**.
- Used **one-hot encoding** for `Embarked`.

### 4. **Feature Scaling**
- Standardized `Age` and `Fare` using **StandardScaler** to ensure even scale across features.

### 5. **Outlier Detection & Removal**
- Visualized outliers using **boxplots**.
- Removed top 5% outliers in `Fare` to reduce noise.

### 6. **Exploratory Data Analysis (EDA)**
- Visualized survival rate by `Sex`, `Pclass`, and correlated features using a **heatmap**.

### 7. **Export**
- Final cleaned dataset saved as `titanic_cleaned.csv`.

---

## 📊 Key Insights
- Female passengers had a significantly higher survival rate.
- Passengers in 1st class had a higher chance of survival.
- Feature scaling and clean encoding improved data readiness for modeling.

---

## 📝 Files in this Repo
| File Name               | Description                           |
|------------------------|---------------------------------------|
| `task1_titanic_preprocessing.ipynb` | Main notebook with code + visuals |
| `titanic_cleaned.csv`  | Cleaned dataset ready for ML          |
| `README.md`            | This file                             |

---
