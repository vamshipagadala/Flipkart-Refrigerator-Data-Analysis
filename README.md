# Flipkart-Refrigerator-Data-Analysis
Web scraping and exploratory data analysis of refrigerator products from Flipkart using Python, Selenium, Pandas, and data visualization to uncover pricing trends, brand performance, and customer insights
Project Title

Web Scraping and Exploratory Data Analysis of Refrigerator Products on Flipkart

What is this project?

This project is a data analysis project where refrigerator product data is collected from Flipkart using web scraping and then analyzed using Exploratory Data Analysis (EDA).

The goal is to understand:

Refrigerator pricing trends
Popular brands
Customer ratings
Discount patterns
Market insights

This helps in understanding customer preferences and business strategies in the online refrigerator market.

Step 1: Problem Statement

Customers see many refrigerator options online with different:

Prices
Brands
Capacities
Discounts
Ratings

It becomes difficult to compare and choose the best refrigerator.

Businesses also need data to understand:

Which refrigerators sell more
Which price range is most popular
Which brands perform better

This project solves that problem by collecting and analyzing real product data.

Step 2: Data Collection (Web Scraping)

I collected refrigerator data from Flipkart using:

Python
Selenium
Chrome WebDriver
Why Selenium?

Flipkart loads product data dynamically, so Selenium helps interact with the webpage and extract live data.

Data Collected

The scraper extracted:

Brand name
Refrigerator capacity
Number of doors
Price
Original price
Discount percentage
Product rating

Example:

Brand	Capacity	Door	Price	Rating
Samsung	253 L	Double Door	₹24,999	4.3
LG	260 L	Double Door	₹26,499	4.4
Step 3: Data Cleaning

Raw scraped data often contains unwanted symbols and missing values.

I cleaned the data by:

Removing ₹ symbol from prices
Converting prices into numeric format
Removing % from discounts
Handling missing values
Standardizing text values

This made the dataset ready for analysis.

Step 4: Exploratory Data Analysis (EDA)

EDA was performed to identify hidden patterns.

Analysis Performed
1. Price Analysis

Analyzed refrigerator price distribution.

Purpose:
To identify affordable, mid-range, and premium products.

Insight:
Most refrigerators fall in the mid-price range.

2. Brand Analysis

Compared brands based on:

Number of products
Average ratings
Price range

Insight:
Some brands dominate the market with better customer trust.

3. Discount Analysis

Studied discount percentages across products.

Insight:
Higher discounts attract customer attention.

4. Ratings Analysis

Analyzed customer ratings.

Insight:
Most products maintain ratings above average.

5. Capacity Analysis

Compared refrigerators based on storage capacity.

Insight:
Medium-capacity refrigerators are most common.

Step 5: Data Visualization

Used charts and graphs for better understanding:

Bar charts
Histograms
Pie charts
Box plots

These visualizations helped identify market trends easily.

Key Insights from Project
Pricing Insight

Most listed refrigerators are in affordable to mid-range pricing.

Brand Insight

Top brands maintain competitive pricing and strong ratings.

Customer Preference

Customers mostly prefer refrigerators with:

Good ratings
Medium capacity
Reasonable price
Trusted brand
Discount Insight

Discounts increase customer attraction but don’t always guarantee higher ratings.

Tools & Technologies Used
Python
Selenium
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Business Value of This Project

This project helps businesses:

Improve pricing strategy
Understand customer behavior
Compare competitors
Optimize product listings
Conclusion

This project successfully collected and analyzed refrigerator product data from Flipkart.

It provided meaningful insights into:

Market trends
Pricing strategies
Brand performance
Customer preferences

This demonstrates practical skills in:

✔ Web Scraping
✔ Data Cleaning
✔ EDA
✔ Visualization
✔ Business Insight Generation

This is a strong portfolio project for Data Analyst roles.
