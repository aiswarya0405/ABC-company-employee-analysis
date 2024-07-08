# ABC Company Employee Data Analysis

## Project Overview

This project analyzes the employee data of ABC Company. The dataset includes information such as team, position, age, height, weight, college, and salary. The goal is to uncover key trends and patterns within the dataset.

## Preprocessing Steps

1. **Loading the Dataset**:
   - I have loaded the dataset from an Excel file using the pandas library.

2. **Fixing Data**:
   - I fixed the "Height" column by replacing it with random numbers between 150 and 180 to ensure the data was consistent.

## Analysis Tasks

### Task 1: Employee Distribution by Team

- **Goal**: Find out how many employees are in each team and what percentage they represent.
- **Method**: Count the employees in each team and calculate the percentage.
- **Visualization**: Bar chart showing the number of employees in each team.

### Task 2: Employee Distribution by Position

- **Goal**: Find out how employees are distributed by their positions.
- **Method**: Count the employees in each position.
- **Visualization**: Pie chart showing the distribution of employees by position.

### Task 3: Predominant Age Group

- **Goal**: Identify the most common age group among employees.
- **Method**: Group employees by age ranges and count the number in each range.
- **Visualization**: Bar chart showing the number of employees in each age group.

### Task 4: Highest Salary Expenditure

- **Goal**: Find out which team and position have the highest salary costs.
- **Method**: Sum up the salaries for each team and position.
- **Visualization**: Bar charts showing the total salary expenditure by team and by position.

### Task 5: Age and Salary Correlation

- **Goal**: See if there is a relationship between age and salary.
- **Method**: Calculate the correlation between age and salary.
- **Visualization**: Scatter plot showing the relationship between age and salary.

## Visualizations

I created the following charts to present my findings:

1. **Team Distribution**: Bar chart showing the number of employees in each team.
2. **Position Distribution**: Pie chart showing the distribution of employees by position.
3. **Age Group Distribution**: Bar chart showing the number of employees in each age group.
4. **Salary Expenditure by Team**: Bar chart showing total salary costs by team.
5. **Salary Expenditure by Position**: Bar chart showing total salary costs by position.
6. **Age vs. Salary**: Scatter plot showing the relationship between age and salary.

## Key Insights

1. **Employee Distribution**:
   - The "Boston Celtics" team has the most employees.
   - Common positions include "SG" (Shooting Guard) and "PF" (Power Forward).

2. **Age Group**:
   - Most employees are aged 25-30.

3. **Salary Expenditure**:
   - The "Boston Celtics" team and the "PG" (Point Guard) position have the highest salaries.

4. **Age and Salary**:
   - Older employees tend to have higher salaries.

## Recommendations

1. **Resource Allocation**: Support larger teams like the "Boston Celtics".
2. **Balanced Recruitment**: Ensure a mix of different positions.
3. **Age-Specific Benefits**: Develop programs for different age groups.
4. **Fair Salaries**: Ensure fair salary structures.
5. **Career Paths**: Create clear career progression paths.

## Dataset

The dataset used for this analysis is included in the repository. You can find the dataset file [here](r'C:\Users\asus\Downloads\myexcel.xlsx').

**File**: `myexcel.xlsx`

This dataset contains information about the employees of ABC Company, including their team, position, age, height, weight, college, and salary.

### Loading the Dataset

In the Jupyter Notebook, you can load the dataset using the following code:

```python
import pandas as pd

# Load the dataset
df = pd.read_excel(r'C:\Users\asus\Downloads\myexcel.xlsx') 

## Tools Used

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn

## How to Run the Analysis

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/aiswarya0405/ABC-company-employee-analysis.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd abc-company-employee-analysis
   ```

3. **Install the Required Libraries**:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook employee_analysis.ipynb
   ```

5. **Run the Notebook**:
   - Follow the instructions in the notebook to perform the analysis and generate the visualizations.

## Conclusion

This project provides insights into ABC Company's workforce, helping improve HR strategies and financial planning. Implementing the recommendations can lead to better management and employee satisfaction.
