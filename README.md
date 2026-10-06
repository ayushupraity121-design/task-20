# Task 20: Sort Dataset

This repository contains the implementation for **Task 20: Sort Dataset** as part of the AI & ML track.

---

## 📌 Description
Sort a dataset using numerical and categorical columns in ascending and descending order using Python and Pandas in Jupyter Notebook.

---

## 🎯 Objective
Understand how sorting helps organize and analyze datasets effectively.

---

## 🛠️ Tools Used
* **Python 3.x**
* **Pandas**
* **Jupyter Notebook / VS Code**

---

## 📁 Dataset Details
The project utilizes a sample Employee Dataset containing both numerical and categorical features:
* `Employee_ID` (Integer)
* `Name` (String / Categorical)
* `Department` (String / Categorical)
* `Salary` (Numerical)
* `Experience_Years` (Numerical)

---

## 🚀 Deliverables & Examples

### 1. Ascending Sorting
Sorting numerical and categorical columns from lowest to highest or A to Z.
```python
# Numerical sort (Salary)
df_salary_asc = df.sort_values(by='Salary')

# Categorical sort (Department)
df_dept_asc = df.sort_values(by='Department')