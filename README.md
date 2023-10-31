# Gloabal Superstore

## Table of Content
- [Project Overview](Project.Overview)
- [Data Source](Data.Source)
- [Tools](Tools)
- [Project Structure](Project.Structure)
- [Data Cleaning](Data.Cleaning)
- [Exploratory Data Analysis(EDA)](Exploratory.Data.Analysis (EDA))
- [Data Insight](Data.Insight)
- [Results/Findings](Reslts/Findings)
- [Recommendation](Recommendation)
- [Refrence](Reference)


## Project Overview
---
Global Superstore, headquartered in New York, is a prominent online retailer with an extensive product portfolio, dedicated to becoming the ultimate shopping destination for its global customer base. Serving clients from 147 different countries, the superstore offers access to a diverse array of over 10,000 products. This comprehensive selection encompasses three primary categories: office supplies (for instance, staples), furniture (including items like chairs), and technology products (featuring smartphones).

The objective of this project is to assist Global Superstore in analyzing and extracting valuable insights from the Superstore dataset. These insights are intended to provide management with the knowledge needed to make informed decisions that enhance overall performance and profitability


## Data Soure
---
This dataset was provided at the conclusion of the training program conducted by Digitaley Drive as the final project. Below is the link to the data set


[Download here](https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281)


## Tools
- Power query - Cleaning and Modeling
- Power Bi - Visualization
- Github - Documentation


## Project Structure
 This project was executed following the subsequent process.

- Data Collection

This initial phase of the project delves into acquiring the Global Superstore data set. The dataset was provided by the academy following the successful completion of our training. 

- Data Cleaning

 The Data Cleaning phase is an integral step in any data analysis project. In this section, i meticulously outline the procedures and techniques employed to ensure that the dataset is accurate, reliable, and ready for analysis within Power BI. This process encompasses data validation, removal of duplicates, handling missing values, and addressing any anomalies or inconsistencies present in the raw data. The goal is to create a clean and structured dataset that forms the basis for our insights and visualizations and this was done using power query.

- Data Visualization

 Data Visualization, a critical aspect of data analysis. This phase involves the development of an interactive and insightful dashboard within Power BI. Through this dashboard and accompanying reports, I present a comprehensive view of Global superstore sals report. My visualization offer a deeper understanding of the key performance metrics, the profitable countries, profitable regions and sub category and other measures . Utilizing charts, graphs, and tables, I bring the data to life, enabling stakeholders to quickly grasp the insights derived from the dataset.
 
- Data Documentation

Upon the completion of the analysis, I understand the importance of clearly communicating the findings and recommendations. To this end, I have created a detailed documentation repository on GitHub. This documentation is a valuable resource that explains the insights I derived from the dataset, offering explanations of the insights I have extracted from the dataset and delivering a comprehensive summary of the recommendations. It equips the management of Global Superstore with the insights required for making informed decisions aimed at improving overall performance and profitability.


## Data Cleaning 
I imported the dataset into Power Query for data cleaning and transformation. The data set had 3 tables known as Orders, people and returns ,During this process, I observed that the 'Postal code' under the Order table  was 80% Null, i replaced the null value to '0' , i merged the retuns table with the order table using vlookup on Microsoft Excel. Additionally, I performed a thorough data validation and quality check on all rows and columns in the dataset to maintain its accuracy and integrity. After ensuring the dataset met the necessary quality standards, I closed the data transformation process and loaded it into Power BI for further analysis. 




## Exploratory Data Analysis(EDA)
Exploratory Data Analysis (EDA) is a crucial step in our approach to the Global Superstore dataset. It involves diving deep into the data to answer essential questions that underpin our analysis and decision-making. These questions are 
  
Question 1.

a) What are the three countries that generated the highest total profit for Global Superstore in 2014?

b) For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?

Question 2.

a) Identify the 3 subcategories with the highest average shipping cost in the United States.

Question 3.

a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries?

b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate shipping costs and the average discount as potential root causes.

Question 4.

a) Identify the product subcategory that is the least profitable in Southeast Asia.

b) Is there a specific country in Southeast Asia where Global Superstore should stop offering the subcategory identified in 4a?

Question 5.

a) Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?

Question 6.

a) Which product subcategory has the highest average profit in Australia?

Question 7.

a)Who are the most valuable customers and what do they purchase?



## Data Analysis 

