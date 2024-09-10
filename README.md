# Coffee Shop Sales Analysis

## Table of Contents
- [About Project](#about-project)
- [Problem Statement](#problem-statement)
- [Questions](#questions)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Full Dashboard](#full-dashboard)
- [Key Insights](#key-insights)
- [Answers](#Answers)
- [Recommendation](#recommendation)

## About Project
The Coffee Shop is a prominent and influential company in the beverage industry in the United States. It operates across four major markets in 20 states, offering a range of premium coffee, tea, espresso, and herbal tea products.

This project focuses on analyzing the company's sales data between 2021 and 2022, identifying patterns in key performance indicators (KPIs), and finding ways to improve sales performance in specific regions and product categories.

## Problem Statement
Despite its success, the Coffee Shop faces challenges in certain regions, particularly in the East and South, due to customer dissatisfaction and shifting consumer preferences (from Espresso to Tea). This has impacted sales, revenue, and overall profit margins. The objective of this study is to leverage Business Intelligence (BI) to address these issues by:
- Identifying underperforming areas and product categories.
- Finding ways to drive higher sales in those regions.
- Tailoring products to meet specific regional demands.

## Questions
- Which region generates the highest sales and profit margins?
- What is the sales distribution by state?
- How does the performance of different product types vary?
- Which products and markets are underperforming?

## Data Cleaning and Transformation

- **Data Source**: The dataset used for this analysis was sourced from Kaggle and can be found here: [Coffe shop dataset.xlsx](https://github.com/user-attachments/files/16955835/Coffe.shop.dataset.xlsx). The data was cleaned using Excel and Power Query. Data preparation involved removing unnecessary columns (e.g., Inventory, Marketing, Area Code) and adding new columns such as Sales Variance, Profit Variance, COGS Variance, Date by Year.

- **Power BI Transformation**: The dataset was imported into Power BI, where further calculated columns were created for deeper analysis, using DAX functions.
  - Sales Variance = [Sales] - [Budget Sales]
  - COGS Variance = [COGS] - [Budget COGS]
  - Profit Variance = [Net Profit] - [Budget Profit]


## Full Dashboard

![Coffee Shop Sales Analysis](https://github.com/user-attachments/assets/e4701e1d-2c67-4077-8c0a-3142963c2d16)

## Key Insights

1. **Sales by Market**:
   - The West region had the highest total sales at $272K, followed closely by the Central region with $265K. The East and South regions underperformed.

    ![Sales by Market](https://github.com/user-attachments/assets/4365b6b0-2bc2-4b35-97fd-5c6e83e7c4fa)

   - The Central region stands out with the highest Net Profit at $94K, followed by the West with $74K and the South with the lowest at $32K.

     ![Sales and Net Profit by Market](https://github.com/user-attachments/assets/b4f3ceaf-24b7-4058-b173-92fd78800f80)

3. **Product Performance**:
   - Colombian coffee led the sales at $128K, while Regular Espresso was the least popular at $24K.
   
    ![Sales by Product](https://github.com/user-attachments/assets/7857ac66-8036-4c2c-b769-145aa84907a3)

4. **State Sales Distribution**:
   - California accounted for the highest sales at $97K, followed by New York and Illinois.
   
    ![Total Sales by State](https://github.com/user-attachments/assets/a59363c2-38d9-4315-81e9-f64d4e0ed81c)

5. **Variance Analysis**:
   - Sales variance showed significant growth in 2022 compared to 2021, especially for Espresso, Coffee, and Tea products.
   
    ![Sales Variance by Date](https://github.com/user-attachments/assets/62b3f865-0315-4276-8e0a-939eb4f58d64)

## Answers

1. Which region generates the highest sales and profit margins?
According to the "Sales and Net Profit by Market" chart, the West region generates the highest total sales ($272K) followed closely by the Central region ($265K). However, when looking at Net Profit, the Central region stands out with the highest at $94K, followed by the West with $74K.

This indicates that while both regions perform well in terms of sales, the Central region has a better profit margin, possibly due to lower expenses or higher profitability.

2. What is the sales distribution by state?

According to the "Total Sales by State" chart,  California leads with $97K in total sales, followed by New York with $71K, and Illinois with $70K. These three states account for a significant portion of total sales.

The distribution shows that a few key states dominate the sales figures, especially in the West and Central regions, while other states contribute less significantly.

3. How does the performance of different product types vary?

The "Sales by Product" chart shows that Colombian coffee is the top performer with $128K in sales, followed by Lemon with $96K, and Caffe Mocha with $85K. On the lower end, Regular Espresso is the least-performing product with $24K in sales.

This indicates a clear preference for Colombian coffee, with espresso-based drinks generally performing well, while Regular Espresso has the lowest demand.

4. Which products and markets are underperforming?

The "Sales and Net Profit by Market" chart shows that East and South regions are underperforming, with sales at $179K and $104K, respectively, and low net profits ($59K in East and $32K in South).

In terms of product performance, as highlighted in the "Sales by Product" chart, Regular Espresso and Amaretto are underperforming compared to other products, generating the lowest sales figures of $24K and $26K, respectively.

## Recommendation
- **Boost Sales in East and South**: Tailor marketing strategies and promotional offers to increase customer satisfaction and product visibility in underperforming regions (East and South).
- **Focus on Popular Products**: Allocate more resources towards promoting Colombian coffee and other high-performing products.
- **Optimize Underperforming Products**: Assess reasons for low performance in products like Regular Espresso and explore ways to improve customer engagement with these products.
- **Leverage BI Insights**: Continue using Business Intelligence tools to monitor sales trends and adapt strategies accordingly.
