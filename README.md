README: LI_Data_Task
────────────────────────────────────────
Folder Structure and Contents
────────────────────────────────────────

1. clean_data/
   └── clean_balanced_panel.csv
       - A cleaned and balanced panel dataset for the academic years 2010–2015.
       - Includes institutional information, enrollment, and federal grant aid variables.
       - Used in all final analyses and figures in the policy memo.

2. code/
   └── SY_data_task.ipynb
       - The Jupyter Notebook containing all Python code for data cleaning, merging, analysis, simulation, and figure generation.
       - Code is organized by section (loading, cleaning, merging, analysis for Question A–C).

3. raw_data/
   ├── hd2010.csv to hd2015.csv
       - Institutional "Directory Information" files for 2010–2015 (IPEDS Institutional Characteristics).
       - Used to extract state, control, and degree-granting status.

   ├── sfa1011.csv to sfa1516.csv
       - Student Financial Aid and Net Price files for 2010–2015.
       - Used to compute per-student federal grant aid and enrollment.

4. Data_Task.pdf
   - Final policy memo submitted to ED.
   - Includes summary of findings for all questions (A–C) and all figures at the end.

────────────────────────────────────────
Instructions
────────────────────────────────────────

- To reproduce results, start by opening `SY_data_task.ipynb` in a Python 3 environment.
- All raw data should be stored in `raw_data/`, and output will be saved to `clean_data/`.
- Figures are generated within the notebook and exported if needed.

────────────────────────────────────────
