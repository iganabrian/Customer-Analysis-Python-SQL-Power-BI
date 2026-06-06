# A Retail Store Sales Data Analysis 

This project aimas at answering two features of this sales data. 

1. Business Revenue
2. Customer Segmentation

## Dashboard

<img src="./Store Sales Dashboard.png">

## Tools used
- Python
- SQL (Postgres)
- Power BI 

## Python (Pandas) 

I loaded the dataset into Anaconda's Jupyter Notebook for:

-Data Cleaning

- Here, I filled null values with the median value per store item i.e shirt, dress etc.

- Removed duplicates. 

-Data Enrichment:

- This involved adding a new column that segmented the customers by age groups (Senior, Adult, Middle-Aged and Young-Adult) 

## SQL (Postgres)

-Connected the data with my Local Postgres for Analysis where I answered Business questions that formed the baseline for KPIs.

1. Revenue;
2. Total Number Customers; 
3. Average age of Customers; and
4. Number of Items in the store.

<img src="SQL Revenue by gender.png">
## Power BI Analysis and Visualisation

I connected my Postgres Database with Power BI for visualisation. 

Here:

- Dax Measures
- I created customized KPIs
- Customized BarCharts 

## Conclusions

- The business generated a revenue of 233k from 4k customers whose average age is 44 from a distinct 25 items. 

- Segmentating the store's items sales helped me realise that Clothing gebnerates more revenue in the store followed by footwear. 

- Customer segmentation by Age group reveled that Senior members of the society are the biggest buyers of items.