# Flipkart-Sales-Analysis
## Background
Founded in 2007, Flipkart is a prominent e-commerce company based in India. Over its relatively short lifespan, Flipkart has established itself as a major player in the online retail market, offering a diverse range of products including electronics, fashion, and home essentials. Despite its success, the e-commerce landscape is becoming increasingly competitive, demanding constant innovation and improvement to maintain market leadership. 

The e-commerce sector has experienced rapid growth and heightened competition in recent years. To stay ahead, Flipkart must continuously enhance its operations, customer experience, and strategic decision-making processes. This necessitates a deeper understanding of business activities and consumer behaviors, which can be achievable through effective data analysis and modeling. 

The given dataset provides information about past orders by our customers from April 2018 to end of March 2019, order details, and monthly sales targets over this observation period. 

##Problem Statement 
Given the growing competition in the e-commerce market, how can Flipkart optimize its sales strategies to maximize revenue and profitability across various product categories? 

##Goal
This data analysis project is directed toward the CEO of Flipkart (as a school assignment). The goal is to conduct a comprehensive analysis about past sales trends and develop actionable insights and strategies to enhance the company's operations and drive sales growth.

It will mainly address the 4 questions that the CEO of the company is concerned about:
1.	Which period (month) has the most sales?
2.	What are the top 5 most popular products?
3.	What are the top and bottom locations by profit?
4.	What is our customer profile?

