# Vortex Tech AI & ML Internship – Week 2

## Build a Classification Model using Scikit-learn

This repository contains my **Week 2 assignment** for the **Vortex Tech AI & ML Internship Program**. The objective of this project is to build and evaluate a machine learning classification model using the Titanic dataset.

---

## 📌 Project Objective

The main objectives of this project are to:

- Load and prepare the cleaned Titanic dataset.
- Select appropriate feature and target variables.
- Encode categorical features into numerical values.
- Split the dataset into training and testing sets.
- Train a Logistic Regression classification model.
- Evaluate the model using multiple performance metrics.
- Interpret the model's results and discuss possible improvements.

---

## 📂 Dataset

**Dataset:** Titanic Dataset

- **Source:** Kaggle
- **Format:** CSV
- **Type:** Binary Classification Dataset

The dataset contains passenger information such as passenger class, gender, age, fare, family relationships, embarkation port, and survival status.

---

## 🛠 Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## 📁 Project Structure

```text
VORTEXTECH-AIML-WEEK2/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── notebook/
│   └── Week2_Classification_Model.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
├── .gitattributes
└── venv/ (local virtual environment, not uploaded to GitHub)
```

---

## 📋 Tasks Completed

### ✅ 1. Imported Required Libraries

Imported the required Python libraries for:

- Data manipulation
- Data preprocessing
- Machine learning
- Model evaluation

---

### ✅ 2. Loaded the Dataset

- Loaded the cleaned Titanic dataset using Pandas.
- Inspected the dataset structure.
- Identified feature columns and the target variable.

---

### ✅ 3. Data Preprocessing

Performed the following preprocessing steps:

- Selected relevant feature columns.
- Selected the target variable (**Survived**).
- Converted categorical variables into numerical values using one-hot encoding (`pd.get_dummies()`).

---

### ✅ 4. Split the Dataset

Divided the dataset into:

- Training Set (80%)
- Testing Set (20%)

using Scikit-learn's `train_test_split()` function.

---

### ✅ 5. Built the Classification Model

Implemented a **Logistic Regression** model to predict passenger survival.

The model was trained using the training dataset and then used to generate predictions on the testing dataset.

---

### ✅ 6. Evaluated the Model

The model's performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## 📊 Results

The Logistic Regression model successfully classified passenger survival using the selected features.

Performance was evaluated using multiple classification metrics, providing insight into the model's predictive ability and overall effectiveness.

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/<your-github-username>/VORTEXTECH-AIML-WEEK2.git
```

### Navigate to the project folder

```bash
cd VORTEXTECH-AIML-WEEK2
```

### (Optional) Create a virtual environment

```bash
python -m venv venv
```

Activate it.

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

---

### Install the required libraries

```bash
pip install -r requirements.txt
```

---

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebook/Week2_Classification_Model.ipynb
```

Run all cells to reproduce the analysis and model evaluation.

---

## 🎯 Learning Outcomes

Through this project, I learned how to:

- Prepare data for machine learning.
- Encode categorical variables.
- Split data into training and testing sets.
- Train a Logistic Regression model.
- Evaluate a classification model using Accuracy, Precision, Recall, and F1-Score.
- Interpret machine learning results and identify possible improvements.

---

## 👤 Author

**Pratik Sharma**

Bachelor in Computer Engineering (BCE)

Vortex Tech AI & ML Internship

2026