In the financial landscape of Global Store for the year 2014, three countries emerged as significant profit drivers: the United States, China, and India.

The United States had an impressive profit of $39,936.85, highlighting its pivotal role as a major revenue source for the company.

China secured the second spot, contributing a commendable $8,421.33 to the overall profits. The Chinese market's dynamic growth played a key role in this achievement.

India, in the third position, made a noteworthy contribution with a profit of $7,330.95. This underscores the growing influence of the Indian market on Global Store's financial performance.

Together, these three countries played a pivotal role in shaping Global Store's profitable journey in 2014."

- Here is a breakdown of the countries and products that have contributed the most to our profitability


**Most Profitable product in United States and their profits**

|Product Name |Profit|
|----------------|-------------------|
|canon imageCLASS 2200 Advanced copier|25,199.993|
|fellowes PB500 electric plastic Comb Binding Machine with Manual Bind|7,753.04 |
|Hewlett Packard Laserjet 3310 Copier| 6,983.88 |
|Total| 39,936.85|

**Most Profitable Product In China and their Profits**

|Product Name |Profit|
|------------------|--------------------|
|Sharp wireless Fax, Digital|2,894.10|
|Hp Copy Machine, Color|2,855.13|
|Samsung Smart Phone, VolP|2,672.10|
|Total|8,421.33|



|**Most Profitable Product In India and their Profits**

|Product Name |Profit|
|--------|--------|
|Sauder Classic Bookcase,Traditional        |2,903.58|
|Apple Smart Phone, with Caller ID          |2,817.99|
|Cisco Smart Phone with Caller ID   |1,609.38|
|Total|7,330.95|


**The 3 subcategories with the highest average shipping cost in the United States**

To answer this i had to get a valuable insights into the shipping dynamics in the United States, shedding light on the cost structures that impact these specific product groups and their implications for the business's overall financial performance."
In the context of shipping costs within the United States, it's interesting to note that there were three distinct subcategories that stood out with the highest average shipping expenses. These subcategories are Chairs, Phones, and Storage, and they played a pivotal role in shaping the shipping cost dynamics.

Among these, Chairs ranked as the subcategory with the highest average shipping cost, coming in at a notable 58.43%. Phones secured the second position with an average shipping cost of 41.02%. The popularity and demand for phones, coupled with their shipping costs, add an interesting dimension to the overall profitability analysis.
Lastly, the subcategory of Storage emerged as the third highest, with an average shipping cost of 27.31%. The expense of shipping these items serves as a key consideration for profit margins and logistical decisions.


