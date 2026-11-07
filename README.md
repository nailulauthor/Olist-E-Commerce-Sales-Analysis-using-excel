# Olist-E-Commerce-Sales-Analysis-using-excel
**Project Type :** Data Analytics Portfolio Project.

Using Microsoft Excel to analyze sales performance, seller distribution by city, product category performance, and freight costs to evaluate marketplace business performance.

## Introduction
Olist is an e-commerce marketplace in Brazil that connects various sellers with customers through a digital platform. To understand the marketplace's business performance, it is important to analyze sales contributions, seller activity across different regions, product category performance, and freight cost structures. This project aims to analyze Olist transaction data to identify key sales contributors, understand seller performance by city, evaluate product category contributions, and examine the proportion of freight costs compared to product sales. The analysis is conducted using Microsoft Excel, utilizing data processing, data modeling, calculations, and interactive visualizations to create a dashboard that supports data-driven business performance evaluation.

## Project Goals
1. **Sales Performance Analysis** : Analyzing revenue growth and order volume to identify sales trends, fluctuations, and the relationship between order volume and sales value over time.
2. **Product Category Performance Analysis** : Comparing product category performance based on the number of orders, revenue, revenue contribution, and average product price to identify the categories with the highest transaction activity and revenue contribution.

## Data Source

The dataset used in this project is the Brazilian E-Commerce Public Dataset by Olist, which is publicly available on Kaggle. Here is a [link to the dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data) for your reference.
The tables used in the analysis include :
| Dataset                   | Information Used                                 |
| :------------------------ | :----------------------------------------------- |
| olist_orders_dataset      | order_status, order_purchase_timestamp, order_id |
| olist_order_items_dataset | price, product_id, order_id                      |
| olist_products_dataset    | product_id, product_category_name                |

Sales performance analysis uses orders with a delivered status as the basis for measuring successfully completed orders.

## Tools and Features Used

1. **Power Query** : Importing, cleaning, transforming, and preparing data before using it for analysis.
2. **Power Pivot** : Building data models and managing relationships between tables to support cross-table analysis.
3. **DAX (Data Analysis Expressions)** : Creating measures to calculate sales and product category performance indicators.
4. **PivotTable** : Summarizing and comparing data based on time periods and product categories.
5. **PivotChart** : Visualizing sales trends, comparisons, and contributions.
6. **Slicer and Timeline** : Providing interactive filters to explore data based on product categories and time periods.

## Analysis Workflow
### Data Prepation
The data was prepared using Power Query through a process of examining table structures, data types, missing values, and duplicates. This stage aimed to ensure that the data had an appropriate structure before being used for data modeling and analysis.

### Data Modeling and Calculations
Power Pivot was used to build the data model and establish the necessary relationships between tables. Furthermore, DAX was used to create measures as the basis for calculating business performance indicators.

### Sales Performance Analysis
The analysis was conducted to understand the development of revenue and order volume over time. The observation focused on sales trends, fluctuations across periods, and the relationship between revenue and the number of orders.

### Product Category Performance Analysis
The product category analysis was conducted by comparing the number of orders, revenue, revenue contribution, and average product price. This comparison aimed to identify differences in category characteristics based on transaction activity and revenue contribution.

## Analysis Results and Key Findings
### Sales Performance Analysis
#### Key findings
1. Revenue shows an upward trend from one period to another, despite experiencing fluctuations in certain periods, with revenue increasing from BRL 13.497 in the initial period to BRL 83.857.664  in the final period.
2. The largest increase in revenue occurred in November 2017, with revenue rising by BRL 33.951.772 or 52% compared to the previous month.
3. The number of orders and revenue show a consistent trend. As the number of orders increases, revenue also tends to increase.
4. September and December 2016 were periods with very low order volumes, each recording only one order.
5. In November 2016, no orders were recorded.

#### Business Implications
The upward trend in revenue from one period to the next indicates an improvement in the sales performance of the Olist marketplace. The increase in revenue, accompanied by a rise in the number of orders, suggests a relationship between customer transaction activity and the marketplace's revenue growth. This condition presents an opportunity for Olist to sustain business growth through the development of marketing strategies, enhancement of product attractiveness, and optimization of the customer shopping experience to encourage an increase in transaction volume.

