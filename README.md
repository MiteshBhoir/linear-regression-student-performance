# Linear Regression Practice – Student Performance Prediction

This project is a practice implementation of Linear Regression using Python to predict student exam performance.

The goal of this project is to understand the complete machine learning workflow including exploratory data analysis, data preprocessing, feature engineering, model training, and evaluation.

---

## Project Objective

To predict the **Final Exam Score** of students based on different factors such as:

- Study hours per week
- Attendance rate
- Past exam scores
- Gender
- Internet access
- Extracurricular activities
- Parental education level

---

## Workflow

### 1. Exploratory Data Analysis (EDA)

The dataset was analyzed using visualizations such as:

- Histograms
- Boxplots
- Line plots
- Count plots
- Correlation heatmap

These visualizations help understand the distribution and relationships between features.

---

### 2. Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Dropped unnecessary columns
- Checked for missing values

---

### 3. Feature Engineering

Categorical variables were converted into numerical form using:

- Label mapping
- One-hot encoding

Feature scaling was applied using **StandardScaler**.

---

### 4. Feature Relationship Analysis

Pearson Correlation was used to analyze relationships between numeric features and the final exam score.

---

### 5. Model Training

The dataset was split into training and testing sets.

A **Linear Regression model** was trained using the training data.

---

### 6. Model Evaluation

The model performance was evaluated using:

- **R² Score**
- **Adjusted R² Score**

The model achieved an **R² score of approximately 0.83**, indicating that the model explains about **83% of the variance in student exam scores**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Google Colab

---

## Project Structure
```
linear-regression-student-performance
│
├── Student_performance.ipynb
├── student_performance_dataset.csv
└── README.md

```
---

## Learning Outcome

This project helped me understand:

- Data preprocessing techniques
- Exploratory data analysis
- Feature engineering
- Regression modeling
- Model evaluation using R²

---

## Author

Mitesh Bhoir  
Computer Engineering Student  
Full Stack Developer | Learning Machine Learning
