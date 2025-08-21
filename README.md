# Sales-Revenue-Overview-Analysis

## Table of Contents

 - [Project Overview](#project-overview)
 - [Data Sources and Column Description](#data-sources-and-column-description)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Discoveries and Insight](#discoveries-and-insights)
 - [Recommendation](recommendations)
 - [Conclusion](conclusions)


![Dashbaord1](https://github.com/Analyticope/Sales-Revenue-Overview-Analysis/blob/main/Sales%20Revenue%20DB.jpg)
![Dashbaord1]

 



   
### Project Overview
---
This analysis explores mobile phone sales in 2024 across different regions. It highlights the best-selling models, common price ranges, and customer preferences. It also looks at buyer behavior based on age, gender, and purchase channels, whether online, in-store, or through partners. By combining sales data with location and demographic insights, the report helps identify trends and improve sales strategies for each region.


### Data Sources and Column Description
 The data used in this project comes from an Excel file. It includes details like phone model, brand, operating system, storage size, color, country, city, price, total 
 revenue, sales channel, as well as customer info like gender, age, and age group.


### Tools

- Excel
  - [Download here](https://microsoft.com)
- Power Query - data cleaning, automate repetitive task(like fiitering, merging, and formatting).
- Building custom columns to perform specific calculations
- Power BI - Data visualization and analytics reports


### Data Cleaning/Preparation

  In the initial stage of this project, I performed key data structuring to ensure the dataset was clean, consistent, and analysis-ready. This phase included:
  
  - Loading and inspecting raw data to understand its structure and quality
  
  - Handling missing values to maintain data integrity
  
  - Removing blank rows and irrelevant columns to streamline the dataset
  
  - Cleaning and formatting data for consistency across all fields

### Exploratory Data Analysis
9 Key Exploratory question from Phone sales dataset, such as:

Here are 10 key questions this Power BI project aims to answer:
- Which mobile brands and models are the top sellers overall and in specific countries or cities?
- How do sales numbers vary by storage size, color, or operating system (Android vs. iOS)?
- What is the typical customer profile, age group, gender, for different brands or models?
- How do sales and revenues break down across different sales channels (online, partner, in-store) and payment types?
- Are there noticeable differences in pricing and sales volume between regions or cities?
- Which countries or cities generate the highest total revenue and units sold?
- Are there patterns in customer demographics based on mobile brand, model, or price range?
- How does sales performance change month over month in 2024?
- Are there correlations between customer age groups and the type of devices they purchase (for example, younger customers preferring certain brands)?




    
### Data Analysis

Tools & Features Used:

- DAX functions for custom measures and KPIs.

- Power Query for data cleaning and transformation.

- Calculated columns and measures.

- Custom columns and “Column by Example”.

- Aggregation functions (SUM, AVERAGE, COUNT etc).

- Interactive slicers and clear filter button for better UX.

### Discoveries and Insights
A. Phone Sales Data
  - Average Buyers: On average, 39 people purchased phones across the dataset.
  - Total Revenue: Phone sales brought in a total of $15 million.
  - Units Sold: Around 19,000 phones were sold through all sales channels.
  - Average Price per Phone: Each phone sold for about $758 on average.
    
B.  Regional and Channel Insights
  - Top-Performing Country:  India led the way with over $6.9 million in revenue.
  - Other Strong Markets: Turkey, Bangladesh, and Pakistan also showed strong but varying performance.
  - Best Sales Channel: Online sales dominated, pulling in $9 million in revenue.
    
C. Product Preferences & Trends
   Operating System Showdown:
 - Android: $11M in revenue, Android clearly led in sales performance
 - iOS: $4M in revenue
 - Top Month: February was the peak month of the fiscal year, generating $1.37 million in sales.

### Findings & Workflow Tools:
- UPI turned out to be the most used and highest-earning payment option across all purchases.

- Younger customers leaned heavily toward Apple devices, showing a clear brand preference.

- The data went through a full clean-up and transformation process using Power Query to get it ready for analysis.

- I organized the data using a star schema, making it easier to connect facts with dimensions like product, customer, and sales details.

- To make the dashboard more user-friendly, I added interactive filters you can explore the data by country, month, gender, payment method, and year.


  ### Recommendation
  After analyzing the 2024 phone sales data, here are some key recommendations to support better business decisions:

- Focus on High-Performing Regions
  
  India and Turkey had the highest sales and revenue. Future marketing and inventory planning should prioritize these regions to drive even stronger results.

- Boost Online Sales Strategy
  
  Online sales brought in the most revenue $9 million outperforming in-store and partner channels. Investing more in digital marketing and online sales platforms is likely 
  to increase returns.

- Expand Android Offerings
  
  Android phones generated $11 million in revenue, far more than iOS. Offering more Android models could help capture a larger market share.

- Optimize UPI Payment Method
  
   UPI was the most popular and highest-earning payment option. It’s important to make sure this payment method is well supported and promoted across all sales platforms.

- Leverage Seasonal Peaks
  
  February recorded the highest monthly revenue. Identifying and preparing for similar peak periods can help plan effective promotions and campaigns.

- Use Age-Based Marketing
  
   Younger buyers preferred Apple, while older customers leaned toward Samsung. This trend can guide age-targeted marketing and product positioning.

- Improve Dashboard Functionality
  
   The dashboard includes filters for country, gender, month, payment method, and year making it easy to explore insights. Future updates could add filters for features 
   like storage size and include predictive analytics for forecasting trends.

   These findings help shape smarter, data-driven strategies to boost sales, improve customer experience, and make better business decisions.

    

### Conclusion
  This dashboard highlights important trends in regions, customer behavior, and product preference. These insights can help guide smarter marketing, better stock planning, 
  and pricing strategies, all aimed at growing sales and improving customer experience.






 
