[README_data_analyst_three.md](https://github.com/user-attachments/files/33962612/README_data_analyst_three.md)
# data_anlyst-three-
THIS IS PROJECT OF DATA ANLYST .
# Employee and Manufacturing Data Analysis

This project explores sample employee and manufacturing-related data using Python visualizations. It examines employee demographics, departments, shifts, salary and expenses, performance, production, and profit.

## Project Overview

The notebook generates a sample dataset of 600 records with NumPy and Pandas. It then uses Matplotlib and Seaborn to visualize different aspects of the workforce and business operations.

## Dataset

The dataset is generated inside the notebook with a fixed random seed (`42`), so no external CSV file is required. It includes fields such as:

- Employee ID and name
- City, department, shift, and job title
- Age, base salary, and bonus
- Overtime hours and food expense
- Performance score and monthly sales target
- Raw material and finished-goods quantities
- Gross revenue, electricity bill, transport cost, net profit, and tax deducted

The values are randomly generated for demonstration and do not represent verified employee or company records.

## Analysis Included

- Basic dataset preview and structure
- Relationship between base salary and bonus
- Food expenses by city
- Employee distribution by city and job title
- Age distribution
- Performance score by city
- Monthly sales target by department and shift
- Overtime hours by age group and shift
- Net profit distribution by shift
- Pairwise comparisons of selected numeric and shift-related fields
- Relationship between food expense and overtime hours

## Libraries Used

- **NumPy** — generating sample data and numerical operations
- **Pandas** — data handling and analysis
- **Matplotlib** — charts and plots
- **Seaborn** — statistical visualizations

## Installation

Install the required libraries:

```bash
python -m pip install numpy pandas matplotlib seaborn notebook
```

## How to Run

1. Download or clone the repository.
2. Install the required libraries.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the notebook and run the cells in order.

## Purpose

This project is intended to practice exploratory data analysis (EDA), grouping, and visualization using employee and operational-style data.

## Note

The notebook uses generated sample data. Some chart titles or labels may be informal or not perfectly aligned with the plotted variables; review them before presenting the project professionally.
