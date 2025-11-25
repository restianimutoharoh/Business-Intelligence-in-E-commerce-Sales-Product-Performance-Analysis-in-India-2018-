# **Business Intelligence in E-commerce Sales: Product Performance Analysis in India (2018)**


## **Executive Summary**


### *Top 5 Best Sub-Category Product by Amount*

### **Insight**

* High sales of printers demonstrate the platform's strength in serving specific market segments.
* This success is driven by a deep understanding of the needs and price sensitivity of segmented consumers.
* There are significant differences in feature and price preferences among different consumer segments.

### **Recommendations**

* Develop pricing strategies specific to each consumer segment.
* Add complementary products (such as ink and paper) to meet the needs of existing market segments.
* Create targeted marketing campaigns tailored to the preferences of each segment.


### *Category Product by Amount*

### **Insight**

* Electronics is the top-selling product category with sales of $166,267, indicating consumers' strong preference for technology products.
* There is great potential to increase sales of the Apparel and Furniture categories, which are still underperforming the electronics category.
* The dominance of electronics creates a great opportunity for cross-selling or bundling strategies of products from other categories.

### **Recommendations**

* Strengthen the strategy for the electronics category by increasing product variety and exclusive promotions.
* Conduct an in-depth analysis to improve sales bottlenecks in the Apparel and Furniture categories.
* Implement cross-selling strategy of electronic products to drive sales of other categories.


### *Amount and Profit by Category*

### **Insight**

* Electronics had the highest sales but the lowest profitability (7.92%), indicating a gap between volume and profit.
* All categories have profit margins below the industry average (10-20%), indicating a large room for efficiency improvement.
* Low margins indicate potential problems with cost structures or overly competitive pricing strategies.


### **Recommendations**

* Prioritize profitability optimization, especially for the electronics category.
* Conduct a comprehensive cost analysis to identify areas for savings.
* Revise pricing strategies, such as using dynamic pricing or bundling.


### *Payment Method*

### **Insight**

* The dominance of COD payments (45.1%) indicates consumers' preference for a sense of security when shopping online.
* The high usage of COD poses significant operational challenges and logistics costs.
* Digital payments account for a large percentage (46.7%), indicating a migration opportunity.

  
### **Recommendations**

* Promote digital payments with incentives to encourage migration from COD.
* Increase consumer confidence in digital payment systems through education and security assurance.
* Optimize the COD logistics process to minimize costs and risks.


### *Top 10 Best Profit by Category & State*

### **Insight**

* Electronics in Uttar Pradesh is losing money with a negative profit margin of -19%.
* This problem is isolated to Uttar Pradesh, in contrast to high profit margins in other regions.
* The decline in Average Selling Price (ASP) indicates an ineffective discounting strategy that is eroding profits.


### **Recommendations**

* Stop non-strategic discounting on electronic products in Uttar Pradesh to stop losses.
* Shift focus to high profit margin markets (such as Madhya Pradesh) to maximize profits.
* Implement a smart and planned discounting strategy, not just to attract customers.


### *Amount, Average Cost, & Profit by Sub-Category*

### **Insight**

* There is an extreme profit difference for handkerchiefs between Madhya Pradesh ($-29) and Maharashtra ($646).
* Negative profits in Madhya Pradesh indicate a cost issue or selling prices that are not sufficient to cover costs.
* This profitability issue could be a systemic issue in Madhya Pradesh as other products are also losing money.


### **Recommendations**

* Conduct an in-depth cost audit in Madhya Pradesh for handkerchiefs and other loss-making products.
* Replicate successful strategies from Maharashtra to Madhya Pradesh to increase profits.
* Thorough evaluation of all operations in Madhya Pradesh to address systemic issues.



## **Project Objectives**

This project aims to analyze e-commerce product sales data in India from 2018 to:
* Evaluate Product Sales Performance: Identify total revenue, sales volume, and performance trends across various product categories and sub-categories.
* Analyze Product Profitability and Its Variations: Assess product profit, profit margins, and identify profitability variations based on product categories, sub-categories, payment methods, and comparisons between regions/states.
* Uncover Consumer Behavior Patterns Related to Payments: Understand payment method preferences and analyze their implications for operational costs or sales strategies. 
* Provide Actionable Business Insights: Deliver data-driven insights to stakeholders for sales optimization, profitability enhancement, logistics management, and regional decision-making.


## **Data Source**

* **Data Source:** This analysis is based on a comprehensive e-commerce sales dataset, titled ‘Online Sales Data’, available on Kaggle.
* **Dataset Overview:** This project utilizes an e-commerce sales dataset with the following characteristics:
* **Data Structure:** Consists of two relational tables:
details (7 columns): Records order details such as Order ID, Amount, Profit, Quantity, Category, Sub-Category, and PaymentMode.
orders (5 columns): Contains general order information such as Order ID, Order Date, CustomerName, State, and City (with 500 unique Order IDs).
* **Data Time Range:** Data is available for 2018.


## **Analysis Approach**

* **Data Cleaning:** To ensure the integrity and accuracy of the analysis, a thorough data cleaning process was conducted. This stage involved comprehensive validation for potential null or empty values, utilizing methods such as Countblank checks. Furthermore, in-depth outlier analysis was applied to the quantity, amount, and profit columns through quartile calculations (Q1, Q3, IQR, Upper Quartile, Lower Quartile, Minimum, and Maximum values). A well-considered decision was made not to remove the identified outliers, as these values contain important business information that enriches the depth of our insights.