## Dashboards
### 1. Which month has the most sales? 
**a) Overview of the sales**
![image](https://github.com/user-attachments/assets/fe7dd66b-b44d-4161-aebb-ab7ffa4b5b55)
This dashboard provides a detailed monthly sales analysis, offering valuable insights into the sales performance for each month. 

Key Insights: 
* Overall sales exceed the target. January exceeded the target the most, while July fell farthest behind.
* Sales are inconsistent over time, with a decreasing trend observed starting from April 2018, dropping to the lowest in July.
* There is a notable sharp increase in sales in August 2018 and between October to November, suggesting successful promotional campaigns or seasonal demand.
* Profit remained low and negative for most of 2018, indicating losses. From October 2018 onwards, we observed both sales and profit increase, showing recovery and improvement. Both sales and profit peaked in November 2018, January, and March 2019.

**b) Diving into the lowest sales month**
![image](https://github.com/user-attachments/assets/1051cdf6-aa20-4a9f-978f-00ca7ab1c64b)
This dashboard provides a more in-depth analysis of the highest sales month, offering insights into daily sales and profit, the amount below or above the target, and the proportion of sold categories for the month.

As identified in the earlier dashboard, January is the month with the highest sales. Thus, this dashboard analyses the data for January. The filter at the top of the dashboard allows for customization, allowing the CEO to choose the month that they want to focus on.

Key insight:
* The Electronics and Furniture categories contributed the highest to the overall sales in January, and the month has recorded sales of more than 61k, which exceeds the target by around 17k.
* The area graph on the left reveals frequent spikes and drops in sales and profit, indicating inconsistency. The 7-day moving average smooths out these spikes and reveals the sales pattern. It indicates higher sales in the latter half of the month. Hence a targeted marketing approach can be conducted to boost sales and profit during these periods for the popular product categories.


### What are the top and bottom 5 locations in terms of profit? 
**a) Overview of the sales by locations**
![image](https://github.com/user-attachments/assets/583ceb44-ede6-4aae-987d-fc43491e6654)
Key insight: 
* The West and Central regions have the highest sales, while the West and North regions generate the highest profit. The map also reflects these sales patterns, showing higher sales density in the Central and West regions, and lower sales in the East and North-East regions.

**b) Top and bottom locations by profit**
![image](https://github.com/user-attachments/assets/b72f1dec-d2af-452e-9619-86cd7778a02c)
Key insight: 
* The top 5 most profitable cities are mainly located in the North, Central and West region, while the bottom 5 profitable cities are mainly located in the Northwest and Southeast region.
* The top city is Pune, which has generated a total of 4.5k in profits, while the worst performing location is Chennai, which has generated a loss of 2.2k.
* Number of customers in the top cities are twice as much as the number of customers in the bottom cities.
* The top 5 most profitable locations have a higher increase in profit compared to the bottom 5 most profitable locations. The city of Indore has shown the highest increase in profit. 

Thus, to enhance overall profitability, we can direct more resources to the identified worst-performing cities by expanding marketing efforts to increase the customer base and implementing successful strategies from top-performing branches. Moreover, we can also target top cities like Indore with specific initiatives to maximize their profitability potential.

### 3. What are the top 5 most popular products (by Category and Subcategory) across different sales channels?
**a) Overview of the top products by category and subcategory.**
![image](https://github.com/user-attachments/assets/a21472fb-073e-4650-b30a-7e7f79668bea)
Key Insights:
* Clothing is the highest-sold category, with Saree, Handkerchief, and Stole being the top subcategories by quantity.
* Printers, Bookcases, and Accessories generate the highest profits, while Electronic Games and Tables have negative profits.
* Products like Tables and Electronic Games could be discontinued or revamped to reduce losses while promoting Printers, Bookcases, Furniture, Sarees, Handkerchiefs, and Stoles can maximize sales and profitability.

**b)Top 5 products most profitable products across different regions (sales channels) in terms of profit**
![image](https://github.com/user-attachments/assets/9d821510-a311-4dc2-8c87-ab0d45844efd)
Key Insights:
* Saree, Stole, and Handkerchief consistently rank as the top 3 most sold sub-categories across most regions.
* The proportion of the three sold categories is similar across regions, except in the East, where clothing and electronics have higher sales, and furniture has significantly lower sales when compared to other regions.

**c) Top 5 products most profitable products across different regions (sales channels) in terms of sales** 
![image](https://github.com/user-attachments/assets/2a0afa55-2752-4dd5-b76d-4ab508f29d8b)
Key Insights:
* Saree is within one of the top categories across all the regions, with the West region having the highest sales at 19K.
* Sales by categories are similar for most of the regions, except for the East where Electronics (46.28%) and clothing (34.61%) occupy a higher proportion of sales compared to Furniture (19.11%). Electronics also has its highest proportion of sales in the East region. 


### 4. What is our customer base? 
![image](https://github.com/user-attachments/assets/8d36ded0-73ac-414e-8f5b-2480e32d4e0a)
Key insights: 
* We have a total of 500 orders over the 12 months, and January 2019 has the highest sales activity.
* We have customers from 24 different cities, and most of our customers are from the West and Central region.
* Our top customer is called Yaanvi, from Madhya Pradesh.

With this, targeted sales strategies can be developed to focus on areas with the highest concentration of customers and peak activity periods. For instance, regions with a higher proportion of customers might benefit from region-specific promotions, discounts, or advertising campaigns. Flipkart can also allocate more resources, such as inventory, staffing, and logistics to prepare for periods of high demand, ensuring a smooth customer experience and maximizing sales opportunities. Additionally, strategies to enhance customer loyalty can be implemented to encourage repeat purchases from top customers like Yaanvi.

## Further Analysis
For further analysis, I plan to conduct a detailed analysis of sales and profit across different categories and locations, to discover key trends and patterns, and forecast future sales 

**Univariate  Analysis**
![image](https://github.com/user-attachments/assets/9ba80c7d-ef01-4ec9-8864-0debd6fc4c8c)
In this univariate analysis of the numerical variables, we found out that most of the orders have sales and profit that are low, close to zero, with some extreme values. From the box plot, most product categories and regions have median profits close to zero, indicating neither significant losses nor gains.

**Bivariate Analysis**
![image](https://github.com/user-attachments/assets/d5220f9f-06b7-49fb-8ef8-50a28f3d17d0)
Overall in this bi-variate analysis, we identified that sales increase as quantity increases, with the Electronics category showing the highest increase in sales. The electronics category also showed the highest profit despite a lower quantity sold and the sales have also increased over time, especially towards the end of the observed period, this shows that it can be a key focus area. both Clothing and Furniture have shown growth but are less consistent.

Cities with more customers contribute more significantly to total profits. Increasing the customer base in different cities could lead to higher overall profits.

**Multi-variate Analysis**

In the multi-variate analysis, PCA was done and the data is being clustered to their natural clusters using k-means clustering. With that, 3 clusters are being formed. Cluster 1 is observed to have the highest average profit and sales, followed by cluster 2 and cluster 0. 
![image](https://github.com/user-attachments/assets/d22b861f-8c1f-4eb3-b4a4-33f7798fd9c7)
In our data mining analysis, we identified product categories and regions. Clusters contain observations from three categories, with some overlap between Clothing and Electronics in clusters 0 and 2, indicating similar attributes or customer behavior. Clusters 1 and 2 mainly represent the west and central regions, suggesting distinct sales dynamics, while cluster 0 contains a mix of all regions, indicating similar sales patterns.


![image](https://github.com/user-attachments/assets/3df86bd4-9e1f-4e3e-8563-3c80f00bca76)
The ARIMA time series analysis, with parameters derived from ACF and PACF, generally follows the original sales data trend and smooths out some peaks. This aids in predicting future sales, planning, and inventory management

## Summary
The primary goal of this data analysis is to leverage the existing datasets on order information and sales targets from April 2018 to the end of March 2019 to develop actionable insights and strategies that will enhance the company’s operations and drive sales growth. To achieve this, we have conducted a comprehensive analysis. Here is a summary of the key findings we have identified.
1.	The month with the identified most sales is January, it has exceeded the target the most. 
* The Electronics and Furniture category has contributed the most sales.
* Sales are higher in the latter half of January, which can be a potential period for targeted marketing. 

2.	The top cities are mainly located in the north, central, and west regions, while the bottom cities are mainly located in the northwest, and south.
* The top profitable cities have twice as many customers as the bottom profitable cities.
* City of Indore shows significant profit growth.

3.	Clothing is the most popular category. Top subcategories include saree, handkerchief, stole, furnishings, and T-shirts.
* Saree remains one of the top sub-categories in terms of sold quantity and profit, with other clothing sub-categories like Stole and Handkerchief being the top 3 most sold sub-categories across all regions. 
* Top products are consistent in terms of quantity sold, but more varied in terms of sales generated across different regions

4.	The West and Central regions have the most customers and the peak activity period for our customers in January. 
o	Our top customer is identified to be Yaanvi from Madhya Pradesh.

In the further analysis, we looked the Uni-Variate, Bi-Variate and Multi-Variate analysis of the sales and profit data, as well as conducting data mining to discover hidden insights. Here is a summary of our key findings. 

1)	Univariate Analysis
* Most of the orders have low sales and profits. There are also large sales transactions but they are rare.
* Extreme losses are mainly identified in the Furniture category and the South region. This suggests potential areas of focus to optimize the profit earned.


3)	Bivariate Analysis
* Sales increase as quantity increases, with the electronics category showing the highest increase in sales.
* We should focus more on the Electronics category, as it demonstrated the highest profit despite a lower quantity sold. Its sales also increased over time, particularly towards the end of the observation period. While clothing and furniture also showed growth, their performance was less consistent.
* Cities with more customers contribute more significantly to total profits. Increasing the customer base in different cities could lead to higher overall profits.

4)	Multivariate Analysis
* PCA was done and the data is being clustered to their natural clusters using k-means clustering
* 3 clusters was formed, cluster 1 is observed to have the highest average profit and sales, followed by cluster 2 and cluster 0. 

5)	Data mining
   
a.	Cluster analysis
* Clusters contain observations from three categories, with some overlap between Clothing and Electronics in clusters 0 and 2, indicating similar attributes or customer behavior.
* Clusters 1 and 2 mainly represent the west and central regions, suggesting distinct sales dynamics, while cluster 0 contains a mix of all regions, indicating similar sales patterns.
  
b.	Time Series Analysis
* A decreasing trend in sales was identified from April to August 2018, followed by a gradual increase from August onward.
* Several irregular spikes are observed particularly from late 2018 to early 2019, and they are smoothed out by the ARIMA model.
* ARIMA forecast then suggested that sales for the upcoming month will be more stable.








