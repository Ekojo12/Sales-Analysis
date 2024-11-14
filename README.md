# Sales-Analysis

## Outline
## [Project Overview](#project-overview)
## [Data Sources](#data-sources)
## [Data Cleaning and Preparation](#data-cleaning-and-preparation)
## [Data Analysis](#data-analysis)
## [Results/Insights](#Results/Insights)

### Project Overview
---
A Data Analysis project;

1. Clean and Prepare the data
2. Create visuals from the data.
3. Document your step by step analysis from the Data given.

### Data Sources
---
The data used for this project was downloaded from Kaggle.
- https://www.kaggle.com/datasets/brsahan/e-commerce-dataset/data

### Data Cleaning and Preparation
---
-I expanded columns and checked for duplicates.
-I removed blank rows.
I added two extra columns;
1. Payment Method
2. Customer Segment

### Data Analysis
---
This was used to calculate the Total Customers; 
-A calculated Column in Power BI
```
TotalCustomers = DISTINCTCOUNT(Sales[CustomerID])
```

Excel Function; To fill cells randomly.
This function created the columns; Payment Method and Customer Segment
```
=IF(M2 = "", INDEX($M$2:$M$10, RANDBETWEEN(1, COUNTA($M$2:$GM$10))), M2)
```

### Results/Insights
---
This has been documented in the Report Uploaded.


