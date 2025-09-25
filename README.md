# 🎓 Student Performance Prediction using Linear Regression

## 📌 Project Overview
This project analyzes the **Student Performance Dataset** to understand factors affecting academic performance.  
We apply **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Linear Regression modeling** to predict the **Performance Index** of students.

---

## 📂 Dataset
- **File:** `Student_Performance.csv`
- **Features:**
  - `Hours Studied`
  - `Previous Scores`
  - `Extracurricular Activities`
  - `Sleep Hours`
  - `Sample Question Papers Practiced`
- **Target:**
  - `Performance Index`

---

## 🔧 Steps Performed

### 1️⃣ Data Exploration
- Loaded dataset with **Pandas**.
- Checked shape, columns, data types, and missing values.
- Statistical summary with `.describe()`.

### 2️⃣ Feature Engineering
- Converted **Extracurricular Activities** (Yes/No) to **binary (1/0)**.
- Normalized features using **max-scaling**.
- Checked **correlations** to understand feature importance.

### 3️⃣ Exploratory Data Analysis (EDA)
- Used **Seaborn Heatmaps** to visualize correlations.
- Plotted the **distribution** of Performance Index.

### 4️⃣ Model Building
- Applied **Linear Regression** with:
  - Single feature models (`Previous Scores`, etc.)
  - Multi-feature models (`Previous Scores + Sleep Hours`, All features).
- Split data into **Training and Testing sets**.

### 5️⃣ Model Evaluation
- Metrics used:
  - **R² (Coefficient of Determination)**
  - **Mean Squared Error (MSE)**
- Compared actual vs predicted values.

---

## 📊 Results
- **Single Feature Model (Previous Scores only):**
  - R² ≈ **0.84**
  - MSE ≈ **60**

- **Multi Feature Model (All features):**
  - R² ≈ **0.99**
  - MSE ≈ **4.04**

✅ The multi-feature model provides **high accuracy**, showing that combining study habits, sleep, and activities leads to better predictions of performance.

---

## 🚀 Tech Stack
- **Python**
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📌 Conclusion
- **Student Performance** can be effectively predicted using Linear Regression.  
- **Previous Scores** are a strong predictor, but adding **Sleep Hours**, **Study Hours**, and **Extracurricular Activities** significantly improves accuracy.  
- The project demonstrates the importance of **multi-feature modeling** in academic performance analysis.

---

## 📎 Future Improvements
- Try **Polynomial Regression** or **Random Forest Regressor** for comparison.  
- Perform **Hyperparameter Tuning**.  
- Add **cross-validation** to reduce bias.  
- Expand dataset for generalization.  

---

👨‍💻 **Author:** *Your Name*  
📅 **Year:** 2025
