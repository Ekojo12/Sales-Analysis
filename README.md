# Sales-Analysis

## Outline
## [Project Overview](#project-overview)
## [Data Sources](#data-sources)
## [Tools Used](#tools-used)
## [Data Cleaning and Preparation](#data-cleaning-and-preparation)
## [Exploratory Data Analysis](#exploratory-data-analysis)
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
Dataset has 14 columns and 1000 rows.

### Tools Used
---
- MS Excel
    1. This is the major tool used for analysis
- Power BI
    1. This is the major tool used for data tranformation and visualization.
 
### Data Cleaning and Preparation
---

I expanded columns and checked for duplicates.
I removed blank rows.
I added two extra columns;
- Payment Method
- Customer Segment

### Exploratory Data Analysis
---
EDA Checklist:
1. Summary Statistics: Understand basic metrics (sum, max, count).
2. Visualizations: Use charts (bar charts, area graphs, pie charts, line graphs to visually explore data.
3. Categorical Data: Summarize and visualize categorical variables.

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
From the data shared and the charts created;
1. The sum of revenue in the different regions was analysed which amounted to 1.3M

2. Category of Products;
   - Electronics
   - Accessories
   - Wearables
     
3. Regions;
   - North
   - South
   - East
   - West

4. Payment Method
   - Paypal
   - Payment on Delivery
   - Credit Card
  
#### Business Decisions
---
1. Unique Regional Strategies: A region-specific strategy can be adopted. High-performing regions (e.g., North East) made great revenue, while regions (e.g., the North-Central) had low revenue. This strategy can enable all regions to be equally focsed on.

2. Capitalizing on the Day Category: From the charts, we analysed that the Work day had the highest number markets and the Local holiday had the least, this implies the work day will have higher revenue.

#### Key Points:
1. Understanding regional performance and adapting strategies to specific stores can unlock hidden growth potential.
2. Understanding the seasons i.e the day category can drive customer engagement and maximize revenue.

#### Problem Statement
Revenue generation is a core part of any business. This generation is influenced by a number of factors, which include the regions, customer segment, etc. There have been issues about revenue generation in the company by region, where certain regions were generating income than others. This analysis provides insight to solve the issue with respect to customer segment and its effect on the revenue. 

#### Recommendations
By leveraging data on regions, markets, stores, day category, we can see the result in the charts.
Understanding the data can lead to higher revenue generation across regions.

![image](https://github.com/user-attachments/assets/b6142c92-2211-419a-8e80-91edfc45d099)


![image](https://github.com/user-attachments/assets/e5c8c24f-3015-4940-802b-e5b88df93066)


![image](https://github.com/user-attachments/assets/e315d8ce-5f45-4e10-b2fe-9f1a5a1651b4)


