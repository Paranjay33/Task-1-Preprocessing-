# ML Preprocessing Task 1 - Titanic Dataset 🚢

This repository contains the solution for **Task 1: Data Cleaning & Preprocessing** from the AI & ML Internship. The task is focused on preparing raw data for machine learning by handling missing values, encoding categorical features, scaling numerical features, and dealing with outliers.

---

## 📌 Objective

To clean and preprocess the Titanic dataset for use in machine learning models.

---

## 📂 Dataset

**Source:** [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
**Alternate Link Used in Notebook:**  
[https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 🧪 Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

## 🛠 Preprocessing Steps

1. **Loaded the dataset**
2. **Explored data**: checked for nulls, data types, and summary stats
3. **Handled missing values**:
   - Filled missing `Age` with median
   - Filled missing `Embarked` with mode
   - Dropped `Cabin` column (too many nulls)
4. **Encoded categorical variables**:
   - Used one-hot encoding for `Sex` and `Embarked`
5. **Normalized numerical features**:
   - Scaled `Age` and `Fare` using StandardScaler
6. **Detected & removed outliers**:
   - Used IQR method on `Age` and `Fare`
   - Visualized with boxplots

---

## 📊 Output

- Cleaned and preprocessed dataset
- Ready for ML modeling

---



## 📧 Author

Paranjay Singh Jamwal 
AI & ML Internship — Task 1
