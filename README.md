# DataFrame Project

## 📌 Project Description

This project demonstrates how to use **Python Pandas DataFrames** to store, organize, analyze, and display data.

A DataFrame is a two-dimensional data structure in Pandas. It looks similar to a table, with **rows and columns**. It is commonly used for data analysis and data science.

## 🛠️ Technologies Used

* Python
* Pandas
* Jupyter Notebook / VS Code


```

## 🚀 Getting Started

### 1. Install Python

Make sure Python is installed on your computer.

### 2. Install Pandas

Open the terminal and run:

```bash
pip install pandas
```

### 3. Import Pandas

```python
import pandas as pd
```

### 4. Create a DataFrame

Example:

```python
student_information = {
    "Name": ["Aaron", "John", "Sarah"],
    "Age": [20, 21, 19],
    "Course": ["IT", "Computer Science", "IT"]
}

df = pd.DataFrame(student_information)

print(df)
```

## 📊 Example Output

```text
    Name  Age            Course
0  Aaron   20                IT
1   John   21  Computer Science
2  Sarah   19                IT
```

## 🔍 Basic DataFrame Operations

### Display the first rows

```python
print(df.head())
```

### Display the last rows

```python
print(df.tail())
```

### Check the number of rows and columns

```python
print(df.shape)
```

### Display column names

```python
print(df.columns)
```

### Get information about the DataFrame

```python
print(df.info())
```

### Get statistical information

```python
print(df.describe())
```

## 📁 Reading a CSV File

A DataFrame can also be created from a CSV file:

```python
df = pd.read_csv("data.csv")

print(df)
```

## 🎯 Objectives

The main objectives of this project are to:

* Understand what a DataFrame is.
* Learn how to create a DataFrame.
* Learn how to read data from a CSV file.
* Learn how to display and inspect data.
* Perform basic data analysis using Pandas.

## 👨‍💻 Author

**Amanya Aaron**

Bachelor of Science in Information Technology (BSIT)

Uganda Christian University
