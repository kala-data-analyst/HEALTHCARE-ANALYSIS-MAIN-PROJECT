Project Title
Healthcare Analytics and Hospital Operations Intelligence Using Python and Power BI
Description
This project focuses on analyzing healthcare and hospital operational data to identify important patterns, performance gaps, and areas for improvement. Python is used for data cleaning, preprocessing, validation, exploratory data analysis, and visualizations, while Power BI is used for data modelling, DAX calculations, KPI analysis, interactive visualizations, and dashboard development. The project analyses patient demographics, admission patterns, health conditions, clinical severity, departmental workload, staff availability, room availability, visitors, admission deposits, and length of stay. Interactive dashboards provide hospital administrators with a consolidated view of operational indicators and support data-driven planning related to staffing, resources, workload management, and performance monitoring
Getting Started
The project can be reproduced using the Python/Google Colab environment for preprocessing and exploratory analysis and Microsoft Power BI Desktop for data modelling, DAX calculations, visualization, and interactive dashboard development.
Dependencies
Windows operating system (for Power BI Desktop use).
Google Colab or Jupyter Notebook.
Python 3 environment.
Pandas for data manipulation and cleaning.
NumPy for numerical operations.
Matplotlib for visualization.
Seaborn for statistical visualization.
Microsoft Power BI Desktop for data modelling, DAX, KPIs, slicers, filters, drill-down, and dashboards.
Healthcare dataset sourced from Hugging Face Datasets.
Data Source
Source: Hugging Face Datasets
Timeline stated in the project documentation: 2024–2025.
Installing
No standalone software package is being distributed. The analytical workflow is implemented in Google Colab/Jupyter Notebook and Power BI Desktop. The project dataset is loaded into the Python environment for preprocessing and analysis and then used in Power BI for modelling and reporting.
1.Open Google Colab or Jupyter Notebook.
2.Load the healthcare dataset from the project data source.
3.Install/import the required Python libraries if they are not already available.
4.Open Power BI Desktop for the dashboard stage.
5.Load the cleaned dataset into Power BI.
Executing Program
The project workflow is executed in the following stages:
6.Load the healthcare dataset into Python/Google Colab.
7.Inspect the dataset structure and attributes.
8.Remove duplicate records and handle missing values.
9.Standardize formats and convert date fields to appropriate data types.
10.Clean and standardize text fields.
11.Perform skewness checks and detect outliers using the IQR method.
12.Validate the cleaned dataset.
13.Perform exploratory analysis using descriptive, bivariate, and multivariate visualizations.
14.Load the cleaned data into Power BI.
15.Create data-model relationships and lookup tables where necessary.
16.Create calculated columns and DAX measures.
17.Develop interactive dashboard pages using KPI cards, charts, slicers, filters, and drill-down.
18.Review insights and use them to support hospital operational planning.
code blocks for commands
```
* Open the project notebook in Google Colab.
* Load the two-wheeler resale dataset.
* Check and clean missing values and duplicate records.
* Convert columns into suitable data types.
* Standardize text and categorical values.
* Check skewness and detect outliers using the IQR method.
* Handle the identified outliers and validate the final cleaned data.
* Perform descriptive and diagnostic analysis using Python.
* Create charts using Seaborn and Matplotlib.
* Load the cleaned data into Power BI.
* Create KPI cards, charts, and interactive dashboard pages.
* Use the dashboard to understand resale price, resale value, depreciation, and other market patterns.
Help
Common issues can arise from missing or incomplete date values, inconsistent categorical values, duplicate records, or incorrect data types. The following checks are recommended:
If date-based visuals or year slicers show blank values, verify that the Admission Date field contains valid dates and has the correct Date data type.
If calculations appear incorrect, verify the data type of numeric fields and the DAX measure definitions.
If a slicer does not filter a visual as expected, check the table relationships and filter interactions in Power BI.
If duplicate or inconsistent categories appear, review the Python/Power Query cleaning and standardization steps.
If outliers affect numerical analysis, review the IQR-based outlier detection and handling step.
Author

Contributors names and contact info
KALA K
ex. Dominique Pizzie  
not known
LinkedIn  
Profile:
version history
0.1
    * Initial Release
    * Initial project release
    * Python data cleaning and analysis completed
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

 Acknowledgments

- Hugging Face – Dataset source
- Google Colab – Python analysis environment
- Python – Data cleaning, preprocessing, analysis, and visualization
- Pandas – Data manipulation and data cleaning
- NumPy – Numerical computation
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Microsoft Power BI – Data modelling, DAX calculations, visualization, and dashboard development

    
