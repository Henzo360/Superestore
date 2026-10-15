# Superstore Data Cleaning

## Project overview

This project uses Python and pandas to profile the Sample Superstore dataset, inspect missing values, identify exact duplicate rows, remove duplicates, and export a cleaned CSV for further analysis. The repository also includes notebook markdown references to Power BI dashboard screenshots from the original project.

## Tools

- Python
- pandas
- Jupyter Notebook
- Power BI (dashboard work referenced in the notebook)

## Repository contents

- `SampleStore .ipynb` — data inspection, missing-value checks, duplicate handling, and CSV export.
- `requirements.txt` — Python dependencies.
- `data/` — expected location for the source CSV, which is not included in this repository.
- `output/` — generated cleaned CSV, created when the notebook runs.

## Workflow

1. Load the source CSV from a project-relative path.
2. Inspect sample rows, dimensions, data types, and non-null counts.
3. Report missing values by column.
4. Count and display exact duplicate rows.
5. Remove exact duplicates and report the before/after row counts.
6. Export the cleaned dataset to `output/sample_superstore_cleaned.csv`.

## How to run

1. Install dependencies with `python -m pip install -r requirements.txt`.
2. Create a `data` folder beside the notebook and place the source file there as `SampleSuperstore.csv`.
3. Open `SampleStore .ipynb` in Jupyter and run cells from top to bottom.

## Data-quality notes

- Exact duplicate removal does not guarantee that every record is correct or that all missing values should be removed.
- Missing values are reported but are not automatically imputed or dropped.
- The source dataset is not included in this repository, so the full workflow requires a separately obtained copy.

## Author

Henry Odionye
