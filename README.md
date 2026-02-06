# VAUTECH IT SOLUTIONS – TASK 2

**Intern:** Abhishek Parihar  
**Intern ID:** VT26DS005  
**Domain:** Data Science
**Company:** VAUTECH IT SOLUTIONS  
**Mentor:** Vishal Rajbhar
 
**Task:** Data Loading and Initial Exploration 

---

## Objective

The objective of this task is to load tha suicide dataset into python and perform initial exploration to understand the structure, size, data types, missing values, and basic statistical properties of the data before performing further analysis.

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code

## Dataset Information

- Dataset: Suicide Data
- Format: CSV
- Source: https://raw.githubusercontent.com/MainakRepositor/Datasets/master/Suicide%20data.csv

## Step 1: Loading the Dataset

import pandas as pd
df = pd.read_csv('suicide_data.csv')

![Screenshot](Images/load_data.png)

## Step 2: Preview Data
df.head()

![Screenshot](Images/preview.png)

## Step 3: Checking Dataset size
df.shape

![Screenshot](Images/dataset.png)

## Step 4: Checking Datatype and Structure
df.info()

![Screenshot](Images/datatype.png)

## Step 5: Checking missing Values
df.isnull().sum()

![Screenshot](Images/missing_value.png)

## Step 6: Checking Inconsistency 
for col in df.select_dtypes('object'):
    print(f"\nColumn: {col}")
    print(df[col].value_counts().head(10))

![Screenshot](Images/inconsistency.png)

## Step 7: Summary Statistics
df.describe()

![Screenshot](Images/summary.png)

---

## Conclusion

In this task, the dataset was successfully loaded and explored. The structure, size, data types, missing values, and basic statistics of the dataset were analyzed. This step ensures a proper understanding of the data before moving to data cleaning, visualization, or advanced analysis.