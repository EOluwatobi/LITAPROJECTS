# LITAPROJECTS

[Project Overview](#data-analysis)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and preparations](data-cleaning-and-preparation)

[Exploratory Data Analysis](exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](data-visualization)

[Discussion and Conclusion](discussion-and-conclusion)


## Project Overview
---
This project is aim at analysing the sales report of a business operating in 6 different region and having different stores operating under it also at different markets. Their line of business includes copier sales, parts, service plan and printer sale. In this reports, several insights will be generated to determine the revenue generated in all the makets operating under the 6 regions, know the top selling region/market, the top selling product, the least selling region/market, the leaset selling product e.t.c. This report will help in making reasonable and profiting business decision to further improves sales in the business

## Data Sources
---
The primary source of data is from online tutorials such as Youtube and other csv files downloaded from Kaggle.

## Tools Used
---
- Microsoft Excel [download Here](https://www.microsoft.com)
   1. For Data Cleaning 
   2. For data analysis 
   3. For Looking up values
   4. For creating pivot tables
   5. For visualization
      
- SQL- Structured querying Language
   1. for data querying using SQL keys and commands
  
- Powerbi
   1. For data visualization
   2. For Building reports

## Data Cleaning and Preparations
---
In the initial phase of the data cleaning and preparations, the following actions were performed:
- Data loading and inspection
- Handling missing variables
- Data cleaning and formatting

## Exploratory Data Analysis
---
 EDA involves exploring of the data to provide answers to some questions about the data such as:
 - What is the total revenue of sales by region?
 - What line of business has the highest sales?
 - What 5 market has the top sales? 

## Data analysis
---
Here, some basic lines of code or queries or even some of the DAX expressions were used during analysis:

```SQL
SELECT * FROM SALESTABLE
AVERAGE_REVENUE = TOTAL_REVENUE / UNITSOLD
```

## Data Visualization
![excel file](https://github.com/user-attachments/assets/1915a170-6966-4aaf-b8e4-7f07cf938d9e)

---

![sales by R](https://github.com/user-attachments/assets/949ec338-f05c-4725-a02f-d86c5ab219a9)

---
![line of business](https://github.com/user-attachments/assets/f6db6819-4581-4409-aaff-924317a96f9c)

![top 5 markets](https://github.com/user-attachments/assets/a78415ae-4165-4b34-8adb-db6be4b8770b)

---
- ![Charts](https://github.com/user-attachments/assets/c7c282a9-f803-4dac-bce0-55482dd11fe2)

---
- ![SQL Queries](https://github.com/user-attachments/assets/b021af7d-e847-4a80-9a80-9f50be183435)

  ## Discussion and Conclusion
  From our analysis, we are able to see that:
     1. In all the 6 regions, North East has the highest revenue generated. Hence, to further maintain/increase profit, determine what product sells more in that region and at what period, thereby making available more of this product for customers
     2. The Service Plan product generates more revenue for the business with a sum of 51,866,481,960.00. Hence, more of this product should be available on the shelve for customers
     3. Amongst all the markets across the Regions, Ekiti has the highest sales of all products with the sum of 5,574,169,800. Followed closely is Abia, Bayelsa, Awka ibom and Kogi.
