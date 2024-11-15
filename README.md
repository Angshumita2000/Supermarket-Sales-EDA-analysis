# Supermarket-Sales EDA analysis (answering common question by the stakeholders)

# Project Background
The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. Predictive data analytics methods are easy to apply with this dataset. 
# Attribute information
* Invoice id: Computer generated sales slip invoice identification number
* Branch: Branch of supercenter (3 branches are available identified by A, B and C).
* City: Location of supercenters
* Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
* Gender: Gender type of customer
* Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
* Unit price: Price of each product in $
* Quantity: Number of products purchased by customer
* Tax: 5% tax fee for customer buying
* Total: Total price including tax
* Date: Date of purchase (Record available from January 2019 to March 2019)
* Time: Purchase time (10am to 9pm)
* Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
* COGS: Cost of goods sold
* Gross margin percentage: Gross margin percentage
* Gross income: Gross income
* Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)
 # Data Source : [https://kaggle.com/datasets/aungpyaeap/supermarket-sales]

With this given dataset the following questions are being answered. Insights and recommendations are provided on the following key areas:
- **What are the key factors driving revenue and profitability across different branches and product lines?**
- **How do customer demographics (such as customer type and gender) impact purchasing behavior and product preferences?**
- **What are the patterns or trends in customer satisfaction ratings across branches, times, or product lines?**
- **Which payment methods are most popular, and do they correlate with larger purchases or specific customer segments?**
- **Are there seasonal or time-based trends in sales volume, and how can we leverage them to maximize peak times?**
 
An interactive Tableau dashboard used to report and explore sales trends can be found here [https://public.tableau.com/shared/HH3ZW6RF8?:display_count=n&:origin=viz_share_link] .



# Data Structure & Initial Checks

The companies main database structure as seen below consists of two tables: table 1 and table 2 with a total row count of 1000 records. A description of each table is as follows:
- **Table 1:**<img src="https://github.com/Angshumita2000/Supermarket-Sales/blob/main/gilmpse%20of%20data.png" alt="glimpse of data" height="500" width="1000"/>
- **Table 2:**<img src="https://github.com/Angshumita2000/Supermarket-Sales/blob/main/summary%20data.png" alt="summary of data" />


[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### What are the key factors driving revenue and profitability across different branches and product lines?:

* **Main insight 1.**
  The primary factors driving revenue are **product line performance**, **branch differences**, and **customer type**. Branch C shows the highest revenue, driven by strong sales in high-demand product lines like 'Food and beverages' and 'Fashion Accessories.' In terms of profitability, All branches stand out due to high gross margins in specific product lines, suggesting that operational efficiencies or customer preferences may play a role.  For 'A' it is:'Home and lifestyle', 'sports and travel', 'Electronic'. For 'B' it is ; 'Sports and travels', 'health and beauty'. For 'C' it is 'Food and beverages and Fashion Accessories'.
  
* **Main insight 2.**
   In branch 'A''s  product line of 'health and beauty','food and beverages', 'Fashion Accessories' having a high gross margin percentage means a company is keeping a large portion of its sales revenue as profit after subtracting the cost of goods sold, indicating efficient cost management and potentially higher profitability, while having "low gross income" means the company is generating a relatively small amount of profit from sales, even if their gross margin percentage is high, which could be due to low sales volume.On the other hand, Branch 'B' is being efficient in selling 'Sports and travel'. But in other product lines, special mention , 'Fashion accessories ' and 'food and beverages' having low gross income.
  
* **Main insight 3.** In Branch 'C' the story is quiet opposite from branch 'A'. It is giving higher revenue in products like, 'Food and beverages', 'Fashion Accessories'. While bringing low revenue in ' Home and life style ' and 'health and beauty'. Although Branch 'B' produce most revenue and efficient in selling ' Sports and Travel', Among the 3 branches it sells 'Health and beauty' efficiently.
  
* **Main insight 4.** Branch C shows the highest revenue, driven by strong sales in high-demand product lines like 'Food and beverages' and 'Fashion Accessories.' In terms of profitability, All branches stand out due to high gross margins in specific product lines, suggesting that operational efficiencies or customer preferences may play a role.  For 'A' it is:'Home and lifestyle', 'sports and travel', 'Electronic'. For 'B' it is ; 'Sports and travels', 'health and beauty'. For 'C' it is 'Food and beverages and Fashion Accessories'.

<img src="https://github.com/Angshumita2000/Supermarket-Sales/blob/main/Story1%20animation.gif" alt="Tablaeu story 1" />
[https://public.tableau.com/app/profile/angshumita.sarkar/viz/shared/HH3ZW6RF8]


### How do customer demographics (such as customer type and gender) impact purchasing behavior and product preferences?:

* **Main insight 1.** After analyzing the purchasing patterns, we see that members tend to purchase more frequently and spend more per visit compared to non-members, especially in  categories like Food and brvarages and Home & Lifestyle, and Sports and travel. Aditinally, Female basket size, means the item grabbed each visit is 9.7% more than a male customer. And they tend to give, 9.2$ more revenue on an average.
* <img src="https://github.com/Angshumita2000/Supermarket-Sales-EDA-analysis/blob/main/How%20do%20customer%20demographics%20(such%20as%20customer%20type%20and%20gender)%20impact%20purchasing%20behavior%20and%20product%20preferences_%20(1).png" alt="viz1" />
  
* **Main insight 2.** Additionally, **female customers** appear to **less prefer** categories like **Health & Beauty**, yet they **prefer** **Food and beverages** more. There’s also a trend of **male members** favoring **Health& beauty**, **sports and beverages**, **electronics**, potentially indicating a high-value demographic that could be targeted with loyalty incentives.
* <img src="https://github.com/Angshumita2000/Supermarket-Sales-EDA-analysis/blob/main/How%20do%20customer%20demographics%20(such%20as%20customer%20type%20and%20gender)%20impact%20purchasing%20behavior%20and%20product%20preferences_.png" alt="viz2" />
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### What are the patterns or trends in customer satisfaction ratings across branches, times, or product lines?:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Which payment methods are most popular, and do they correlate with larger purchases or specific customer segments?:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]

### Are there seasonal or time-based trends in sales volume, and how can we leverage them to maximize peak times?:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 5]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
