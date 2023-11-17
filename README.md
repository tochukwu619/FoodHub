# FoodHub
## Analysis of restaurants in a region

---
### TABLE OFCONTENT

1. [PROJECT OVERVIEW](#project-overview)
2. [DATA SOURCE](#data-source)
3. [TOOLS](#tools)
4. [DATA CLEANING/PREPARATION](#data-cleaning/preparation)
5. [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
6. [DATA ANALYSIS](#data-analysis)
7. [RESULTS/FINDING](#results/finding)
8. [RECOMMENDATION](#recommendation)
9. [LIMITATION](#limitation)
---

### PROJECT OVERVIEW

The project is on the analysis of sales data gotten from the restaurants in a given vicinity. We are analyzing for the top performing restaurants and cuisines. 
![Foodhub-Dashboard](https://github.com/tochukwu619/FoodHub/assets/125865918/440d5a06-1ec1-43a7-abe8-6a7cb99cc8eb)

### DATA SOURCE

The dataset used for this project is labelled as ’foodhub_order(1).csv’.

### TOOLS

-	Microsoft Excel

### DATA CLEANING/PREPARATION

Using Microsoft Excel, the data was cleaned by ensuring that there were no duplicates. Spelling checks were also performed on the fields for consistency. Blank-value check was done to ensure that there was no inappropriate blank cell.
![Analysis 1](https://github.com/tochukwu619/FoodHub/assets/125865918/2be37462-c7ac-43f6-b61c-bef58a2e42eb)

### EXPLORATORY DATA ANALYSIS

The following were the KPIs asked during this project: 
1.  The total number of restaurant name.
2.	Which is the most frequently ordered restaurant and how many times were orders placed on this restaurant?
3.	Create a visual for the highest ten (10) restaurants based on their frequency of orders.
4.	Which restaurants is mostly sorted after during weekends and how many orders were placed?
5.	With the aid of a chart, compare the number of orders between weekday and weekends.
6.	How many types of cuisine do we have?
7.	Present a visual that shows the cuisine type and the number of times they were ordered?
8.	Which cuisine type is the most expensive?

### DATA ANALYSIS

- Using Microsoft Excel, a formula was used to get the sum of restaurants.
```
=1/COUNTIFS([restaurant_name],[@[restaurant_name]])
```
  The above formula was used to create a new column which was then summed up to give the total number of restaurants.
- Using a pivot chart, the top ten restaurants based on total number of orders received, was plotted.
![Analysis 2](https://github.com/tochukwu619/FoodHub/assets/125865918/53c521ad-f376-445e-9e63-2ecd5b542ba4)

- A comparison was made between weekends and weekdays for the top 10 restaurants based on the total number of orders received.
![Analysis 3](https://github.com/tochukwu619/FoodHub/assets/125865918/d9e860a4-3a9c-4f1e-8d20-c87fd1d33ff3)

- A formula was used to get a column for total number of cuisines.
```
=1/COUNTIF([cuisine_type],[@[cuisine_type]])
```
  The sum of this column gives the total number of cuisines.
- A pivot chart for the relationship between the cuisine type and number of orders was plotted.
![Analysis 5](https://github.com/tochukwu619/FoodHub/assets/125865918/4030b8e9-fd19-454a-affe-ea6ff85843f4)

- The most expensive cuisine was gotten from the dataset.
![Analysis 6](https://github.com/tochukwu619/FoodHub/assets/125865918/267c479f-64a5-4441-a8db-b9bd5166ab3a)

- All analysis was used to build a dashboard.
![Foodhub-Dashboard](https://github.com/tochukwu619/FoodHub/assets/125865918/47163c30-26fe-4310-bd52-d04ab29b180f)

### RESULTS/FINDING

It was observed that:
-	Total number of restaurants was 178
-	The total number of cuisines was 14
-	The most expensive cuisine was from the Mediterranean.
-	The top 3 restaurants by number of orders are: Shake Shack, The meatball Shop and Blue Ribbon Sushi.
-	The top 3 cuisines by number of orders are: American, Japanese and Italian.

### RECOMMENDATION

Further information should be given about the vicinity to understand the reason for the top restaurants and cuisines. 

### LIMITATION

The locations of the restaurants and customer demographics were not given


