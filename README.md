# Page-View-Time-Series-Visualizer
# Time Series Visualizer

This project visualizes time series data using **Python, Pandas, Matplotlib, and Seaborn**.  
It is part of the **freeCodeCamp Data Analysis with Python Certification**.

The dataset contains daily page view counts for the freeCodeCamp forum from May 2016 to December 2019.  
The goal is to clean the data, analyze trends, and visualize patterns over time.

---

## Dataset

- **File:** `fcc-forum-pageviews.csv`
- **Source:** freeCodeCamp
- **Columns:**
  - `date` – date of observation
  - `value` – number of forum page views

The `date` column is parsed as a datetime index to enable time series analysis.

---

## Project Tasks

### 1. Data Cleaning
- Removed outliers by excluding days in the top 2.5% and bottom 2.5% of page views.
- This keeps the central 95% of the data for clearer trend analysis.

### 2. Line Plot
- Displays daily forum page views over time.
- Shows the overall trend from May 2016 to December 2019.

### 3. Bar Plot
- Shows **average daily page views per month**, grouped by year.
- Helps compare monthly trends across different years.
- Months are displayed in correct calendar order.

### 4. Box Plots
- **Year-wise box plot:** shows distribution and trends across years.
- **Month-wise box plot:** shows seasonal patterns across months.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- unittest (for automated testing)

---

## Project Structure
```
time-series-visualizer/
├── time_series_visualizer.py # Main analysis and plotting logic
├── main.py # Local test runner
├── test_module.py # Unit tests (provided by FCC)
├── fcc-forum-pageviews.csv # Dataset
└── README.md
```
