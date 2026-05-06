# 🎓 Student Performance Analysis using Machine Learning

## 📌 Project Overview
This project analyzes student academic performance using Machine Learning techniques.  
The project performs both:

- 🔵 Classification → Predict Pass/Fail
- 🔴 Regression → Predict Student Math Scores

The dataset used in this project is the **Students Performance in Exams** dataset from Kaggle.

---

# 📊 Dataset Information

- Dataset Name: Students Performance in Exams
- Source: Kaggle
- File Used: `StudentsPerformance.csv`

### Dataset Features
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

---

# ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🔍 Machine Learning Techniques Used

## 🔵 Classification

### 1. Logistic Regression
- Type: Binary Classification
- Purpose: Predict student Pass/Fail status

### 2. K-Nearest Neighbors (KNN)
- Purpose: Predict class based on nearest neighboring data points

### 3. Random Forest Classifier
- Purpose: Improve prediction accuracy using multiple decision trees

---

## 🔴 Regression

### 1. Linear Regression
- Type: Multiple Linear Regression
- Purpose: Predict student math scores

### 2. Random Forest Regressor
- Purpose: Improve regression prediction performance

---

# 📈 Data Preprocessing

The following preprocessing steps were performed:

- Handling categorical data using encoding
- Creating Pass/Fail target column
- Feature selection
- Train-test split
- Feature scaling for KNN

---

# 📊 Visualizations

The project includes:

- Correlation Heatmap
- Score Distribution Graphs
- Scatter Plots
- Pairplots

---

# 🧠 Models Evaluation

### Classification Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

### Regression Metrics
- Mean Squared Error (MSE)
- R² Score

---

# 🚀 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
4. Exploratory Data Analysis
5. Data Visualization
6. Classification Models
7. Regression Models
8. Model Evaluation
9. Conclusion

---

# 📌 Conclusion

This project demonstrates how Machine Learning can be used to analyze and predict student academic performance using classification and regression techniques.

The models successfully learned patterns from the dataset and produced accurate predictions.

---

# 🔮 Future Improvements

- Add Deep Learning models
- Use larger educational datasets
- Deploy project using Flask or Streamlit
- Improve accuracy using hyperparameter tuning

---

# 📂 Project Structure

```bash
project/
│
├── StudentsPerformance.csv
├── student_performance_analysis.ipynb
├── README.md
└── requirements.txt