Nevertheless, revenue fluctuations across several periods indicate that sales growth has not yet been consistent. The largest revenue increase occurred in November 2017, amounting to BRL 33.951.772, or 52% compared to the previous month. This indicates the potential for significant revenue growth during certain periods. Therefore, Olist needs to evaluate the factors contributing to this increase so that effective strategies can be maintained and further developed in subsequent periods.

Furthermore, the low number of orders in September and December 2016, with only one order recorded in each month, as well as the absence of recorded orders in November 2016, indicate periods of very limited transaction activity. This situation requires Olist's attention to evaluate sales performance while ensuring the completeness of transaction records. If these figures reflect low purchasing activity, the marketplace needs to identify the underlying factors and optimize its marketing strategies to increase transaction volume. Meanwhile, if the situation is related to limitations in data recording, improvements to transaction data management and monitoring systems are necessary to ensure that the information generated accurately reflects actual business conditions.

Overall, Olist needs to maintain a balance between revenue growth and consistency in the number of orders. Regular monitoring of sales performance can help the marketplace identify changes in transaction trends, evaluate the effectiveness of business strategies, and determine appropriate actions to sustain revenue growth and ensure the long-term sustainability of business activities.

### Product Category Performance Analysis
#### Key Findings
1. The bed_bath_table category ranks first among the top five product categories in terms of the number of orders, with a total of 9.272 orders, followed by the health_beauty category with 8.647 orders. This indicates a high level of customer demand and transaction activity in the bed_bath_table category.
2. The health_beauty category generates the highest revenue among the top five categories, amounting to BRL 123.313.172, with a contribution of 9%, despite ranking second in terms of the total number of orders, with 8647 orders.
3. Based on the analysis of average product prices across the top five categories by revenue, the watches_gifts category ranks first, with an average product price of BRL 19.904, followed by health_beauty in second place, with an average product price of BRL 13.028. Meanwhile, the bed_bath_table category ranks fifth, with an average product price of BRL 9.344. These findings indicate that health_beauty has a higher average product price than bed_bath_table, which contributes to its higher revenue despite having a lower number of orders.
4. Among the top five categories by contribution revenue, the contribution of each category is relatively evenly distributed, with an average contribution of 8% and an average difference of approximately one percentage point.

#### Business Implications
The difference between the category with the highest number of orders and the category with the highest revenue indicates that transaction volume does not always correspond to the level of revenue contribution. The bed_bath_table category has the highest number of orders, totaling 9.272 orders, while the health_beauty category generates the highest revenue, amounting to BRL 123.313.172. This condition indicates that product category performance should not be evaluated solely based on the number of orders but should also take into account the revenue generated.

This difference is also related to the average product prices of each category. The health_beauty category has an average product price of BRL 13.028, which is higher than that of bed_bath_table, at BRL 9.344. Therefore, the marketplace needs to develop marketing strategies based on the characteristics of each category. For the bed_bath_table category, the marketplace can increase product visibility and encourage sellers to optimize product variety and information to maintain high transaction activity. Meanwhile, for the health_beauty category, the marketplace can maintain product attractiveness through relevant promotions and programs that encourage repeat purchases to sustain its revenue contribution.

Furthermore, the watches_gifts category has the highest average product price, at BRL 19.904. This condition indicates the potential for relatively high transaction values in this category. The marketplace can support the development of this category by increasing product visibility and implementing marketing strategies that align with its product characteristics, thereby expanding customer reach and encouraging an increase in the number of orders.

On the other hand, the revenue contributions of the top five product categories show a relatively balanced distribution, with an average contribution of 8%. This indicates that the marketplace's revenue is not generated solely by one particular product category. Therefore, the marketplace needs to maintain product category diversity and develop marketing strategies that align with the potential of each category. These efforts can help sustain revenue contributions across various categories while reducing dependence on any particular product category.

## Recommendations 
Based on the results of the sales performance and product category performance analyses, Olist is recommended to implement an integrated and data-driven business strategy to sustain revenue growth, increase transaction activity, and strengthen the overall performance of the marketplace.

