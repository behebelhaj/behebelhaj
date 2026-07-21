# Employee Data Cleaning 🧹

## About
Real-world messy HR employee dataset cleaned using Python and Pandas.
This project simulates the kind of data cleaning tasks performed daily
by data analysts in banking and finance environments.

## Problems found in the original data
- ❌ Negative phone numbers (impossible in real life)
- ❌ Department and Region mixed in one column
- ❌ Join Date stored as text not as a real date
- ❌ 211 missing Age values
- ❌ 24 missing Salary values

## What I did to fix it
- ✅ Converted negative phone numbers to positive using abs()
- ✅ Split Department_Region into two clean columns
- ✅ Converted Join_Date to proper datetime format
- ✅ Filled missing Age and Salary with median values
- ✅ Exported clean dataset to new CSV

## Key findings
- Sales department has the highest average salary
- Good performers earn slightly more than Excellent performers
- Interesting compensation structure worth investigating

## Files
- `Messy_Employee_dataset.csv` — original messy data
- `employees_cleaned.csv` — cleaned version
- Notebook — full cleaning process step by step

## Technologies
- Python
- Pandas
- Google Colab

## Author
[behe belhaj] — Informatique de Gestion Student
Building toward a Data Science career in banking and finance 🎯