![shipping cost in United states ](https://github.com/chieduife/Global-Superstore-Dashboard/assets/148073427/d0f3d4d5-1353-49c2-bd86-6fab344b38e3)


**Nigeria’s profitability  for 2014. How does it compare to other African countries?**


The total sales figures reached 54.4k. Notably, Nigeria incurred a significant loss of -80.8k. A detailed analysis of the situation revealed that this loss could be attributed to both high shipping costs and a substantial average discount offered in Nigeria. Interestingly, in contrast to Nigeria, other countries with high shipping costs did not provide comparable discounts.

South Africa stood out as a notable exception, boasting both the highest profit and the highest shipping costs. This suggests that South Africa's favorable profit margins effectively balanced the associated shipping expenses.

Conversely, Zimbabwe and Uganda also extended discounts to their customers. However, their losses, while still concerning, were less severe than Nigeria's. This could be attributed to these countries having comparatively lower shipping costs, which somewhat mitigated the impact of discounts on their overall financial performance.

The collective sum of sales in the remaining African countries reached an impressive 729.4k and their combined profit totaled 169.6k.


**The least product subcategory profitable in Southeast Asia and the specific country in Southeast Asia where Global Superstore should stop offering the subcategory with the least profit**

The Southeast Asian countries included in this analysis are Malaysia, Indonesia, Philippines, Thailand, Vietnam, Cambodia, Singapore, and Myanmar. Within these countries, a wide range of subcategories was offered, including Phones, Copiers, Appliances, Bookcases, Machines, Chairs, Storage, Binders, Furnishing, Labels, Art, Fasteners, Paper, Supplies, Accessories, and Tables.

Remarkably, among all these subcategories, 'Tables' emerged as the least profitable with a negative profit of -19k in the Southeast Asian region. In contrast, 'Phones' was the most profitable subcategory, generating a profit of 13k.

Given the substantial loss associated with 'Tables' in Indonesia, it may be advisable to reconsider the supply of this subcategory in that Global Superstore to avoid further financial setbacks.


**Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?**

Amongst the cities in the United States, Concord stands out with the lowest profit, amounting to a significant loss of •23.18. A closer look at the chart reveals that Concord grapples with high shipping costs paired with minimal discounts. High shipping costs can deter customers from making purchases due to elevated selling prices, causing them to seek local alternatives. Conversely, offering limited discounts may discourage frequent buying, leading to financial losses.

To enhance profitability in Concord, it is advisable for the company to reevaluate its pricing strategy. This could involve exploring avenues to mitigate shipping costs or providing more enticing discounts to motivate customers to make more frequent purchases. A profound understanding of local market dynamics and customer preferences in Concord is pivotal in crafting a strategy that can reverse the current situation and restore profitability



**Which product subcategory has the highest average profit in Australia?**
Australia offers a diverse array of subcategories, encompassing Phones, Copiers, Appliances, Bookcases, Machines, Chairs, Storage, Binders, Furnishing, Labels, Art, Fasteners, Paper, Supplies, Accessories, and Tables. Notably, 'Appliances' stands out as the leading subcategory in Australia, having generated a substantial total of 139.



**Who are the most valuable customers and what do they purchase?**

Below is a list of our most profitable customers and what they purchase from us


|Name of Customer|Products they purchased|Country|
|----------------|-----------------------|-------|
|Tamara Chand|Canon imageCLASS 2200 Advanced Copier|United State|
|Raymond Buuch|Canon imageCLASS 2200 Advanced Copier|United State|
|Hunter Lopez|Canon imageCLASS 2200 Advanced Copier|United State|
|Adrian Barton|GBC Ibimaster 500 Manual ProClick Binding System|United State|
|Sanjit Chand|Ibico EPK-21 Electric Binding System|United State|
|Patrick Jones|Hoover Stove, Red|Italy|



## Findings

Throughout the analysis, I have uncovered several key insights and observations.

- Profitable Countries: The United States, China, and India are the countries that have contributed the most to the company's profitability.

- Shipping Costs and Discounts: High shipping costs and substantial discounts in certain countries, such as Nigeria, have resulted in significant financial losses. In contrast, South Africa managed to maintain high profits despite high shipping costs.

- Subcategories in Southeast Asia: Among the subcategories offered in Southeast Asia, 'Tables' was the least profitable, while 'Phones' was the most profitable. The negative profit associated with 'Tables' in Indonesia suggests reconsidering its supply in that market.

- Subcategories in Australia: Australia offers a wide range of subcategories, with 'Appliances' standing out as the highest-performing subcategory, generating a total profit of 139.

These findings offer insights into the company's financial performance, the impact of shipping costs and discounts, and the performance of various products and regions. Further analysis and actions can be based on these findings to enhance profitability and decision-making.

## Recommendations

Here are some overarching recommendations to help improve Global Superstore's performance, enhance customer service, and boost profitability

- Shipping Costs and Discounts: Analyze the impact of high shipping costs and significant discounts in specific regions, such as Nigeria. Consider adjusting pricing or discount strategies to balance profitability.

- Subcategories Strategy: Review the profitability of subcategories in different markets. If certain subcategories consistently result in losses, consider discontinuing or optimizing their supply in those regions.

- Market Focus: Given the profitability of countries like the United States, China, and India, consider expanding marketing and sales efforts in these markets to further boost profitability.

- Customer Insights: Explore and analyze the characteristics and behaviors of the most profitable customers to identify patterns that can be leveraged to attract and retain similar customers.

- Product Mix: Evaluate the product mix in Australia, with 'Appliances' performing well. Consider promoting or expanding the offerings in this category if it aligns with your overall business strategy.

- Data-Driven Decisions: Continue to use data analysis and insights to inform business decisions and strategies. Regularly monitor and adapt to changing market dynamics to maintain and improve profitability.

- Pricing Strategy: Carefully evaluate the impact of discounts and shipping costs in different regions. Adjust pricing strategies to maximize profitability while remaining competitive.   

By incorporating these recommendations into Global Superstore's operations and strategy, the aim is to drive better performance, enhance customer satisfaction, and ultimately boost profitability. These actions should be guided by a commitment to data-driven decision-making and a focus on meeting customer needs.



## Reference 
[Link to Dataset](https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281)