## **Unlocking Insights from E-commerce Sales**

### *Top 5 Best Sub-Category Product by Amount* 



![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Top%205%20Best%20Sub-Category%20Product.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Top%205%20Best%20Sub-Category%20Product).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Top%205%20Best%20Sub-Category%20Product%20(Dashboard).png?raw=true)


### **Insight**


* **Niche Market Dominance:** The top-selling product, printers, is not a common consumer good. This indicates that the e-commerce platform has a strong capability in serving specific, well-defined market segments (such as students and SMEs).
* **Effectiveness of Consumer Segmentation:** The success of printer sales is driven by a highly specific consumer base. This highlights that a deep understanding of the needs, preferences, and price sensitivity of these segments is key to driving sales.
* **Importance of Product Customization:** The data shows different preferences in features and price points among different consumer segments (e.g., students are more price-sensitive, while SMEs may prioritize multifunctional features).



### *Category Product by Amount* 


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Category%20Product.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Category%20Product).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Category%20Product%20(Dashboard).png?raw=true)


### **Insight**

* **Dominance of the Electronics Market:** Electronics is the best-selling product category with total sales of $166,267, significantly outperforming other categories. This shows a strong consumer preference for technology products on this e-commerce platform.
* **Untapped Potential of Other Categories:** Although clothing and furniture sales are ranked second and third, there is a significant sales gap compared to electronics. This indicates room to improve the performance of both categories to optimize their sales contribution.
* **Cross-Selling Opportunities:**  Since electronics is the main category, there is a great opportunity to increase sales of clothing and furniture products through a cross-selling or bundling strategy.


### *Amount and Profit by Category* 


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Amount%20and%20Profit.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Amount%20and%20Profit).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Amount%20and%20Profit%20(Dashboard).png?raw=true)


### **Insight**

* **Gap Between Sales and Profitability:** Although electronics products have the highest sales, their profitability (7.92%) is the lowest among the three main categories. This indicates a significant gap between sales volume and profit efficiency.
* **Significant Room for Improvement:** All product categories have profit margins below the healthy industry average (10-20%). The figures of 7.92%, 9.23%, and 8.24% indicate a substantial opportunity to optimize profitability and efficiency across the entire product line.
* **Importance of Cost Analysis:** The low margins, especially in the highest-selling category, suggest potential issues with cost structure (e.g., high COGS, operational, or logistics costs) or an overly competitive pricing strategy.



### *Payment Method*


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Payment%20Method.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Payment%20Method).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Payment%20Method%20(Dashboard).png?raw=true)


### **Insight**

* **Consumer Preference for Security:** The dominance of the COD payment method (45.1%) shows that a large portion of consumers prioritize a sense of security and confidence when shopping online, as they can inspect the goods before paying.
* **Operational and Cost Challenges:** The high usage of COD creates significant operational challenges, particularly related to high logistics costs and the risk of returns that are less efficient than digital payment methods.
* **Opportunity for Digital Payment Migration:**  Although COD dominates, the total percentage of digital payments (UPI, Debit Card, Credit Card) is also very large (46.7%). This indicates a ready consumer base that can be incentivized to switch.



### *Top 10 Best Profit by Category & State*


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Top%2010%20Best%20Profit%20by%20Category.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Top%2010%20Best%20Profit%20by%20Category).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Top%2010%20Best%20Profit%20by%20Category%20(Dashboard).png?raw=true)



### **Insight**

* **Localized Profitability Crisis:** The electronics product category in Uttar Pradesh is suffering a significant loss with a negative profit margin of -19%. This is a critical condition as the company is losing money on every sale in that region, driven by a decrease in the Average Selling Price (ASP).
* **Isolated Geographical Issue:** This profitability problem is not systemic to the entire electronics category but is isolated to the Uttar Pradesh region. This is evident when compared to other electronics sales in the table which have very high, positive profit margins in other states.
* **Ineffective Discounting:** The decline in ASP suggests that the discounting or pricing strategy in this region is ineffective and is eroding profits to below the cost of the product.



### *Amount, Average Cost, & Profit by Sub-Category*


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Main%20Query%20(2).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Amount%2C%20Average%20Cost%2C%20%26%20Profit.png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Results%20(Amount%2C%20Average%20Cost%2C%20%26%20Profit).png?raw=true)


![alt text](https://github.com/restianimutoharoh/Business-Intelligence-in-E-commerce-Sales-Product-Performance-Analysis-in-India-2018-/blob/master/Img/Amount%2C%20Average%20Cost%2C%20%26%20Profit%20(Dashboard).png?raw=true)



### **Insight**


* **Regional Profitability Disparity:** There is a stark difference in profit for the same product, handkerchief, between two regions. A negative profit of $-29 in Madhya Pradesh indicates the company is losing money on sales there, while the same product in Maharashtra is significantly profitable, generating $646.
* **Cost or Pricing Issues in Madhya Pradesh:** The negative profit in Madhya Pradesh suggests that the selling price of the product may not be sufficient to cover costs (COGS, logistics, etc.). This points to a deeper issue with pricing strategy or an elevated cost structure in that specific region.
* **Systemic Issue at the Regional Level:** The profitability problem in Madhya Pradesh appears to be more than a single-product issue. The table also shows losses in other categories like furnishings and chairs in the same state.
