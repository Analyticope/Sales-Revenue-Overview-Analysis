# Sales-Revenue-Overview-Analysis

## Table of Contents

 - [Project Overview](#project-overview)
 - [Data Sources and Column Description](#data-sources-and-column-description)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Discoveries and Insight](#discoveries-and-insights)
 - [Findings](#findings)
 - [Workflow and Tools](#workflow-and-tools)
 - [Recommendation](recommendations)
 - [Conclusion](conclusions)


![Dashbaord1](https://github.com/Analyticope/Sales-Revenue-Overview-Analysis/blob/main/Sales%20Revenue%20DB.jpg)
![Dashbaord1](https://github.com/Analyticope/Sales-Revenue-Overview-Analysis/blob/main/Sales%20Revenue%20DB2.jpg)
![Dashbaord1](https://github.com/Analyticope/Sales-Revenue-Overview-Analysis/blob/main/Sales%20Revenue%20DB3.jpg)


 



   
### Project Overview
---
This project provides a comprehensive overview of sales overview analysis in 2022, 2023, 2024, covering total revenue, costs, profits, and conversion rates. It further breaks down results by month, marketing campaigns, lead sources, and sales channels (in-store vs. online) to uncover key drivers of growth and efficiency.

### Data Sources and Column Description
 The data used in this project comes from an text CSV file. It includes details like CUST_Data, Marketing_Data, Lead_Source_Data, Channel_Data, Sales_Rep_Data, Sales_Data, Product_Data, Region_Data.


### Tools

- Excel
  - [Download here](https://microsoft.com)
- Power Query - data cleaning, automate repetitive task(like fiitering, merging, and formatting).
- Building custom columns to perform specific calculations
- Power BI - Data visualization and analytics reports


### Data Cleaning/Preparation

  In the initial phase of this project, I focused on preparing the dataset to ensure it was clean, consistent, and ready for analysis. The key steps included:
  
  - Importing and reviewing the raw data to understand its structure and quality
  
  - Addressing missing values to preserve data accuracy
  
  - Removing empty rows and unnecessary columns to streamline the dataset
  
  - Standardizing and formatting fields to maintain consistency across all records

### Exploratory Data Analysis
3 Key Exploratory question from sales dataset, such as:

Here are 3 key questions this Power BI project aims to answer:
1. Sales & Campaign Performance
- How do revenue, cost, and profit change monthly?
- Which campaigns drive the most revenue?
- Which lead sources contribute most to sales?
- Do in-store or online channels perform better?
- Why is the conversion rate dropping despite higher revenue?
  
2. Regional & Country Insights
- Which regions generate the most revenue?
- Which countries are top or low performers?
- Are costs aligned with revenue growth across regions?
- How do conversion rates differ by country?
- Do sales channels vary in effectiveness by region?

3. Product Performance
- Which products earn the highest revenue and profit?
- Do top-rated products also bring in top sales?
- Which products get the most views compared to sales?
- Which low-rated products need improvement?
- Which price ranges or categories dominate sales?



    
### Data Analysis

Tools & Features Used:

- DAX functions for custom measures and KPIs.

- Power Query for data cleaning and transformation.

- Calculated columns and measures.

- Custom columns and “Column by Example”.

- Aggregation functions (SUM, AVERAGE, COUNT etc).

- Interactive slicers and clear filter button for better UX.

### Discoveries and Insights
1. Sales & Campaign Performance 
- Revenue and profit show an upward trend month by month, even though conversion rates declined slightly.
- Certain campaigns (e.g., targeted marketing) generated higher sales returns, while others underperformed.
- Lead sources like social media and website contributed most to revenue compared to referrals or emails.
- In-store sales still lead in performance, but online channels are showing steady growth.

2. Regional & Country Insights 
- Asia and North America are the strongest revenue-generating regions, with Europe and South America trailing.
- Top countries (e.g., USA, China, and India) significantly outperformed smaller markets.
- Some regions show higher costs without matching revenue growth, affecting profitability.
- Conversion rates vary widely across countries, indicating regional differences in buyer behavior.
- Sales channel performance differs by region, with online sales growing faster in developed markets.

3. Product Performance 
- Top-selling models drive most of the revenue and profit, while lower-rated products struggle.
- High customer ratings often align with high sales, confirming that customer satisfaction boosts revenue.
- Products with high views but low purchases indicate interest but weak conversion (possible pricing or value gap).
- Low-rated items like Smartwatch 3 and Laptop Pro 14 need quality or marketing improvements.
- Mid-range products dominate sales, showing that affordability drives customer preference.

### Findings

1. Sales & Campaign Performance
- Revenue and profit are increasing month by month, but conversion rates are falling slightly.
- Certain campaigns deliver high ROI, while others add cost without strong returns.
- Website and social media are the strongest lead sources, outperforming email and referrals.
- In-store sales still generate more revenue than online, but online sales are steadily growing.

2. Regional & Country Insights
- Asia and North America contribute the highest share of revenue, while Europe and South America lag behind.
- The USA, China, and India dominate sales compared to other countries.
- Some regions show high operating costs without matching revenue growth.
- Conversion rates vary by country, reflecting differences in customer behavior.
- Online channels perform better in developed regions, while in-store dominates emerging markets.

3. Product Performance
- Top-selling models (e.g., flagship phones and mid-range devices) bring in the most revenue and profit.
- Highly rated products also achieve higher sales, confirming the link between customer satisfaction and revenue.
- Some products attract high views but low purchases, indicating interest but weak conversion (possibly pricing or features).
- Poorly rated products (e.g., Smartwatch 3, Laptop Pro 14) need quality improvements or stronger marketing.
- Mid-range products dominate demand, showing affordability drives buying decisions.

### Workflow & Tools
 The following workflow and tools were used:
 
1. Data Preparation
- Cleaned and structured raw data (handled missing values, removed duplicates, standardized formats).
- Ensured consistency across regions, products, and channels for accurate reporting.

2. Data Analysis & Modeling
- Applied DAX (Data Analysis Expressions) in Power BI to create measures for revenue, profit, cost, and conversion rates.
- Built relationships between datasets (sales, regions, products, campaigns) to enable dynamic filtering and drilldowns.

3. Dashboard Development
- Power BI used to design three dashboards:
- Sales & Campaign Performance (Revenue, cost, profit, conversion, campaigns, channels).
- Regional & Country Insights (Revenue by region/country, conversion rates, cost vs. revenue, channels).

4. Product Performance (Revenue/profit by product, customer ratings, product views vs. sales, categories).
- Created interactive visuals (bar charts, line trends, maps, KPIs) for storytelling.

5. Visualization & Communication
- Highlighted KPIs (total revenue, profit margin, conversion rates).
- Used filters for regional, product, and channel analysis.
- Focused on insights that help improve sales strategy and product positioning.

 
### Recommendation
 1. Sales & Campaign Performance
- Improve conversion rates: Although revenue is rising, conversion is dropping. Refine targeting, optimize landing pages, and simplify the checkout process to boost 
  conversion.
- Focus on high-ROI campaigns: Allocate more budget to campaigns delivering strong returns and cut back on low-performing ones.
- Strengthen digital channels: Since online is steadily growing, invest in e-commerce infrastructure, SEO, and digital ads to balance dependence on in-store sales.
- Leverage lead sources: Double down on website and social media acquisition channels since they outperform email and referrals.

2. Regional & Country Insights
- Prioritize high-performing regions: Scale operations and marketing in Asia and North America, which drive the bulk of revenue.
- Address underperforming regions: In Europe and South America, reassess pricing, promotions, and distribution to increase competitiveness.
- Optimize cost structure: Reduce overhead in regions where costs are high but revenue growth is weak.
- Tailor strategies to markets: Customize campaigns by region—online-heavy in developed markets, in-store-focused in emerging markets.
- Localize products: Introduce region-specific promotions or product bundles to meet local preferences.

3. Product Performance
- Promote best-sellers: Expand stock and marketing for top-performing phones and mid-range devices that dominate sales.
- Enhance poorly rated products: Improve product quality, add missing features, or redesign marketing for underperformers like Smartwatch 3 and Laptop Pro 14.
- Capitalize on customer ratings: Encourage reviews and testimonials since high ratings align with strong sales.
- Address view-to-purchase gap: For products with high interest but low conversion, consider price adjustments, discounts, or clearer value messaging.
- Expand mid-range offerings: Since affordability drives demand, launch more mid-tier models with strong specs at competitive prices.
    

### Conclusion
 The analysis shows that while total sales and profits are growing, conversion rates and underperforming campaigns remain key challenges. Regional differences highlight the need for tailored strategies, with Asia and North America leading in revenue while other regions require targeted interventions. At the product level, mid-range devices and highly rated models drive success, whereas poorly rated products and those with low conversion need improvement.
Overall, these insights emphasize the importance of data-driven decision-making. By focusing on optimizing campaigns, strengthening online channels, improving product quality, and tailoring strategies by region, the business can achieve sustainable growth and better align sales strategies with customer preferences.






 
