# Day 07 — Pandas Practice & Dataset Summary

This repository contains the Day 07 Python/Pandas learning practice and the Dataset Summary Report assignment.

## 📁 Notebooks

### 1. `day_07_practise.ipynb`

A beginner-friendly Pandas practice notebook designed to teach the fundamentals of working with tabular data.

Topics covered include:

- Introduction to Pandas
- Pandas Series
- Creating Series from lists and dictionaries
- Pandas DataFrames
- Creating DataFrames from dictionaries and NumPy arrays
- Converting DataFrames to NumPy arrays
- Basic Series operations
- Pandas index alignment and `NaN`
- Reading CSV files with `pd.read_csv()`
- Saving DataFrames using `to_csv()`
- Important `read_csv()` parameters: `sep`, `header`, `names`, `index_col`, and `usecols`
- Dataset inspection with `head()`, `tail()`, `sample()`, `shape`, `columns`, `index`, `dtypes`, `info()`, `describe()`, and `isnull().sum()`
- Common CSV loading pitfalls

The notebook is structured as a learning resource so that a beginner can follow the explanations and examples step by step.

### 2. `Day7_Dataset_Summary_Report.ipynb`

A practical Dataset Summary Report created using Python and Pandas.

The notebook demonstrates how to:

- Load `Day7_Student_Dataset.csv`
- Inspect the first few rows using `head()`
- Inspect the last few rows using `tail()`
- View random samples using `sample()`
- Check the dataset shape
- View column names
- Examine the DataFrame index
- Check column data types
- Use `info()` to inspect structure and non-null values
- Use `describe()` to generate descriptive statistics
- Identify missing values
- Write basic observations about the dataset

The assignment focuses on understanding the structure and characteristics of the dataset rather than performing advanced data analysis or machine learning.

## 📊 Dataset

The assignment uses `Day7_Student_Dataset.csv`.

The dataset contains student-related information such as:

- Student ID
- Name
- Age
- Course
- Marks
- Attendance Percentage
- City

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

## 🎯 Learning Objective

The main objective of Day 07 is to build a strong foundation in Pandas and learn how to inspect, understand, and summarize tabular datasets before moving on to deeper data analysis.

## 🚀 How to Use

1. Clone or download this repository.
2. Open `day_07_practise.ipynb` in Google Colab or Jupyter Notebook to study the Pandas concepts.
3. Open `Day7_Dataset_Summary_Report.ipynb` to review the practical dataset analysis.
4. If running the assignment notebook in Google Colab, upload `Day7_Student_Dataset.csv` before executing the data-loading cell.

## 📌 Note

The practice notebook and assignment notebook are intentionally kept separate. The practice notebook is for learning Pandas concepts, while the Dataset Summary Report is the practical assignment.
