# Retail Sales Data Analyzer

## Project Objective
A Python-based Retail Sales Data Analyzer that loads a CSV dataset, validates and cleans data, calculates sales metrics, filters records, and creates visualizations.

## Technologies Used
- Python
- Control Structures and Arrays
- OOP / Class and Methods
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Files
- `retail_analyzer.py` - main Python program
- `retail_sales.csv` - sample dataset
- `README.md` - setup and project explanation

## Dataset Columns
- Date (YYYY-MM-DD)
- Product
- Category
- Price
- Quantity Sold
- Total Sales

## OOP Methods
`RetailAnalyzer` contains:
- `load_data(self, file_path)`
- `calculate_metrics(self)`
- `filter_data(self, condition)`
- `display_summary(self)`
- `create_visualizations(self)`

## How to Run

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn
```

Run:

```bash
python retail_analyzer.py
```

Press Enter when asked for the CSV path to use the included `retail_sales.csv`.

## Features
1. CSV input validation
2. Missing/invalid data handling
3. Total sales calculation
4. Average sales calculation
5. Most popular product
6. NumPy growth-rate calculation
7. Category filtering
8. Date-range filtering
9. Bar chart
10. Line graph
11. Correlation heatmap

## Example Workflow
1. Enter CSV file path.
2. Program validates the file.
3. Pandas loads and cleans the dataset.
4. Metrics are calculated using Pandas and NumPy.
5. User can filter by category/date.
6. User can view graphs.
