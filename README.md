# Student_Performance_Analysis
Student performance analysis using Python, Pandas and NumPy

## Project Overview

This project analyses student academic performance using Python, Pandas, and NumPy. It uses a CSV dataset containing student details, subject marks, and attendance to evaluate academic performance and generate meaningful insights.

The project demonstrates fundamental data analysis skills, including data loading, DataFrame manipulation, numerical calculations, conditional logic, reusable functions, loops, and data aggregation.

## Objectives

- Load and organise student data from a CSV file using Pandas.
- Inspect dataset structure, column names, data types, and missing values.
- Use NumPy for numerical calculations and statistical analysis.
- Calculate total marks and average marks for each student.
- Assign grades based on predefined grading criteria.
- Identify students who pass or fail.
- Analyse subject-wise academic performance.
- Identify the highest-performing and lowest-performing students.
- Determine the top five students based on average marks.
- Analyse attendance and grade distribution.
- Export processed results to CSV files.

## Technologies Used

- **Python** — core programming language
- **Pandas** — data loading, DataFrame manipulation, filtering, and aggregation
- **NumPy** — numerical calculations and statistical analysis
- **Google Colab** — cloud-based Python development environment
- **GitHub** — source code management and project documentation

## Dataset Description

The project uses `Student_data.csv`, containing 20 student records.

The dataset includes the following fields:

| Column | Description |
|---|---|
| `Student_Id` | Unique student identifier |
| `Name` | Student name |
| `SQL` | SQL subject marks |
| `Python` | Python subject marks |
| `Artificial Intelligence` | Artificial Intelligence subject marks |
| `Big Data Analytics` | Big Data Analytics subject marks |
| `Data Structures` | Data Structures subject marks |
| `Attendance` | Student attendance percentage |

Subject marks and attendance are expected to be numeric values between 0 and 100.

## Project Methodology

### 1. Data Loading and Inspection

The CSV file is loaded into a Pandas DataFrame. The dataset is inspected using functions such as `head()`, `info()`, `describe()`, and `isnull().sum()`.

### 2. Data Validation

The project checks for missing or non-numeric values, duplicate student IDs, and marks or attendance outside the valid range.

### 3. Data Processing

Reusable Python functions calculate total marks, average marks, grades, and pass/fail results. Loops and conditional statements are used to process student records and evaluate individual subjects.

### 4. Academic Performance Analysis

Pandas and NumPy are used to calculate:

- Overall class average
- Highest and lowest student averages
- Median and standard deviation of student averages
- Subject-wise average, maximum, and minimum marks
- Pass and fail counts and percentages
- Top five students
- Grade distribution
- Average attendance and students with attendance below 75%

### 5. Results Export

The processed student results and summary analyses are exported to CSV files for further analysis and reporting.

## Grading Criteria

Grades are assigned according to the student's average marks across five subjects.

| Average Marks | Grade |
|---|---|
| 80 and above | A |
| 70 to below 80 | B |
| 60 to below 70 | C |
| 40 to below 60 | D |
| Below 40 | F |

**Pass/Fail Rule:** A student passes only if they score at least 40 marks in every subject. A student who scores below 40 in any subject is classified as a fail.

The 75% attendance threshold is used for reporting purposes only and does not affect the pass/fail calculation.

## Key Outputs

The project generates the following files:

- `Student_Performance_Results.csv` — student details, total marks, average marks, grades, and results.
- `Subject_Performance_Analysis.csv` — average marks for each subject.
- `Grade_Distribution.csv` — number of students in each grade.

The notebook also displays a final summary report containing the class average, top-performing students, subject comparisons, pass rate, and attendance statistics.

## How to Run the Project

1. Download or clone this GitHub repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload `Student_data.csv` to the Colab session.
4. Open `Student_Performance_Analysis.ipynb` in Google Colab, or paste the project code into a new notebook.
5. Ensure that the CSV filename and column names match those expected by the code.
6. Run the notebook cells from top to bottom.
7. Review the analysis results and download the generated CSV files.

## Skills Demonstrated

- Python programming fundamentals
- Pandas DataFrame operations
- NumPy numerical analysis
- Data validation and quality checks
- Functions, loops, variables, and conditional statements
- Statistical calculations and data aggregation
- CSV file handling
- Analytical thinking and interpretation of results
- GitHub repository management and documentation

## Conclusion

This project demonstrates how Python can be used to transform raw student records into structured academic performance insights. It provides practical experience in data processing, numerical analysis, and reporting, forming a foundation for more advanced data analytics projects
