# Sales-Report-And-Analysis (Q1)
This is a first quatre report for the CEO of a B2B and B2C product sales company. The CEO is interested in knowing how his company perfermoned in the first quater of the year 2020 and the ongoing second quater.

# Data Transformation

There wasn't much cleaning to be done on the dataset. However, since the data was in different tables, it was modelled together by creating a relationship between them. 
General Excel Formulas which were used includes:

     Cost per order =[@[Order qty]]*[@[unit cost]]
     
     Sales per order =[@[unit price]]*[@[Order qty]]

     Profit =[@[Sales per order]]-[@[Cost per orders]]

     Total Cost =SUM(@[Cost per orders])
     
     Total Sales =SUM(@[Sales per orders])

     Gross Profit = Total Sales - Total Cost
     
     Gross Margin (%) = (Gross Profit / Total Sales) * 100
     
     Profit Margin (%) = (Gross Profit / Total Cost) * 100

     MoM Growth (%) = =(B44-B43)/B43% ((current month - previous month)/previous month * 100)

**Questions he is interested in includes:**

1. Which channel(s) generates the most profits and what is the margind across the months?.

2. What percentage of sales does each region generates, which region should we look into expanding into?.

3. What are the best selling products by profits generated?.

4. Which products should we keep stocking based on the numbers of orders, are they also high performing products?.

5. How many stores do we currently have over the states, which states has the most number of stores?.

6. Which sales employee does their job satisfactorily?.

7. What is the growth rate of the company over the months?.

# EDA

1. Which channel(s) generates the most profits and what is the margind across the months?.

![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/6e5fc7bf-a124-426d-8562-f8360ea0e350)

As compared over the months, Online sales channel generated the most profits in January but the least in February while In-store sales which held the third position in january is currently leading in profits. However, at the end of the Q1, both Distributor and Wholesale has an increased profits followed by Online and Distributor respectively. 

2. What percentage of sales does each region generates, which region should we look into expanding into?.

![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/9ab40c91-f147-4d36-bd9a-8a99048bffec)

Across all four regions, the Midwest region has the highest percentage of sales at 30.57% followed by the South region at 23.63%. Although, with exceptions of Midwest, all regions have an evenly distributed sales record ranging from 22.70% to 23.63%.

3. What are the best selling products by profits generated?.

![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/93f93d86-0273-44b7-a169-b461c255fd45)

The product generating the highest gross profit is the Clock generating over $310,000.00, followed by Vases at over $300,000.00. Cookware, Ornaments and phones fall in the same range generating about $290,000.00 while  Candles, Collectibles, Table Lamps and Wallframes generates about $280,000.00, while Rugs which is the top tenth product generates just a little less than $280,000.00

4. Which products should we keep stocking based on the numbers of orders, are they also high performing products?.

![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/de6c22e3-a266-43b3-962a-4b67602327b0)

The most ordered product is Clock, followed by Cookware and Vases with almost 2800 and 2600 orders respectively. While Rug is a high profit grossing product, it however isn't among the top 10 most ordered profit.

5. How many stores do we currently have over the states, which states has the most number of stores?.

![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/df94f9cd-0539-4a00-891c-77ba40235f26)

While over 30.57% profits are generated from the Midwest, there are about 74 stores in California. However, California falls under the West regions, which generates the least profits at 22.70%. 

6. Which sales employee does their job satisfactorily?.
 
![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/b98bc095-3a99-40cf-ad2c-a4b9168d1e0e)

Employee of the quater will be Nicholas Cunningham who has made about$530,000.00 in sales, leading with about $65,500.00 over Douglas Tucker who has generated about $463,000.00 in sales.

7. What is the growth rate of the company over the months?.
![image](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/6b6193aa-c2d6-467b-8ad9-3d3c536051e9)

In the Q1 of the year, there is a positive - negative month-on-month (MoM) growth. January witnessed a significant high revenue,however there was a decline in February and also and increase in March. In the ongoing Q2, April also witnessed a decrease followed by an increase in May.

# Insights and Conclusion

1. Online sales generated the most profits in January but the least in February. In-store sales, which ranked third in January, is currently leading in profits.
By the end of Q1, both the Distributor and Wholesale channels experienced increased profits, with Online and Distributor channels following suit.

2. The Midwest region has the highest sales percentage at 30.57%, followed by the South region at 23.63%.
All regions, except the Midwest, have relatively evenly distributed sales percentages ranging from 22.70% to 23.63%.

3. The Clock product generates the highest gross profit, exceeding $310,000.00, followed closely by Vases at over $300,000.00.
Cookware, Ornaments, and Phones fall within the same profit range, generating about $290,000.00 each.
Candles, Collectibles, Table Lamps, and Wallframes contribute about $280,000.00 each.
Rugs generate slightly less than $280,000.00.

4. Clock is the most ordered product, with over 2,800 orders, making it a best seller.
Rug, despite being a high-profit product, does not rank among the top 10 most ordered products.

5. There is a pattern of positive and negative MoM growth in the first quarter.
January experienced significant high revenue, followed by a decline in February and an increase in March.
In Q2, April saw a decrease followed by an increase in May.

6. Despite having approximately 70 stores in California, it falls under the West region, which generates the least profits at 22.70%.
The Midwest region, with just over 30.57% of profits, outperforms other regions.

7. Nicholas Cunningham is the top-performing employee, generating approximately $530,000.00 in sales.
Cunningham leads by a margin of about $65,500.00 over Douglas Tucker, who generated about $463,000.00 in sales.

# Data Visualization

![Q1 sales report](https://github.com/olajumokeabe/Sales-Report-And-Analysis/assets/125363157/feed3e43-24c9-4ead-9206-38c5047ce13b)

# Recommendations

1. Given the fluctuating performance of sales channels, consider a deeper analysis to understand the reasons behind the variations. Invest more in marketing and strategies for the Online channel to maintain its profitability throughout the year.
Evaluate the strategies that led to the significant growth in Distributor and Wholesale profits in Q1 and explore ways to sustain this growth.

2. Investigate why the Midwest region consistently outperforms others in terms of sales percentage. Identify successful practices and potentially replicate them in other regions.
In the West region, where there are numerous stores in California but lower profits, conduct a region-specific analysis to uncover potential issues affecting profitability and implement corrective measures.

3. Continue to promote and prioritize top-grossing products like Clock and Vases. Consider bundling them with complementary products or launching marketing campaigns to boost their sales further.
For products like Rugs that have high profitability but lower sales, explore strategies to increase their visibility and customer demand.

4. Analyze the product ordering patterns to ensure that high-demand products are well-stocked to meet customer needs. On the flip side, optimize inventory management for low-demand products.
 Use the MoM growth patterns to make informed decisions regarding production and inventory adjustments.

5. Recognize and reward high-performing employees like Nicholas Cunningham. Consider implementing an employee recognition program to motivate the sales team.
Provide ongoing training and support to ensure all employees have the tools and knowledge to excel in their roles.

6. Implement robust sales forecasting models to anticipate future trends and demand variations, allowing for proactive adjustments in marketing, inventory, and staffing.
   
7. Given the positive MoM growth patterns, focus on retaining existing customers. Implement customer loyalty programs and personalized marketing campaigns to encourage repeat purchases.

8. Continuously monitor competitors' strategies and market dynamics to adapt and remain competitive.

9. Tailor marketing strategies based on seasonality and MoM growth trends. Allocate marketing budgets more effectively during peak months to maximize ROI.
