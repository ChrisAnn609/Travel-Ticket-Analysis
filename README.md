# Travel-Ticket-Analysis
## Table Of Contents
- [Project overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results of Findings](#results-of-findings)
- [Recommendations](#recommendations)
- [Limitations](limitations)

  ### Project Overview
  This Data Analysis Project aims to provide insights into  customer behaviour, travel ticket booking patterns and market trends. By analyzing various aspects of travel ticket booking data, this project seeks to identify trends,make data-driven recommendations to improve profitability and gain a deeper understanding of the industry's performance.

  [Dashboard](Travel ticket analysis.png)
  

 ![image](https://github.com/ChrisAnn609/Travel-Ticket-Analysis/assets/173093556/7012ddc6-b85b-41f9-b119-7de50c8f7068)


  
### Data Sources
  The Primary Data set used for this analysis is the "Travel ticket Booking Analysis.xlsx" file containing detailed information about
  - Customer Demographics
  - Destination prices
  - Customers' Bookings
  - Booking platforms
  - Performance table
  - Cancellations
    
  #### The tools used were:
  - Kaggle : Data Collection  
- Excel: Data Entry
- Power BI: Data Cleaning, transformation and Visualization

 ### Data Cleaning and Preparation
  In the initial data preparation phase, the following tasks were performed:
  - Data loading and inspection
- Handling missing and duplicate values
- Data cleaning and formatting

### Exploratory Data Analysis
Exploratory Data Analysis involved exploring the Travel ticket Booking Analysis Analysis data to answer key questions such as:
- What are the peak travel periods over time?
- What are the popular origin-destination pairs and ticket prices?
- What's the distribution of bookings across the different channels and customer demographics?
- Correlations between booking behaviour and customer segments?
    
    
The visualizations used to answer this question included: Slicers, cards, Line charts, Bar charts, Scatter Plots, donut chart, gauge chart and Pie Charts.
 
 ### Data Analysis

 The following metrics were calculated:
 Average Ticket Price 
```
Average Ticket Price = AVERAGE('Customers'' Bookings'[Total Cost ($) incurred by Customer])
```
Total Number of Customers
```
Total number of Customers = COUNTROWS('Customer Details')
```
Total Male Customers
```
Total male customers = 
CALCULATE(
    COUNTROWS('Customer Details'),
    'Customer Details'[Gender] = "Male"
)
```
Total Female Customers
```
Total male customers = 
CALCULATE(
    COUNTROWS('Customer Details'),
    'Customer Details'[Gender] = "Female"
)
```
### Results Of Findings

- The peak months for traveling were July, November and June.
- The WEB platform was the most popular platform for booking airline reservations, accounting for 48.21% of 108 of the bookings. The use of travel agents to book airline is also a popular practice, accounting for 37.1 % or 83 of the total bookings; whilst the booking app accounted for 14.7% or 33 of the total bookings.
- The customers are placed in 1 of three loyalty status categories based on their booking behavior.The platinum customers are those who make 5 or more bookings, the royal customers are those who make between 2-4 bookings while the standard customers are those who make 1 booking only.
- Platinum customers spend on average $1040 for ticket prices, Royal customers spend on average $591.85 for tickets while standard customers spend on average $394.09 for tickets.
- For Miami to Chicago, MBJ to Charlotte, KIN to Santo Domingo, travelers solely went for business purposes. For MBJ to Atlanta, majority of the bookings were for business purposes.
- Males placed more bookings than females- with the males accounting for 141 out of the 224 bookings and contributing $138,706 to the yearly revenue. The most popular age range of the male travelers was within the age group 23-27, with 18 travelers, age group 18-22 and 28-32 each accounting for 6 of the male travellers and the age group 33-37 accounting for 5 of the male travelers.
- Travellers travelled first class for almost 50% of the total bookings.
- Miami to las Vegas is one of the popular destination for travelers looking to relax.
- The most expensive route was MBJ to Atlanta, while the cheapest route was KIN to Cartagena.


### Recommendations
Based on the analysis, the following actions are recommended:
- Ensure the web platform is optimized for user experience and offers seamless booking processes, as the convenience and accessibility of web platforms could make them more popular.
- Tailor business travel packages and services to attract more male travelers, as the majority of the bookings are done by male customers.
- Enhance first-class offerings and create business travel packages that cater to these preferences, particularly for Business travelers, as they might prefer the comfort and amenities of first class for long or important trips.
- Plan promotional campaigns and manage capacity during the peak travel periods(Summer and Christmas holidays) to maximize revenue.



### Limitations
  Some records had to be excluded, as the accuracy of the analysis conclusion would have been affected.
