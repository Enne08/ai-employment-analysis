# AI Employment Analysis (USA, May 2023)

Visualising U.S. employment and wages in AI, data science and software development jobs,
using the BLS Occupational Employment and Wage Statistics (OEWS) data.

## How to run
1. Download the **May 2023 "All data"** file from https://www.bls.gov/oes/tables.htm
2. Unzip it and put `all_data_M_2023.xlsx` in the `data/` folder
3. Open `ai_employment_analysis.ipynb` in Jupyter and run all cells

The raw Excel file is not in this repo because of its size. The smaller filtered CSVs in
`data/processed/` are created by the notebook.

## Requirements
`pandas`, `numpy`, `matplotlib`, `seaborn`, `openpyxl`
