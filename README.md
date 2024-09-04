# Ecommerce Data Analysis using SQL and python

This project demonstrates an eCommerce data analysis workflow using SQL and Python. The analysis includes storing data in a SQL database, retrieving and manipulating it using Python, and visualizing insights using Matplotlib and Seaborn.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Visualization](#analysis-and-visualization)

## Introduction

This project focuses on analyzing eCommerce data, covering data storage, retrieval, and visualization. The data is first stored in a SQL database. Python is then used to connect to the database, execute SQL queries, convert the results into DataFrames, and perform detailed analysis using various Python libraries.

## Technologies Used

- **SQL**: Data storage and query execution.
- **Python**: Data manipulation and analysis.
- **SQL Connector**: For connecting Python to the SQL database.
- **Pandas**: Data manipulation and DataFrame handling.
- **Matplotlib**: Visualization of data trends.
- **Seaborn**: Advanced data visualization.

## Project Structure

```
├── data/
│   ├── ecommerce_data.sql      # SQL script for creating and populating the database
├── notebooks/
│   ├── ecommerce_analysis.ipynb # Jupyter notebook for analysis
├── src/
│   ├── database_connection.py  # Python script for SQL connection
│   ├── analysis.py             # Python script for data analysis and visualization
├── README.md                   # Project README file
└── requirements.txt            # Python dependencies
```

## Installation

1. **Set up the SQL database**:
   - Run the SQL script in the `data/` folder to create and populate the database.

2. **Install the required Python libraries**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Establish a database connection**:
   - Use the `database_connection.py` script to connect to your SQL database. Modify the connection parameters as needed.

2. **Run the analysis**:
   - Execute the Jupyter notebook `ecommerce_analysis.ipynb` or run `analysis.py` to perform the analysis and generate visualizations.

## Analysis and Visualization

- The data analysis includes various SQL queries to extract relevant information, which is then transformed into DataFrames in Python.
- The visualizations are created using Matplotlib and Seaborn, covering different aspects such as sales trends, customer behavior, and product performance.