First, Olist needs to develop consistent and targeted marketing strategies to increase the number of transactions while maintaining revenue growth. These strategies can be implemented through regular promotional campaigns, discount vouchers for customers, shipping subsidies, and special offers during periods of low transaction activity. In addition, Olist needs to evaluate the factors contributing to the significant revenue increase in November 2017, which reached 52% compared to the previous month. This evaluation may include changes in the number of orders, transaction values, product category contributions, and the effectiveness of marketing programs implemented during that period. The evaluation results can be used as a basis for identifying effective strategies and developing similar marketing programs in subsequent periods. In this way, Olist can sustain revenue growth while reducing fluctuations in transaction activity across periods.

Second, Olist needs to optimize its marketing strategies based on the characteristics and performance of each product category. The bed_bath_table category, which has the highest number of orders at 9.272, should be supported through increased product visibility on the marketplace, such as featuring products on recommendation pages, promotional pages, or dedicated category campaigns. Furthermore, Olist can enhance product attractiveness by encouraging more informative product descriptions and images, as well as a wider variety of product options. Meanwhile, the health_beauty category, which generates the highest revenue of BRL 123.313.172, should be prioritized through relevant promotional campaigns, product recommendations, and repeat-purchase programs to maintain customer interest and revenue contributions. Olist should also optimize the potential of the watches_gifts category, which has the highest average product price at BRL 19.904, by increasing product exposure and implementing marketing campaigns during specific occasions, such as holidays and special celebrations. These strategies are expected to expand customer reach and encourage transaction growth in each category according to its respective potential.

Third, Olist needs to maintain product category diversity to ensure a balanced distribution of marketplace revenue contributions. This recommendation is based on the analysis results, which show that revenue contributions from the top five product categories are relatively evenly distributed, with an average contribution of approximately 8%. This condition indicates that marketplace revenue does not depend solely on one particular product category. Therefore, Olist needs to maintain product availability and category diversity while providing marketing exposure that aligns with the potential of each category. In addition, the number of orders, total revenue, average product prices, and revenue contributions of each category should be evaluated regularly to identify high-performing categories as well as those with further growth opportunities. Through these strategies, Olist can maintain a balanced revenue distribution, expand product choices for customers, and reduce the risk of excessive dependence on particular product categories.

Fourth, Olist needs to improve its transaction performance monitoring and marketplace data management systems to ensure that the information used for business decision-making accurately reflects actual conditions. This recommendation is based on the findings of very low transaction activity in September and December 2016, with only one order recorded in each month, as well as the absence of recorded orders in November 2016. Olist needs to evaluate whether these conditions genuinely reflect low purchasing activity or are caused by issues in transaction data recording. These efforts can be implemented through data validation systems, regular monitoring of order volumes and revenue, and verification of transaction data completeness. Furthermore, Olist needs to monitor marketplace performance indicators, such as the number of orders, total revenue, revenue growth across periods, average transaction value, and revenue contributions from each product category. This information can be used to identify changes in transaction activity, evaluate marketing strategy effectiveness, and determine appropriate business actions based on marketplace conditions.

Overall, Olist needs to focus on developing consistent marketing strategies, optimizing marketing efforts based on product category characteristics, maintaining product category diversity, and improving transaction performance monitoring systems. As a marketplace, Olist's success in sustaining business growth depends not only on increasing transaction volume but also on the platform's ability to provide diverse product choices, enhance the attractiveness of its offerings, and facilitate transactions between customers and sellers. Through the implementation of these strategies, Olist is expected to increase transaction activity, optimize revenue potential across various product categories, maintain consistent sales performance, and support the long-term sustainability of marketplace business growth.

## Analysis Limitations
1. The sales performance analysis focuses on orders with a delivered status as a representation of successfully completed orders.
2. The product category analysis focuses on comparing the number of orders, revenue, revenue contribution, and average product prices.
3. Business recommendations are interpretations based on patterns identified in the dataset and do not represent the results of direct testing of marketing or promotional strategy effectiveness.

## Project Information
1. Tools : Microsoft Excel 2021
2. Data Preparation : Power Query
3. Data Modeling : Power Pivot
4. alculations : DAX
5. Analysis : PivotTable
6. Visualization : PivotChart
7. Interactivity : Slicer












