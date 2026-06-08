# E-Library Data Insights Dashboard

## Project Overview
The E-Library Data Insights Dashboard is a Python-based project developed to analyze and visualize library transaction data. The project uses OOP concepts, NumPy, Pandas, Matplotlib, and Seaborn to generate meaningful insights from library borrowing records.

## Objective
To manage and analyze book borrowing trends and provide insights such as:
- Most borrowed books
- Average borrowing duration
- Busiest borrowing day
- Genre-wise analysis
- Data visualizations

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset Columns
The project uses a CSV file named `library_transactions.csv` containing:

- Transaction ID
- Date
- User ID
- Book Title
- Genre
- Borrowing Duration (Days)

## Features

### 1. Data Validation
- Reads CSV file
- Checks required columns
- Removes missing values
- Removes duplicate records

### 2. OOP Implementation
A class named `LibraryDashboard` is used with the following methods:
- `load_data()`
- `calculate_statistics()`
- `filter_transactions()`
- `generate_report()`
- `create_visualizations()`

### 3. Statistical Analysis
- Total Transactions
- Most Borrowed Book
- Average Borrowing Duration
- Busiest Day

### 4. Filtering
Users can filter records by Genre.

### 5. Data Visualization
The project generates:
- Bar Chart
- Line Graph
- Pie Chart
- Heatmap

## Control Structures Used
- if
- elif
- else
- for loop
- while loop

## How to Run

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
