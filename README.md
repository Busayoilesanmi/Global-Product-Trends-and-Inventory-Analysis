# Global-Product-Trends-and-Inventory-Analysis
[Introduction](#Introduction)

[Objective](#Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction

This report presents a comprehensive analysis of global product trends and inventory performance for the year 2023. Using Microsoft Excel, the study investigates how product categories,
pricing, customer ratings, stock quantity, and other factors influence business outcomes. The analysis aims to help stakeholders make data-driven decisions to improve product strategies, optimize inventory, and enhance customer satisfaction.

### Objective of the Project

This project aims to evaluate and understand global product performance trends in 2023 using Microsoft Excel. The objective is to identify how product categories, pricing, customer 
ratings, inventory levels, and other variables such as color, size, and warranty period influence business performance.

### Problem Being Addressed

Businesses often face challenges in determining which product lines drive the highest returns and customer satisfaction. This analysis seeks to:

* Which product categories get the best customer reviews?
  
* Which product categories are the most expensive?
  
* Are higher-rated products more expensive?

* Does a longer warranty increase price?
  
* Do certain colors or sizes get higher ratings?
  
* Are newer products getting better reviews?

* Which specific products are the most expensive?
  
* Does stock quantity impact product rating?
  
* Is there any correlation between the number of tags and product rating?

### Key Datasets and Methodologies

### Datasets Used
The analysis uses sales and inventory data from internal systems which include product categories, pricing, customer ratings, stock quantity, and other factors influence business outcomes.

#### Methods Used
The analysis utilizes Microsoft Excel tools, such as: 

•	Pivot Tables for data summarization. 

•	Data Cleaning Techniques such removing duplicate and blank space and empty rows to ensure data quality. 

•	Visualizations and Dashboard (charts and graphs) to illustrate trends.
## Story of Data

### Data Source

Platform: Kaggle.com

Nature: Public, open-source

### Data Collection Process

Although the data was obtained in a structured CSV format, it was originally compiled through aggregated records of product listings, customer reviews, and inventory levels. The dataset simulates real-world commercial data, offering practical dimensions for analysis.

### Data Structure

Each row in the dataset represents a single product entry, while columns represent various product features:

Categorical variables: Category, Color, Size, Month

Numerical variables: Price, Rating, Stock Quantity, Warranty Period

### Key Features & Significance

Category: Helps compare performance across product types

Price: Indicates perceived value or cost positioning

Rating: Reflects customer satisfaction

Stock Quantity: Impacts availability and sales planning

Warranty: Influences buyer trust and product reliability perception

Color/Size: Useful in customer preference segmentation

### Data Limitations & Biases

The dataset may not reflect real-time trends as it is static and simulated.

Certain attributes had missing values, which were addressed through Excel’s imputation techniques.

Some data may reflect synthetic generation methods, so while patterns are realistic, they may not directly translate to live business environments.

## Data Splitting and Preprocessing

### Data Cleaning

Removed duplicates and null values.

Standardized format for colors and product names.

### Handling Missing Values

Used average imputation for missing ratings and warranty fields to maintain integrity without deleting records.

### Data Transformations

Created new fields such as “Price by Rating” and “Average Rating by Category”.

### Data Splitting 

Dependent variables: Price, Rating.

Independent variables: Category, Stock, Warranty, Month, Color/Size.

### Industry Context
The e-commerce industry has experienced exponential growth over the past decade, driven by digital transformation, increased internet penetration, and changing consumer preferences toward online shopping. In this highly competitive and fast-moving environment, data-driven decision-making has become essential for maintaining market relevance and improving operational efficiency.

### Relevance to Analysis
This analysis provides insights that are particularly relevant for retailers, inventory managers, marketing teams, and product strategists within the e-commerce sector. Understanding how product attributes such as price, rating, warranty, and stock levels interact allows businesses to:

* Optimize product offerings based on customer satisfaction and perceived value

* Improve inventory turnover rates by identifying overstocked or underperforming items

* Enhance pricing strategies to align with customer expectations and competitor benchmarks

* Detect seasonal trends in product demand, helping with promotion and stocking decisions

### Value to the Industry

By using Microsoft Excel's analytical capabilities (PivotTables, formulas, charts), the analysis enables decision-makers to:

* Translate raw product data into actionable intelligence

* Create visually intuitive dashboards to monitor performance metrics

* Develop recommendations for strategic planning such as which products to scale, discontinue, or discount

* Identify opportunities for cross-selling and bundling based on related attributes like warranty and price range

### Stakeholders

Marketing Teams: Use insights to tailor campaigns to high-performing product categories

Inventory Managers: Monitor and balance stock levels across regions and time periods

Product Development: Focus on features that correlate with high customer ratings

Executives & Business Analysts: Leverage summarized insights to make informed investment or expansion decisions

## Pre-Analysis

### Key Trends Identified

* Home Appliances are the highest priced category on average ($258.8).

* Clothing holds the best average product rating (3.02).

* Blue/Medium sized products receive the best feedback (3.015 rating).

### Potential Correlations

* Products with a higher stock range (81–100) are generally rated better.

* Longer warranties are associated with slightly higher prices.

### Initial Insights
* Ratings peak in March, suggesting potential seasonal or campaign influence.

* Electronics are competitive in pricing but fall behind in customer satisfaction.

## In-Analysis

### Unconfirmed Insights

* High-priced products may drive customer expectations and lower ratings unless supported by warranty and quality.

* Some variations like Red/Small also perform well, suggesting size and color influence perception.

### Recommendations

* Increase inventory for best-performing variants (e.g., Blue/Medium clothing).

* Bundle extended warranties with electronics to improve perceived value.

* Monitor high-price items (e.g., monitors) for return rates and satisfaction trends.

### Excel Techniques Used

Pivot Tables: Summarizing average prices and ratings.

## Post-Analysis and Insights

### Key Findings

* Best-reviewed category: Clothing (3.02 rating).

* Highest average price: Home Appliances ($258.8).

* Most expensive product: Monitor ($259.12).

* Top-rated variation: Blue/Medium (3.015).

* Best month: March (3.048 average rating).

### Comparison with Initial Findings
Initial expectations suggested Electronics might dominate. However, Clothing products outperformed others in customer satisfaction despite lower pricing.

## Data Visualizations & Charts

![Dashboard6](https://github.com/user-attachments/assets/92303ef8-0283-4e62-acab-6f137461b020)

### Link to the Excel documents and Dashboard

https://docs.google.com/spreadsheets/d/1OYkcj3w4L03QLAZE34MTSFMl6sEyRMK0/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

### Explanation of Visualizations

Each visual offers quick insights:

Clothing’s consistent performance is seen across price, rating, and warranty data.

Inventory levels strongly correlate with better product reviews.

## Recommendations and Observations

### Actionable Insights

* Increase production of high-rated combinations (Clothing, Blue/Medium).

* Reprice underperforming products in the Electronics category.

* Reassess stock levels for low-rated products with high inventory.

### Optimizations

* Shift marketing spend toward best-rated months and categories.

* Extend warranty coverage on mid-tier products to raise perceived value.

### Unexpected Outcomes

* March performed exceptionally well across all categories; requires further investigation into marketing actions during that period.

## Conclusion

### Key Findings

* Product attributes like size, color, and warranty period significantly affect customer satisfaction.

* Clothing products offer the best balance between affordability and customer rating.

### Limitations

* Limited time span of analysis (3 months).

* Dataset does not include geographic segmentation or returns data.

### Future Research

* Explore integration of customer sentiment (reviews).

* Analyze year-over-year performance for long-term trends.

* Incorporate sales volume for deeper profitability insights.

## References & Appendices

### References

Internal Sales and Inventory Systems

Microsoft Excel Documentation

Product Management Records

### Appendices

* Appendix A: Full Pivot Table Output

* Appendix B: Excel Formulas Used

* Appendix C: Raw Dataset (sanitized)

* Appendix D: Screenshot of Final Dashboard
