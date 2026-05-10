Student Performance Analysis using PySpark

Project Overview
This project analyzes student performance data using Apache PySpark for Big Data Analytics. It demonstrates data loading, cleaning, transformation, and visualization capabilities.

Tools & Technologies Used
- Anaconda Distribution
- Apache Spark (PySpark)
- Jupyter Notebook
- Python 3.x
- Pandas & Matplotlib for visualization

Dataset
- Manually created CSV file with 23 student records
- Columns: ID, Name, Department, Marks
- 2 records with missing values for cleaning demonstration

Tasks Performed

1. Data Loading
- Loaded CSV dataset using PySpark DataFrame API
- Schema automatically inferred (ID: integer, Name: string, Department: string, Marks: integer)

2. Data Cleaning
- Identified 2 records with missing marks (Uma & Victor)
- Removed null values using dropna() function
- Final cleaned dataset: 21 records

3. Analysis Results

**Average Marks by Department:**
| Department | Average Marks |
|------------|---------------|
| Computer Science | 82.29 |
| Physics | 76.67 |
| Mathematics | 75.88 |

**Top 5 Students:**
| Rank | Name | Department | Marks |
|------|------|------------|-------|
| 1 | Grace | Computer Science | 95 |
| 2 | Kate | Mathematics | 93 |
| 3 | Rachel | Physics | 92 |
| 4 | Charlie | Computer Science | 91 |
| 5 | Eve | Mathematics | 88 |

 4. Key Findings
- Computer Science department has highest average marks (82.29)
- Overall average marks: 78.24
- Highest score: 95 (Grace), Lowest score: 45 (Henry)
- Mathematics has the most students (8), Physics has the least (6)
- 5 students scored above 85 marks (High Performers)

 5. Visualizations Created
- Bar chart: Average marks by department
- Horizontal bar chart: Top 5 students
- Pie chart: Student distribution by department
- Histogram: Distribution of student marks

 Challenges & Learnings
- Handling missing data in PySpark DataFrames
- Managing Windows-specific Hadoop configuration issues
- Converting between PySpark and Pandas DataFrames for visualization
- Understanding PySpark's column operations and aggregations

 Conclusion
Successfully analyzed student performance data using PySpark, demonstrating essential big data processing skills including data cleaning, aggregation, sorting, and visualization on a sample dataset.

---

Submitted by:Fizah Iman 
Ag - no : 2023-ag-9537
Date: 9 May 2026  
Course: Big Data 
