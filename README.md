# 2023GSU_ANA_515P_01-Exp-Practicum-Fundamentals

**Data Cleaning and Analysis in R - README**

This README document provides an overview of the data cleaning and analysis process for the survey dataset on attitudes towards mental health and frequency of mental health disorders in the tech workplace. The dataset is sourced from a 2014 survey.

**Files**
survey.xlsx: The Excel file containing the survey data. It consists of two sheets.
data_cleaning.R: The R script used for data cleaning and preparation.
data_analysis.R: The R script used for data analysis and visualization.
cleaned_survey_data.csv: The cleaned dataset saved in CSV format.

**Data Cleaning**
File Reading: The survey.xlsx file is read using the appropriate R package (e.g., readxl or openxlsx).
Handling Missing Values: Missing values are identified and handled appropriately, either by imputation or exclusion, based on the specific context and variables.
Spelling Errors: Spelling errors in text columns are identified and corrected using manual or automated methods, such as string matching or approximate string matching algorithms.
Data Type Conversion: Columns with incorrect data types are converted to their appropriate types, such as converting dates to DateTime objects, converting strings to factors, or converting numeric values to integers.
Outliers: Outliers are identified and handled based on domain knowledge and the specific requirements of the analysis. Outliers may be removed, winsorized, or treated using other appropriate methods.
Data Transformation: If necessary, data transformation techniques like scaling, normalization, or log transformations are applied to improve data distribution or meet modeling assumptions.
Data Integrity Checks: Data integrity is ensured by checking for any inconsistencies, duplication, or illogical values. Inconsistencies are resolved by validating and verifying the data against known rules or external sources.
Saving Cleaned Data: The cleaned dataset is saved in a separate file, cleaned_survey_data.csv, in a widely compatible format like CSV, which can be used for further analysis.

**Data Analysis**

Combining Data: If multiple data files are available, they are combined into one dataset to facilitate analysis.
Descriptive Analysis: Descriptive statistics, such as measures of central tendency, variability, and frequency distributions, are computed to summarize the dataset.
Visualization: Visualizations, such as histograms, boxplots, or graphs, are created to gain insights into the distribution, relationships, and patterns within the variables.
Statistical Analysis: Statistical techniques, such as hypothesis testing, regression analysis, or clustering, are applied to explore relationships, identify significant factors, or draw conclusions based on the research questions or objectives.
Interpretation and Reporting: The findings from the analysis are interpreted and summarized in a clear and concise manner, accompanied by appropriate visualizations, tables, or charts. Conclusions are drawn and any limitations or assumptions are mentioned.

**Dependencies**
The following R packages were used in the data cleaning and analysis process:

readxl: For reading Excel files.
openxlsx: For reading and manipulating Excel files.
Other packages as required for specific cleaning, analysis, and visualization tasks.
Ensure that these packages are installed to execute the provided scripts.

**Usage**
Download the survey.xlsx file and place it in the appropriate directory.
Execute the data_cleaning.R script to clean the data and save the cleaned dataset.
Execute the data_analysis.R script to perform the analysis and generate visualizations.
Refer to the output and generated files for the cleaned dataset, analysis results, and visualizations.
