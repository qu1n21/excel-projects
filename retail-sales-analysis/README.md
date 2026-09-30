# Retail Sales Dataset Analysis

## Project Overview
This project used Excel to prepare, analyse and visualise a retail sales dataset. 

## Skills Demonstrated
- Date functions
- Logical functions and calcluations (IF, IFS, SUMIFS, AVERAGEIF)
- Lookup functions (VLOOKUP)
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- IF Functions
- SUMIFS

## Dataset
The raw dataset can be found in `retail_sales_dataset_raw.xlsx`

The analysis of the data set can be found in `retail_sales_dataset_analysis.xlsx`

## Data Preperation

### Duplicate checks
The dataset was checked for duplicate records before analysis

### Data Transformation
Year values were extracted from transaction dates, allowing for the calculation of year-specific commisions.

### Generation Classification
Customers were categorised into age groups (Young Adult, Adult and Senior) using an IFS function.
```
=IFS([@Age]<30, "Young Adult", [@Age]>50, "Senior", [@Age]>= 30, "Adult")
```
## Analysis

Using UNIQUE, i dentified each individual catehory. Using SUMIFS, I summarised total sales and then quantity separated by by gender.

### Sales Summary Analysis
To gain further insights, I broke the data down further. Using SUMIFS, total sales and quantities were analysed by:
- Gender
- Generation
- Product Category


## Skills Demonstrated
This project highlights: 
- Data preparation
- Sales analysis
- Commission calculations
- Pivot table reporting
- Data visualisation
