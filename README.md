# 📊 ML Data Preprocessing & EDA

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Scikit--Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)

</p>

## 📖 Overview

This project demonstrates the complete **data preprocessing pipeline** for two Machine Learning datasets. It covers **Exploratory Data Analysis (EDA)**, **data cleaning**, **feature engineering**, and **preprocessing** to transform raw data into a model-ready format.

### 📂 Project Structure

```
├── heart_disease.ipynb
├── insurance.ipynb
├── heart.csv
├── insurance.csv
└── README.md
```

---

## ❤️ Heart Disease Dataset

**Dataset:** 918 rows × 12 columns

### Tasks Performed

* Loaded and explored the dataset
* Checked data types, summary statistics, missing values, and duplicates
* Visualized feature distributions using histograms and count plots
* Replaced invalid `0` values in **Cholesterol** and **RestingBP**
* Generated additional visualizations (boxplots, violin plots, heatmap)
* Applied One-Hot Encoding using `pd.get_dummies()`
* Standardized numerical features with `StandardScaler`
* Selected important features using:

  * Pearson Correlation
  * Chi-Square Test
* Saved the processed dataset as `df_final`

---

## 💰 Insurance Dataset

**Dataset:** 1338 rows × 7 columns

### Tasks Performed

* Performed exploratory data analysis
* Removed duplicate records
* Encoded categorical features
* Renamed columns for better readability
* Applied One-Hot Encoding on `region`
* Created a new `bmi_category` feature
* Standardized numerical features
* Performed feature selection using:

  * Pearson Correlation
  * Chi-Square Test
* Saved the processed dataset as `df_final`

---

## 📚 Skills Practiced

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Feature Encoding
* Feature Scaling
* Data Visualization
* Correlation Analysis
* Chi-Square Feature Selection

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Google Colab
