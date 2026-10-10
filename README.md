# Student Pass/Fail Prediction Using Logistic Regression

## 📌 Project Overview

This project uses Machine Learning to predict whether a student will pass or fail based on academic performance and study habits. A Logistic Regression classification model is trained to predict the student's result.

## 🎯 Objective

To build a classification model that predicts student outcomes using attendance, homework performance, midterm scores, and weekly study hours.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Dataset

The dataset contains student information and academic performance features.

**Input Features:**
- `attendance_pct` — Student attendance percentage
- `homework_pct` — Homework performance percentage
- `midterm_score` — Midterm examination score
- `study_hours_per_week` — Weekly study hours

**Target Variable:**
- `pass` — Student result (0 = Fail, 1 = Pass)

The `student_id` column was excluded from the input features because it is an identifier rather than an academic performance measure.

## ⚙️ Project Workflow

1. Loaded the dataset using Pandas.
2. Explored the dataset and checked column data types.
3. Selected input features (`X`) and target variable (`y`).
4. Split the dataset into training and testing sets.
5. Trained a Logistic Regression model using Scikit-learn.
6. Predicted student results on the test set.
7. Evaluated the model using accuracy, precision, recall, and F1-score.
8. Visualized actual and predicted results using Matplotlib.

## 📊 Model Evaluation

The Logistic Regression model achieved the following results on the test dataset:

| Metric | Score |
|---|---:|
| Accuracy | 100% |
| Precision — Class 0 | 100% |
| Recall — Class 0 | 100% |
| F1-score — Class 0 | 100% |
| Precision — Class 1 | 100% |
| Recall — Class 1 | 100% |
| F1-score — Class 1 | 100% |
| Test Samples | 20 |

### Classification Report

| Class | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 (Fail) | 1.00 | 1.00 | 1.00 | 8 |
| 1 (Pass) | 1.00 | 1.00 | 1.00 | 12 |
| **Accuracy** | | | **1.00** | **20** |
| Macro Average | 1.00 | 1.00 | 1.00 | 20 |
| Weighted Average | 1.00 | 1.00 | 1.00 | 20 |

**Note:** These metrics represent the model's performance on the 20 test samples. Further validation is recommended to check how well the model generalizes to new student data.

## 📈 Visualizations

Matplotlib was used to visualize:
- Actual student pass/fail results.
- Predicted student pass/fail results.
- Confusion matrix.

## 💡 Key Learnings

- Understanding classification problems in Machine Learning.
- Implementing Logistic Regression using Scikit-learn.
- Splitting data into training and testing sets.
- Evaluating a classification model using performance metrics.
- Visualizing model predictions with Matplotlib.

## 🚀 Future Improvements

- Test additional classification algorithms.
- Validate the model using cross-validation.
- Tune model parameters to improve generalization.
- Test predictions on new student data.

## 📚 Dataset Credits

Dataset sourced from Kaggle:

[Student Pass/Fail Dataset — Kaggle](https://www.kaggle.com/datasets/ishanjha100/student-passfail-data)

Credit goes to the original dataset creator on Kaggle. Please refer to the dataset page for the original description and applicable license or usage conditions.

## 👨‍💻 Author

**Lokesh Babu**

Machine Learning Beginner | Python | SQL | AI/ML

