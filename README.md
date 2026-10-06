# Task 17 - Dataset Exploration

## 📌 Overview

This project is part of my AI & ML Internship tasks.

The objective of this task is to explore and understand a dataset using Python and Pandas before applying machine learning techniques.

For this task, the **Iris dataset** is used for basic dataset exploration and analysis.

---

## 🎯 Objectives

- Load and explore a dataset using Python.
- Understand the structure and dimensions of the dataset.
- Identify column names and data types.
- Generate statistical summaries.
- Check for missing values.
- Identify numerical and categorical columns.
- Examine unique values in categorical columns.
- Make observations about the dataset.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

The **Iris dataset** contains information about three species of iris flowers:

- Setosa
- Versicolor
- Virginica

The dataset contains:

- **150 rows**
- **5 columns**

### Columns

| Column | Type | Description |
|---|---|---|
| `sepal_length` | Numerical | Length of the sepal |
| `sepal_width` | Numerical | Width of the sepal |
| `petal_length` | Numerical | Length of the petal |
| `petal_width` | Numerical | Width of the petal |
| `species` | Categorical | Species of the iris flower |

---

## 🔍 Exploratory Data Analysis

The following Pandas functions were used:

```python
df.shape
````

Used to find the number of rows and columns.

```python
df.columns
```

Used to display the column names.

```python
df.info()
```

Used to understand data types, non-null values, and memory usage.

```python
df.describe()
```

Used to generate statistical summaries of numerical columns.

```python
df.head()
```

Used to display the first few rows.

```python
df.tail()
```

Used to display the last few rows.

```python
df.isnull().sum()
```

Used to check for missing values.

```python
df.select_dtypes(include='number')
```

Used to identify numerical columns.

```python
df.select_dtypes(include=['str'])
```

Used to identify categorical/string columns.

```python
df['species'].unique()
```

Used to find unique species.

```python
df['species'].value_counts()
```

Used to count the number of observations for each species.

---

## 📝 Observations

1. The Iris dataset contains 150 rows and 5 columns.
2. The dataset contains four numerical columns.
3. The `species` column is categorical.
4. The dataset contains no missing values.
5. There are three different species: Setosa, Versicolor, and Virginica.
6. Each species contains 50 observations.
7. The `describe()` function provides useful statistical information about the numerical features.

---

## 💡 Interview Questions

### 1. Why should a dataset be explored before modeling?

Dataset exploration helps us understand the structure and characteristics of the data before building a machine learning model. It helps identify data types, missing values, outliers, distributions, and possible data quality problems.

### 2. What does DataFrame.shape return?

`DataFrame.shape` returns a tuple containing the number of rows and the number of columns in a DataFrame.

For the Iris dataset:

```python
df.shape
```

Output:

```text
(150, 5)
```

This means the dataset contains 150 rows and 5 columns.

### 3. What information does info() provide?

The `info()` function provides information about a DataFrame, including column names, number of non-null values, data types, number of entries, and memory usage.

---

## 📁 Project Structure

```text
Task-17-Dataset-Exploration/
│
├── Task_17_Dataset_Exploration.ipynb
└── README.md
```

---

## ▶️ How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
Task_17_Dataset_Exploration.ipynb
```

5. Run the cells from top to bottom.

---

## ✅ Conclusion

The Iris dataset was successfully explored using Python and Pandas. The exploration helped understand the dataset's structure, dimensions, data types, statistical properties, missing values, and categorical features.

This task demonstrates the importance of understanding and preparing a dataset before applying machine learning algorithms.

---

## 👨‍💻 Author

**Divakar R**

AI & ML Internship

**Task 17 - Dataset Exploration**

```
```
