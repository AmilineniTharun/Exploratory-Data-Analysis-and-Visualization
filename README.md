# Week 2: Exploratory Data Analysis and Visualization

## Project Overview
This project explores the Titanic passenger dataset using Python. The objective is to understand the dataset, identify missing values, analyze passenger characteristics, and visualize patterns related to survival.

## Dataset
- **Dataset:** Titanic passenger dataset
- **Rows:** 891
- **Columns:** 15
- **Main variables:** Survival, passenger class, sex, age, fare, family information, and embarkation port.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Tasks
1. Load and inspect the Titanic dataset.
2. Examine data types and descriptive statistics.
3. Identify missing values and duplicate records.
4. Analyze passenger age and fare distributions.
5. Compare survival rates by sex and passenger class.
6. Create a correlation heatmap.
7. Analyze survival rates by family size and embarkation port.
8. Save charts and summary files for reporting.

## Visualizations
The project includes the following charts:
- Age Distribution
- Fare Distribution
- Survival Rate by Sex
- Survival Rate by Passenger Class
- Correlation Heatmap
- Survival Rate by Family Size
- Survival Rate by Embarkation Port

## Key Findings
- The overall survival rate was approximately 38.4%.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Age and deck information contained missing values.
- Fare values were right-skewed, with some passengers paying considerably higher fares.
- Survival rates varied across family sizes and embarkation ports.

## Project Files
- `Week2_EDA_Titanic.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- `raw_titanic.csv` — Dataset used for analysis.
- `descriptive_statistics.csv` — Descriptive statistics.
- `missing_values.csv` — Missing-value summary.
- `eda_summary.json` — Summary of analysis results.
- `outputs/` — Folder for saved charts, if configured in the notebook.
- `Week2_EDA_Report.docx` — Written report describing the methodology and findings.

## How to Run
1. Open the project in Jupyter Notebook.
2. Install the required libraries if necessary:
   `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `Week2_EDA_Titanic.ipynb`.
4. Run the notebook cells from top to bottom.
5. Check the generated charts and exported summary files.

## Conclusion
This project demonstrates practical skills in data inspection, data quality assessment, exploratory data analysis, visualization, and interpretation using Python. The results provide an overview of the Titanic passenger dataset and show how passenger characteristics were associated with observed survival rates.

## Limitations
The analysis is descriptive. Missing data and differences between passenger groups may affect the results. Observed relationships do not establish causation.
