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

## Dataset
The raw dataset can be found in `retail_sales_dataset_raw.xlsx`

The analysis of the data set can be found in `retail_sales_dataset_analysis.xlsx`

## Data Preperation

### Duplicate checks
The dataset was checked for duplicate records before analysis.

### Data Transformation
Year values were extracted from transaction dates, allowing for the calculation of year-specific commisions.

### Generation Classification
Customers were categorised into age groups (Young Adult, Adult and Senior) using an IFS function.
```
=IFS([@Age]<30, "Young Adult", [@Age]>50, "Senior", [@Age]>= 30, "Adult")
```
## Analysis

Using UNIQUE, identified each individual category. SUMIFS was then used to summarised total sales as well as quantity separated by gender.
!

### Sales Summary Analysis

To gain further insights, the data was broken down further. Using SUMIFS, total sales and quantities were analysed by:
- Gender
- Generation
- Product Category
!

### Pivot Table Analysis

A pivot table was created to summarised the same sales and quantities metrics.
!

### Interactive Sales Analysis Report

Pivot tables, pivot charts and slicers were used to create an interactive sales report analysing generations, genders and categories
!

### Transactions

VLOOKUP was used to find the total sales and the category of selected transactions using transaction IDs.
!

## Skills Demonstrated
This project highlights: 
- Data preparation
- Sales analysis
- Commission calculations
- Pivot table reporting
- Data visualisation
