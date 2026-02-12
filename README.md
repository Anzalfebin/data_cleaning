## 📌 Objective
The objective of this task is to learn how to clean and prepare raw data for Machine Learning models. This includes handling missing values, encoding categorical variables, feature scaling, and detecting/removing outliers.

---

## 📂 Dataset Used
- **Dataset:** Titanic Dataset  
- **Source:** Public dataset (Kaggle / Open-source ML datasets)  
- The dataset contains passenger information such as Age, Sex, Fare, Embarked, etc., and whether they survived.

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔎 Steps Performed

### 1️⃣ Data Exploration
- Loaded dataset using Pandas  
- Checked dataset shape and data types  
- Identified missing values using `.isnull().sum()`  
- Generated statistical summary using `.describe()`  

### 2️⃣ Handling Missing Values
- Filled numerical missing values (e.g., Age) using **median**  
- Filled categorical missing values (e.g., Embarked) using **mode**  
- Dropped columns with excessive missing values (e.g., Cabin)  

### 3️⃣ Encoding Categorical Variables
- Applied **Label Encoding** for binary categories (e.g., Sex)  
- Applied **One-Hot Encoding** for multi-class categorical features (e.g., Embarked)  

### 4️⃣ Feature Scaling
- Used **Standardization (StandardScaler)**  
- Scaled numerical features like Age and Fare  
- Transformed features to have:
  - Mean = 0  
  - Standard Deviation = 1  

### 5️⃣ Outlier Detection & Removal
- Visualized outliers using **Boxplots**  
- Used **IQR (Interquartile Range) method** to remove extreme values  

### 6️⃣ Final Output
- Generated a cleaned dataset ready for Machine Learning modeling  
- Saved cleaned dataset as:  

