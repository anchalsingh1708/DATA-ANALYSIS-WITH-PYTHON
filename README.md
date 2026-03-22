DATA-ANALYSIS-WITH-PYTHON
I will be uploading all my Projects and the Practice that I do in Python here.

📁 Contents
🔢 NumPy Practice — Numpy_Prac.ipynb
Essential NumPy operations used in data analysis and scientific computing.
Core Concepts

Creating arrays using array, linspace, arange, ones, zeros, logspace
Random number generation with np.random.rand
Execution speed with timeit and memory usage with sys.getsizeof, itemsize

Array Manipulation

Reshaping arrays with reshape()
Accessing elements, slicing rows/columns, and creating subsets
Broadcasting and arithmetic operations (add, subtract, multiply, divide, remainder)
Summation along axes

Modifying Arrays

Updating values through slicing
Using transpose()
Appending and inserting rows/columns with np.append() and np.insert()
💡 Key insight: modifying a subset automatically updates the original array


🐼 Pandas Practice — Pandas_Prac.ipynb
Data cleaning and manipulation using Pandas on real-world datasets (Salary data & Toyota car data).
Data Types & Conversion

Checking dtypes with data.dtypes and data.info()
Converting types with astype() — object, int, category
category dtype for memory efficiency (e.g. FuelType: 11488 bytes → 1460 bytes)

Data Cleaning

Handling inconsistent entries with replace()
Fixing mixed string/int columns (e.g. Doors: 'three' → 3)
Handling missing values with fillna() and isnull().sum()
Using na_values in read_csv() to catch ?? and ???? as NaN

Extracting Data from Word Documents

Reading .docx tables using python-docx
Loading table data into DataFrames using inline list comprehension
Splitting, transposing, and fixing headers for clean DataFrames

GroupBy & Lambda

Aggregating data with groupby() and mean()
Writing inline transformations using lambda functions


🛠 Tools & Libraries Used
NumPy · Pandas · python-docx

📌 About
This repo is part of my ongoing journey in Data Analysis with Python. Each notebook covers hands-on practice with real datasets and real bugs — learning by doing.
