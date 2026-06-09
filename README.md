# 🎓 Student Score Prediction using Linear Regression

## Project Overview

This project uses Machine Learning to predict a student's mathematics score based on their reading and writing performance.

The objective is to understand the relationship between different academic scores and build a predictive model that can estimate a student's mathematics score using Linear Regression.

This project demonstrates a complete beginner-friendly Machine Learning workflow including data analysis, visualization, model training, evaluation, and prediction.

---

## Dataset

The dataset contains information about student performance in examinations.

### Features Used

* Reading Score
* Writing Score

### Target Variable

* Math Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Machine Learning Workflow

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas
* Checked dataset dimensions
* Verified missing values
* Generated descriptive statistics

### 2. Exploratory Data Analysis (EDA)

* Mathematics Score Distribution
* Reading Score vs Mathematics Score
* Writing Score vs Mathematics Score
* Correlation Matrix
* Correlation Heatmap
* Pairplot Analysis

### 3. Data Preparation

* Selected Reading Score and Writing Score as input features
* Selected Mathematics Score as the target variable
* Split the dataset into Training and Testing sets

### 4. Model Training

A Linear Regression model was trained using Scikit-Learn.

### 5. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Prediction

The trained model can predict a student's mathematics score based on new reading and writing scores.

---

## Key Insights

* Reading and writing scores show a strong positive correlation with mathematics scores.
* Students performing well in reading and writing generally tend to achieve higher mathematics scores.
* Linear Regression provides a simple and effective approach for predicting student performance.

---

## Project Structure

```text
student-score-prediction/
│
├── data/
│   └── student_scores.csv
│
├── notebook/
│   └── Student_Score_Prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/student-score-prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook
```

Open:

```text
Student_Score_Prediction.ipynb
```

and run all cells.

---

## Future Improvements

* Compare multiple regression models
* Feature engineering
* Hyperparameter tuning
* Interactive prediction interface using Streamlit

---

## Author

**Sasindra Sri Sai Nandam**

B.Tech – Computer Science and Engineering

Indian Institute of Information Technology Design and Manufacturing (IIITDM) Kancheepuram
