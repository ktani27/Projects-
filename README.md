# Franck Tani - Data Analyst Portfolio 
## About 
Hi I 'm Franck. I have a background in Business Admnistration, but I switched to Information technology after falling in love with the power of analytics during my time as an real estate admnistrative assistant. This is when I was introduced to the world of databases and the power SQL. 

Since then, I decided to immerse myself into tech and to become a data analyst. I got one step closer to my goal by  obtaining a master's degree in Management Information Systems with a concentration in project management. 

Now, I have a created this repository to showcase skills, share projects and track my progress in Data analytics/Data engineering related topics. 

## Table of Contents 
- [About](https://github.com/ktani27/Projects-/blob/main/README.md#about)
  
- Python Projects
  
  - [Building a Retail Data Pipeline](https://github.com/ktani27/Projects-/blob/main/README.md#building-a-retail-pipeline)
  - [Cleaning Bank Marketing Campaign Data](https://github.com/ktani27/Projects-/blob/main/README.md#cleaning-bank-marketing-campaign-data)
- SQL Projects
  
  - [Analyzing Industry Carbon Emissions](https://github.com/ktani27/Projects-/blob/main/README.md#analyzing-industry-carbon-emissions)
  - [Analyzing Students Mental Health](https://github.com/ktani27/Projects-/blob/main/README.md#analyzing-students-mental-health) 

## Python Projects 
### Building a Retail Data Pipeline 
**Goal**: Creating a data pipeline for the analysis of Walmart's supply and demand around the holidays.

**Description**: The project focused on building a data pipeline using custom functions to extract, transform, aggregates, and loads e-commerce data. I used the data from the [grocery_sales](https://github.com/ktani27/Projects-/blob/main/assets/Grocery_sales.png) table in PostgreSQL and from the [extra_data](https://github.com/ktani27/Projects-/blob/main/assets/Walmart%20sales%20Extra%20data%20Parquet%20files%20.png) parquet file.   

**Code**: [Building a retail data pipeline](https://github.com/ktani27/Projects-/blob/main/assets/Building%20a%20retail%20data%20pipeline%20notebook.ipynb) 

**Skills**: Data cleaning, data analysis, data engineering 

**Technology**: Python, SQL   
### Cleaning Bank Marketing Campaign Data 
**Goal**: Cleaning a bank marketing dataset 

**Description**: During this project, I used many data cleaning techniques to perform operations on the [bank marketing dataset](https://github.com/ktani27/Projects-/blob/main/assets/bank_marketing.csv) for processing among which:
- Data types conversion
- Missing values replacement 
- Split of the dataset into three subsets:
  - [client](https://github.com/ktani27/Projects-/blob/main/assets/Cleaning%20bank%20data%20client%20table%20.png)
  - [campaign](https://github.com/ktani27/Projects-/blob/main/assets/Cleaning%20bank%20data%20campaign%20table%20.png)
  - [economics](https://github.com/ktani27/Projects-/blob/main/assets/Cleaning%20bank%20data%20economics%20.png)

**Code**: [Cleaning Bank Marketing Data](https://github.com/ktani27/Projects-/blob/main/assets/Cleaning%20Bank%20Marketing%20Data%20Notebook.ipynb) 

**Skills**: Data cleaning 

**Technology**: Python 
## SQL Projects 
### Analyzing Industry Carbon Emissions 
**Description**: The [product_emissions table](https://github.com/ktani27/Projects-/blob/main/assets/Product%20Emissions%20.png) contains product carbon footprints (PCFs) for various companies. The records include the greenhouse gas emissions attributable to given product measured in CO2. 

**Code**: [Analyzing Industry Carbon Emissions](https://github.com/ktani27/Projects-/blob/main/assets/Analyzing%20Industry%20Carbon%20Emissions.ipynb) 

**Analysis**: Based on the [query's result](https://github.com/ktani27/Projects-/blob/main/assets/Analyzing%20the%20Carbon%20Industry%20Query%20.png), the worst offenders, as far as global emissions, are:

- The materials industry with a product carbon footprint of 107129
- In second position, we have the capital goods industry with a PCF of 94942.7, which is three times more than the next industry on the list (Technology Hardware & Equipment). 


**Skills**: Data Manipulation 

**Technology**: SQL
### Analyzing Students' Mental Health 
**Goal**: The project consists in finding out if international students have a higher risk of mental health difficulties than the general population. 

**Description**: A Japanese international university surveyed its students in 2018 and published a study the following year. The study found that international students have a higher risk of mental health than the general population. 
I will explore the [Students data](https://github.com/ktani27/Projects-/blob/main/assets/Analyzing%20Students%20Mental%20Health%20Data%20Description%20.png) data using PostgreSQL to find out if I would come to a similar conclusion for international students. 


**Code**: [Analyzing Students Mental Health](https://github.com/ktani27/Projects-/blob/main/assets/Analyzing%20Students'%20Mental%20Health%20Notebook.ipynb)


**Analysis**: The queries return the average depression, social connectedness, and accultural stress for both domestic and international students. A s[ide-by-side comparison](https://github.com/ktani27/Projects-/blob/main/assets/Queries%20Side%20-%20by-side%20comparison.png) indicates the following:
- On average, domestic students  scored higher on depression, social connectedness.
- The international students averaged more on accultural stress, as expected.

Based on these results, We cannot support the thesis claiming that the international students have higher risk of mental health difficulties. 


**Skills**: Data Manipulation, Data analysis  

**Technology**: SQL 

