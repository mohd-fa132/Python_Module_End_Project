# Python_Module_End_Project

# 📊 ABC Company Employee Data Analysis

# 📁 Project Overview

This project involves analyzing a dataset from ABC Company containing information on 458 employees across various teams. The dataset consists of 9 columns capturing different attributes such as age, position, height, salary, and team. The goal is to perform data preprocessing, conduct insightful analysis, and present results graphically to support decision-making.

# 🔧 Preprocessing

The height column was found to contain inconsistent or unrealistic values.
These values were corrected by replacing them with random numbers between 150 and 180 cm to reflect realistic human heights.
General data integrity checks (e.g., for missing/null values or duplicates) were performed to ensure clean data before analysis.

# 📈 Analysis Tasks and Results

Employee Distribution by Team

Counted the number of employees in each team.
Calculated the percentage each team contributes to the overall workforce.
Bar charts were used to visualize the distribution.
Segregation by Position

Grouped employees based on their job positions (e.g., Manager, Analyst, Developer).
Used pie chart to depict position-wise distribution.
Predominant Age Group

Analyzed the age distribution using bins (e.g., 20–30, 31–40, etc.).
Identified the age range with the highest employee count using a bar plot.
Salary Expenditure by Team and Position

Calculated total salary paid by each team and position.
Highlighted which team and position had the highest total payroll.
Represented findings using grouped bar plots .
Correlation Between Age and Salary

Investigated the relationship between employees’ age and salary using correlation analysis.
Created a scatter plot to visualize potential trends or patterns.

# 📊 Visualizations

Bar Charts: Team distribution
Pie Chart: Team and position percentage
Scatter Plot: Age vs Salary correlation
Heatmap or Grouped Bars: Salary expenditure by team/position

# 🔍 Key Insights

The team with the highest number of employees and salary expenses was identified.
Most employees fall within the [predominant age group].
There is [weak/moderate/strong/no] correlation between age and salary.
The [specific position] role contributes most to payroll expenses, highlighting potential workforce structuring decisions.
#v🔍 Findings

Team Distribution New Orleans Pelicans has most number of employees followed by Memphis Grizzlies team.

Position Segregation Majority of employees are SG and PF. C Position have least number of employees

Age Grouping Created clear age brackets: 11–20,21–30, 31–40, 41–50. Employees aged 21–30 dominate the workforce.

Salary Expenditure Cleveland Cavaliers consumes the highest salary budget among teams. C contribute the highest total salary among all positions.

Correlation: Age vs Salary Correlation: ~0.21. Conclusion: No significant relationship between employee age and salary.

# 📦 Dataset Info

Rows: 458
Columns: 9
Fields may include: Name, Age, Height, Team, Position, Salary, etc.

# ✅ Tools & Libraries Used

Python
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook

# 📌 Notes

Data privacy and realism were maintained using synthetic adjustments (e.g., randomized heights).
The project is designed as a foundational data analytics exercise, reinforcing skills in cleaning, analysis, and visualization.
