# School District Project: Educational Data Aggregation and Visualization

## Introduction

This Project is designed to aggregate, format, and visually present key educational data from Cleveland Municipal School District across three academic years. The goal is to provide a cohesive and analytical view of school achievement and growth, facilitating insightful discussions and presentations.

## Goals

1. **Dataset Goal**: Aggregate and format key educational data for Cleveland Municipal district schools across three academic years into a single, coherent file.
2. **Visual Goal**: Develop a visual representation that clearly illustrates changes in school achievement and growth over three years, tailored for presentation and analytical discussions.

## Methodology

### Data Collection

- Data was downloaded from the Ohio Department of Education's 'Report Card' website.

### Data Processing and Analysis

- **Python and Jupyter**: Utilized for initial data upload and quick visual analysis. Pandas was employed for its powerful data manipulation capabilities, allowing for the shaping of datasets as required. Relevant Python scripts, alongside documentation on column names and steps taken, are included.
- **Excel**: Post-Jupyter, datasets were transferred to Excel for detailed manipulation. This included confirming data consistency, data type formatting, duplication removal, adding 'Schoolyear' columns, and consolidating metadata. The process across each Excel sheet is documented, with each sheet's name reflecting the specific cleaning step performed.

### Visualization

- **Power BI**: The final CSV file was imported into Power BI to create a visual dashboard. This dashboard showcases changes in CMSD schools' performance, focusing on Performance Index Percent, Enrollment, and Overall Value Added Grade over the three years. Slicers were implemented for detailed analysis, from a broad district-wide view to specific buildings or years.

## Project Structure

The project is organized into three main folders:

1. **Data Cleaning**: Contains materials related to the Python code used for initial data handling.
2. **Excel Processing**: Includes the Excel file, with each sheet named according to the cleaning step it represents.
3. **Power BI Visualization**: Holds materials for the data visualization component, including project files and PDFs.
