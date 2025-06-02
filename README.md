
## File Descriptions

### `clean_data/clean_balanced_panel.csv`
- Final cleaned and merged dataset used for analysis.
- Includes institutional characteristics, first-time full-time enrollment, and federal aid information from 2010 to 2015.
- Only includes institutions present in all six years.

### `code/SY_data_task.ipynb`
- Jupyter Notebook with all Python code for:
  - Reading and cleaning raw data
  - Merging files into a balanced panel
  - Computing descriptive statistics
  - Simulating new grant allocation formula
  - Creating figures for the memo

### `raw_data/`
- **hdYYYY.csv**: Directory/Institutional Characteristics data from IPEDS.
- **sfaYYZZ.csv**: Student Financial Aid data from IPEDS for academic years 2010–11 to 2015–16.
- These are the original files downloaded from the IPEDS "Complete Data Files" section.

### `Data_Task.pdf`
- Final policy memo submitted to the Department of Education.
- Contains answers to Questions A, B, and C, including all figures at the end.

## How to Reproduce

1. Open `code/SY_data_task.ipynb` in a Jupyter environment with Python 3.
2. Ensure the folder structure remains unchanged.
3. All output files will be generated and saved to `clean_data/`.

---
