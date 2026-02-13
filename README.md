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

![Screenshot](Images/import.png)

## Step 2: Preview Data
df.head()

![Screenshot](Images/head.png)

## Step 3: Handling Missing values

![Screenshot](Images/missing.png)

## Step 4: Removing Duplicate values

![Screenshot](Images/drop.png)

## Step 5: Creating seperate columns for each category

![Screenshot](Images/dummy.png)

## Step 6:  Saving clean data set 

![Screenshot](Images/clean.png)

---

## Conclusion

In this task, the dataset was successfully loaded and explored. The structure, size, data types, missing values, and basic statistics of the dataset were analyzed. This step ensures a proper understanding of the data before moving to data cleaning, visualization, or advanced analysis.