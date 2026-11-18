
# E-Commerce Dataset Cleaning

## WeIntern Data Science Internship – Week 1

### 1. Project Overview

This project focuses on cleaning and preparing the Brazilian Olist E-Commerce dataset as part of the WeIntern Data Science Internship – Week 1 assignment.

The main objective is to inspect raw datasets, identify data quality issues, handle missing values, detect duplicates, perform data validation, and prepare clean datasets for further analysis.

### 2. Task Objectives

- Understand the structure of the datasets.
- Inspect rows, columns, and data types.
- Identify and analyze missing values.
- Detect and investigate duplicate records.
- Perform data validation checks.
- Apply appropriate data cleaning techniques.
- Export cleaned datasets.
- Document cleaning decisions and results.

### 3. Dataset Description

The project uses nine CSV datasets:

1. Customers
2. Geolocation
3. Order Items
4. Order Payments
5. Order Reviews
6. Orders
7. Products
8. Sellers
9. Product Category Translation

### 4. Data Cleaning Process

The following steps were performed:

1. Imported the required Python libraries.
2. Loaded all nine raw datasets.
3. Inspected dataset dimensions and data types.
4. Analyzed missing values.
5. Identified duplicate records.
6. Performed data validation checks.
7. Applied appropriate missing value treatment.
8. Removed confirmed duplicate records.
9. Exported cleaned datasets.
10. Generated cleaning and validation reports.

### 5. Cleaning Outputs

The following reports were generated:

- dataset_overview.csv
- missing_values_report.csv
- duplicate_analysis.csv
- data_validation_report.csv
- cleaning_decisions.csv
- cleaning_summary.csv

### 6. Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

### 7. Project Structure

```text
Task-1_Data-Cleanning/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebook/
│   └── task1_data_cleaning.ipynb
│
├── outputs/
│   └── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

### 8. How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_TASK1_GITHUB_REPOSITORY_URL
```

**Step 2:** Navigate to the project directory.

```bash
cd Task-1_Data-Cleanning
```

**Step 3:** Install the dependencies.

```bash
pip install -r requirements.txt
```

**Step 4:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open and execute:

`notebook/task1_data_cleaning.ipynb`

### 9. Expected Deliverables

- Raw dataset inspection summary
- Missing value report
- Duplicate analysis
- Data validation report
- Cleaned datasets
- Cleaning decisions documentation

### 10. Author

**Gaurav Varat**

WeIntern Data Science Internship – Week 1

### 11. Conclusion

This task demonstrates practical skills in data inspection, data quality assessment, missing value treatment, duplicate detection, data validation, and data preprocessing.

