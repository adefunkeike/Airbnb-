# AIRBNB REPORT 2022


 ## Project Overview 
This is dataset explore different rental apartment from Airbnb where the hosts are the owner of the rental in different borough in New York, USA. This dashboard gives an overview of count , prices , availability and geographic of the rental apartment on Airbnb .

	

 ## Data Source

This dataset was gotten from kaggle as csv file which was downloaded to work on 

## Tools

- WPS Spreedsheet - This was used to make quick correction,data cleaning and analysis
- Power Bi - This was used for visualization of insight and to expansaite the analysis derived using DAX

## Data Cleaning / preparation
  Initially the data cleaning steps was performed from
  - Data Loading
  - Data Cleaning
  - Filling null values and characters
  - Removal of Missing Values
  - Correcting dates format
  - Using pivot table to analyse data and give quick overview
 
  ## Exploratory Data Analysis

  EDA involves explaining the human resource datasetbto answerthese questions 
  
  1. What can we learn about different hosts and areas?
  2. What can we learn from predictions? (ex: locations, prices, reviews, etc)
  3. Which hosts are the busiest and why?
  4. Is there any noticeable difference of traffic among different areas and what could be the reason for it?

     
## Data Analysis
Include some interesting code/features worked with
```excel
=trim(B2:B48896)
```
To revome extra  white spacing 
```excel
==COUNTIF(F:F,"Crown Heights")
`````
To count based on conditions
### Results/Findings
The analysis results are summarized as follows:
1. The total host are 37,450
2. The total count of rentals 48,895
3. we have four major borough which are manhattan,Brooklyn, Queens, Bronx, State Island
4. I observe that most host in Manhattan have many listed apartment with low average prices but increased sum price because they have more listing space 

## Recommendations
Based on the analysis, we recommend the following actions:
From this analysis Host in Manhattan are the most productive and the busiest , some certain host  charge low prices on listing space and have many spaces to list, In Brooklyn there also productive host but don't have many listing space as host in Manhattan. Private room and Entire apartment room type are preferred listing space for host to own as customer can stay for more nights which increase profitability. Host who has many listing space has higher reviews because they are experienced

## References
 - Github
 - Kaggle
 - Youtube
