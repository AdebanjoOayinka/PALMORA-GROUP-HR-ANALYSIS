# PALMORA-GROUP-HR-ANALYSIS

## PROJECT OVERVIEW

#### The Palmoria Group, is a manufacturing company based in Nigeria, is embroiled in issues bordering on gender inequality in its 3 regions. Unfortunately, the media recently published the news with the headline “Palmoria, the Manufacturing Patriarchy”. 
This doesn’t look good for the owners of the business, based on their ambition to scale the business to other regions and even overseas. Cases like this can only spiral downwards,
revealing other issues like the gender pay gap, amongst other possible issues. The CEO of Palmoria, Mr Ayodeji Chukwuma, is keen to address these issues before they get out of hand. The CHRO, Mr Yunus Shofoluwe, has been assigned the task to identify key areas within the business that could give rise to issues and address them immediately.

Mr Shofoluwe decided to recruit you as an HR Analytics expert to analyse the company’s HR data and come up with recommendations for management’s attention. “Now, the future of gender equality in Palmoria lies in your hands” – the exact words of Mr Shofoluwe before he handed the data to you.

## Project Instruction
     *- Analyse the company data and generate insights that the Palmoria management team would need to address
     *- Your analysis should be visualised using appropriate charts
     *- Your focus should be on gender-related issues within the organization and its regions
     *- The insights required are based on your discretion. However, Mr Gamma, as an insider, has offered to give you pointers on areas you need to pay attention to

## PROJECT INSIGHT
    ● Generally, there are two genders in the organization. However, some employees refused to disclose their gender. You would need to assign a generic gender status to these employees
    ● Some employees are without a salary because they are no longer with the company. You will need to take those employees out
    ● Lastly, some departments are indicated as “NULL”. These departments would also need to be taken out.

## MORE INFORMATION
    1. What is the gender distribution in the organization? Distil to regions and departments
    2. Show insights on ratings based on gender
    3. Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management
    4. A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000
        ● Does Palmoria meet this requirement?
        ● Show the pay distribution of employees grouped by a band of $10,000. For example:
        ● How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000, etc.?
        ● Also visualize this by regions

## FURTHER ANALYSIS
    5. Mr Gamma thought to himself that since you were already working on the employee data, you could help out with allocating the annual bonus pay to employees based on the performance rating. He handed you another data set that contains rules for making bonus payments and asked you to:
        ● Calculate the amount to be paid as a bonus to individual employees
        ● Calculate the total amount to be paid to individual employees (salary inclusive of bonus)
        ● Total amount to be paid out per region and company-wid




#### For this project, I was asked to carry out a comprehensive Exploratory Data Analysis (EDA) using the appropriate analytical tools and techniques relevant to the context of the dataset.

## Company Overview
#### I am working as a Junior Data Analyst at RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon.
#### I am tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

## Dataset Description
#### The dataset contains information scraped from Amazon product pages, including:
   - Product details: name, category, price, discount, and ratings
   - Customer engagement: user reviews, titles, and content
   - Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
   - Total Records: 1,465 rows TotalFields: 16 columns

## Analysis Tasks
#### The data from the scrapped pages where to provide insight to how the company performed with respect to product sales and reviews.

   1. What is the average discount percentage by product category?
   2. How many products are listed under each category?
   3. What is the total number of reviews per category?
   4. Which products have the highest average ratings?
   5. What is the average actual price vs the discounted price by category?
   6. Which products have the highest number of reviews?
   7. How many products have a discount of 50% or more?
   8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
   9. What is the total potential revenue (actual_price × rating_count) by category?
   10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
   11. How does the rating relate to the level of discount?
   12. How many products have fewer than 1,000 reviews?
   13. Which categories have products with the highest discounts?
   14. Identify the top 5 products in terms of rating and number of reviews combined.

## Final Task

#### Include dashboard creation from the informations gotten from the analysis to present to the company stake holders for the quarterly product review meeting. This will show areas where they are winning and also where they need to improve.

#### Using my cleaned dataset and pivot outputs, build an Excel dashboard.

## Data Source
   *- Microsoft Excel [Download Here](https://microsoft-excel.en.download.it/download)

## Data Presentation
   *- Microsoft PowerPoint [Download Here](https://microsoft-powerpoint.en.download.it/download)

## Tools Deployed
   *- MS Excel Tables for data sorting, manipulating, cleaning and formatting
   *- MS Excel pivot tables for analysis and showing distributions
   *- MS Excel Charts to create charts
   *- MS PowerPoint for charts presentation

## How the Analysis Were Carried Out
   1. What is the average discount percentage by product category:
      
      *- Using Pivot tables to extract the Categories, Product and % Discount
      
      *- Using Excel function to get the average
      
   2. How many products are listed under each category
      
      *- Removing product duplicate
      
      *- Using Excel function (COUNTIFS) to count the data
      
   3. What is the total number of reviews per category:
      
      *- Using Excel function to extract the review id for each product
      
      *- Using Excel function (COUNTIFS) to count the data
      
   4. Which products have the highest average ratings:
      
      *- Using pivot tables to extract product and average ratings
      
      *- Using Excel function (VLOOKUP) to get the products with the highest average ratings.
      
   5. What is the average actual price vs the discounted price by category:
    
      *- Using pivot tables to extract actual price per category

      *- Using Excel function (AVERAGE) to get the figure
      
   6. Which products have the highest number of reviews:
      *- Sorting the tables that has the data for reviews and product to get the result
       
   7. How many products have a discount of 50% or more:
    
      *- Sorting the tables that has the data for % discount and product to get the result
       
   8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.):

      *- Sorting the tables that has the data for the product and ratings to see the distribtion
      
   9. What is the total potential revenue (actual_price × rating_count) by category:

      *- Using pivot tables to extract actual price and rating counts
      
      *- Creating a new cloumn to show the prouct using Excel formula (MULTIPLY)
      
   10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500):

      *- Using pivot tables to extract actual price per product
      
      *- Using Excel function (IF) to get the figure
      
   11. How does the rating relate to the level of discount:

      *- Using pivot tables to extract product id, rating and % discount
      
      *- Sorting the data by highest ratings and highest % discount to show the distribution
      
   12. How many products have fewer than 1,000 reviews:

      *- Using pivot tables to extract product id and rating count to show the total count
      
   13. Which categories have products with the highest discounts:

      *- Using pivot tables to extract category and % discount to show the total count
      
      *- Used a chart to show the distribution
      
   14. Identify the top 5 products in terms of rating and number of reviews combined:

      *- Using pivot tables to extract product id and rating count to show the total count
      
      *- Using Excel functions (IF) and (AND) to get the overal figure highest
      
      *- Confriming the results by column sorting by fighest figures 
      
      *- Using Excel function (VLOOKUP) to get the name of the products in category column
       
## Charts

#### Charts were deployed for:
     *- Analysis 6:
