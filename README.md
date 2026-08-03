# MiamiRetailShop
This data analysis project investigates daily sales fluctuations for a [retail shop](https://github.com/Gaelim/youtube/blob/master/Miami%20Shops.zip) based in Miami. thanks to  [Absent Data](https://www.linkedin.com/in/gaelimholland/) for providing this challenge. Currently, leadership lacks clear visibility into the primary drivers behind these sales variations.

By analyzing how weather patterns and customer demographics influence store performance, this project provides actionable insights to help leadership optimize inventory planning, staffing schedules, and promotional campaigns.

--- 
Analysis Ohjectives 
* Link sales data with weather patterns and survey demographics
* identify correlations: temperature vs sales, rainfall effects, weekend lift.
* Compare shop performance and seasonal patterns.
* Build foundation for dashboards.

Expected Outcomes 
* Clear picture of how weather drives custoer demand.
* Insights on family vs single, male vs female shopping patterns.
* Shop-level comparisons to guide staffing and inventory decisions.
* Dashboard that allows ongoing monitoring of trends.

Dashboard Questions 
1. How strongly do temperature and rainfall affect daily sales?
2. Which shop performs best, and why?
3. Who are our customers -- families vs single male vs female and how does this change over time? 
4. Are there predictable seasonal patterns in sales?
5. What actions would you take based on these insights? 
--- 

### Data Preparation 

1. Combined columns from all three sheets into one master table by joining them on the date column using the From Table/Range. 

<p align="center">
  <img src="images\FromTableRange.png" alt="CatorDog" width="80%">
</p>


2. adding features (feature engineering) such as days_of_the_week, Is_weekend and sales_per_customer 
<p align="center">
  <img src="images\features_column_added.png" alt="CatorDog" width="80%">
</p>

3. it has been found that there is 0 null values

--- 

### DASHBOARD Analysis

