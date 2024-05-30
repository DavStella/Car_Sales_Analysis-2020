# Zion Car_Sales_Analysis-2020
![](cars.jpg)
## Introduction
This data set is about Zion car retailer company with branches across six states in Nigeria charges us with the task of providing insightful business analysis
They are interested in their sales performance for the year 2020. 

### Power BI Concepts Applied: 
DAX Concepts: Calculated Column, 
- Custom Column,
- Quick Measures,
- Filters,
- Tooltips, and
- Slicer

## Problem Statement
1.	Sales Performance Analysis: -Dive deep into our sales performance throughout 2020.
- Identify trends in sales volume,
- uncover any seasonality effects, and
- pinpoint peak sales periods.
  
2.	Customer Demographics:
- Gain a comprehensive understanding of our customer base demographics.
- Uncover insights into the age, gender, location, and
- Other relevant characteristics of our customers.
  
3.	Geographical Analysis:
- Analyse the performance of our branches across different regions.
- Identify areas with the highest sales volumes,
- Compare sales performance across branches, and
- Understand regional preferences or market trends.
  
5.	Product Analysis:
- Explore the preferences of our customers regarding car brands and models.
- Identify the top-selling models,
- Analyse the popularity of different car categories, and
- Uncover any trends or patterns in product preferences.
  
## Data Sourcing
Excel file was downloaded after which extracted into a Power BI query for cleaning, transformation, manipulation, analysis, and visualization. The dataset contains a single sheet/table comprising of **1,491 rows and 6 columns**.

![](raw_data.png)

## Data Transformation/Cleaning:
Data was efficiently cleaned and transformed with the Power Query Editor of Power BI. 
Some of the applied steps included:

![](transformed_data.png)

- Promote headers
- Duplicated my table
- Creating an “Age Bracket” using the “Age” column. Note the ages are between 24-47 years of age in this dataset. Go to “Add Column – conditional Column” and create the Age Bracket in groups.
- Trim “Car_Model” to eliminate any space
- Change the “Sale_Date” data type from number to Date data type
- Split the “Car Model column to have the “Car Model” and “Car Brand”
- Extracted from  “Sale Date” - “Sale Month” and “Sale Day”
- For the Gender column we had ‘F’, Females, Female, Male, Malee which was replaced with “Female” and “Male”
- Choose the needed columns for the required analysis
- Excluded the duplicated table before loading to Power BI desktop using “close and Apply”

## Data Analysis and Visuals(What Happened?)
![](Dashboard_analysis.png)

## Sales Performance Analysis:
- sales performance throughout 2020 =1,491
- The peak sales period is November having 200 monthly sales.
- However, the highest growth rate(%) was in June.
- There was a drastic increase from 90 to 140 the following month.

  
## Customer Demographics:
- Lagos has the highest number of customers = 361. 
- Average age in this analysis = 34, with approximately 51% female.

  ![](Location_analysis.png)

## Geographical Analysis:
- Having seen that Lagos has the highest sales, below is the overall performance.
- Total sales =361
- Highest monthly Sale= November (40)
- Average age 35, Majorly Female gender between the ages 31-41
- Preferred car Brand = Ford followed by Toyota

## Why it happened? (Why the large difference, this brings us to insights).
### Product Insights
![](product_analysis.png)

The top 5 Car Brands From the dashboard generated approximately 90% of the total Sales transactions while the rest generated about 10%.

### Brand Insight
![](brand_model.sale.png)

-	The top 5 Brands have more than 1 Model.
-	This shows that there is a strong correlation between the Sales and Brand Model.
-	The more the models are rowed out, the tendency for more Sales/Patronage

### Location Insight
![](Brand_Transaction_Location.png)
- Just like the above observation, it is evident also that the more, the tendency of more sales. Eg. Ford had a total of 368 Sales , having 7 locations while Volswagen had just 3 sales having 2 locations.

### Date Insight
![](Matrix_table.png)
we could see the effect of the number of months on the Sales. For example, Volkswagen was sold only in January, hence the low number of sales, unlike the top brands which were sold throughout the year

## Conclusions & Recommendations
- All branches should endeavor to have the top 5 brands(Reason been that 90% of sales where from it)
- An increase in the models in all the branches having at least 3 models which may attract more customers.
- Brands made available all year round
- Promotional measures such as dicounts and bonaza could be introduced to bottom Brand, location in orther to boast Sales
- However, further research and investigation could be carried out to ascertain if these brands' models will be viable.

![](tank_you_image.jpg)


  
