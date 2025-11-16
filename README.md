# SAPAPS – Smart Academic Performance Analyzer & Predictor System

SAPAPS is a Python-based project that analyzes student academic performance using CSV data and generates meaningful insights.  
It is developed as a mini-project for the Python Programming course in BTech CSE (AI/ML).

---

## Project Overview

This project reads student marks from a CSV file, processes the data using Pandas and NumPy, and produces:

- Class statistics (average, highest, lowest marks)
- Subject-wise performance analysis
- Top performer list
- Pass/Fail status for each student
- Simple prediction of future performance
- Identification of students at academic risk

The entire project is implemented in a Jupyter Notebook (`.ipynb`) using Object-Oriented Programming concepts.

---

##  Tech Stack

- **Python 3.x**
- **Pandas** – data handling and analysis  
- **NumPy** – numerical and statistical calculations  
- **Jupyter Notebook** – development and execution environment  
- **CSV** – input and output data format  

---

##  Repository Structure


---

##  How to Run

1. Open the project folder in **VS Code** or **Jupyter Notebook**.  
2. Open `student_performance_analyzer.ipynb`.  
3. Run all cells from top to bottom in order.  
4. The notebook will:
   - Create or load `student_data.csv`
   - Perform analysis
   - Display statistics, top performers, predictions, and alerts

---

##  Main Features

### 1. Student Class (OOP)
- Stores individual student details  
- Adds subject-wise marks  
- Calculates average and pass/fail status  

### 2. PerformanceAnalyzer Class
- Loads data from CSV  
- Computes overall and subject-wise statistics  
- Generates pass/fail distribution  
- Identifies at-risk students  

### 3. Prediction Module
- Uses a simple improvement assumption to predict future average marks  
- Gives a qualitative assessment (Excellent / Good / Needs improvement)

---

##  Sample Outputs

- Class average, highest and lowest average marks  
- Subject-wise mean, maximum, and minimum marks  
- Table of top N performers  
- List of students with average marks below the passing threshold  

(You can also add screenshots of the notebook outputs here.)

---

##  Learning Outcomes

This project demonstrates:

- Practical use of Python for real-world data analysis  
- Application of Object-Oriented Programming  
- Working with Pandas DataFrames and CSV files  
- Performing basic statistical operations with NumPy  
- Writing clean, modular, and well-documented code

---

##  Author

**PRASHANT LONDHE**  
BTech CSE (AI/ML), Sanjivani University  

GitHub: [prrashantlondhe](https://github.com/prrashantlondhe)

---

This project is created for educational purposes as part of a university Python Programming course.  
Feel free to fork and modify it for learning and academic use.
