# Store_Data_Analysis
Dyanamic Dashboard and Data Analysis Of Store
Objective:
Vrinda Store wants to create an annual sales report for 2022. So that, Vrinda can understand
their customers and grow more sales in 2023.

Sample Questions:
1. Compare the sales and orders using single chart.
2. Which month got the highest sales and orders?
3. Who purchased more- men or women in 2022?
4. What is different order status in 2022?
5. List top 10 states contributing to the sales?
5. Relation between age and gender based on order number?
6.Which channel is contributing to maximum sales?

Data Cleaning:
1.	Moving through each of the columns and looking for a. Duplicates b. Data type consistencies c. Null values d. Typos.
2.	Correction was made in Age and Qty column as there I found data inconsistent.
3.	Rest all in order.

Data Processing:
Calculations to be incorporated, basis the questions.

1.	I had a business question “Relation between age and gender based on number?” for that I have created a column named “Age Group” and used formula “=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))” to create there categories 1. Senior 2. Adult and 3. Teenager.
2.	Basis the question” Which month got the highest sales and orders?” I planned to create a separate column on month using formula “=TEXT(G2,"mmmm")”
Data Analysis

1.	Now I created Pivot Table and started analysing basis the business questions.
2.	First was to create the values Sum for Amount and Count for Orders and show it basis the Month, I found an issue as Order ID was in thousands and Amount in millions so I used the combo chart with secondary axis.
3.	Now for the Y- axis the values are in million and not friendly to read so I double clicked on Y-axis values and used format axis toolbar under “Number” used category as “General” and under that used Format code as “0,,”M””.
4.	Created Pie Chart for Men Vs Women on contribution over sales.
5.	Created a Pie Chart again for order status.
6.	Created a Clustered Bar graph for Sales: Top 5 States.
7.	Created a Clustered Column graph for Orders: and compared it between Age and Gender.
8.	Created lastly the Pie chart for Orders: Channels.
Addressing the Business Questions and Answering It using AI:
1.	Compare the sales and orders using single chart.
Ans:  Peak in March: Both sales and orders peak in March, suggesting a significant sales event or promotion during that month.
Decline After March: After March, both sales and orders show a general decline, with some fluctuations.
Sales Dip in June: There is a noticeable dip in sales during June, while the number of orders remains relatively stable. This could indicate a period of lower-value orders or discounts.
Orders Decline in September: The number of orders sees a sharp decline in September, which is also reflected in a drop in sales.

Potential Insights:

Marketing Effectiveness: The March peak suggests successful marketing or promotional efforts.
Seasonal Trends: The decline after March might indicate seasonal fluctuations in demand.
Pricing/Discount Strategies: The July dip in sales with stable order numbers could be due to pricing or discount strategies.
Operational Issues: The sharp decline in orders in September could point to operational issues or supply chain disruptions.

2.	Which month got the highest sales and orders?
Ans: Evident from the graph, march received the highest number of Order followed by August the second highest.

3.	Who purchased more- men or women in 2022?
Ans: Women have contributed to higher share in the sales. 

4.	What is different order status in 2022?
Ans: For these please refer the dashboard but taking data as whole the store really performed well with returned, cancelled, and refunded percentages quite low across all months.

5.	List top 5 states contributing to the sales?
Ans: For these please refer the dashboard, but considering the data set as whole the list start with Maharashtra at top followed by Karnataka, Uttar Pradesh, Telangana and finally Tamil Nadu.

6.	Relation between age and gender based on order number?
Ans: In these The Adults and under those men contributed the highest.

7.	Which channel is contributing to maximum sales?
Ans: Amazon, the maximum contribution is from that channel.

 
