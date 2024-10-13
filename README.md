**India EV Market Data Project**
_Overview_
In this project, I analyzed data about Electric Vehicles (EV) in India. I looked at where EV makers are located, how many public charging stations (PCS) are working, how many EVs were registered, and how many EVs were sold by different companies over time. I also made graphs and charts using Python and Power BI to understand the data better.

_Datasets Used_
Here are the files I used for my analysis:

EV Maker by Place.csv
OperationalPC.csv
Vehicle Class - All.csv
ev_cat_01-24.csv
ev_sales_by_makers_and_cat_15--24.csv

_Steps I Followed_
1. Loading and Checking the Data
I imported all the datasets using Python (pandas) and checked for any missing or strange data.

2. EV Makers by State
I counted how many EV makers are in each state and made a bar graph to show it. I also saved this information in a CSV file.

3. Top 7 States with the Most Charging Stations (PCS)
I found the seven states with the highest number of public charging stations and saved the results.

4. Vehicle Registration Data
I found the top seven vehicle classes that had the most EV registrations and saved that data too.

5. Cleaning and Formatting the Data
For the file ev_cat_01-24.csv, I cleaned the data, fixed the date format, and added columns for Year and Month to make it easier to work with.

6. Sales by Category and Maker
I calculated the total sales by category and by EV maker. I also found the top seven EV makers in terms of sales and saved the results.

_Power BI Dashboards_
I used Power BI to create interactive dashboards, where I visualized the data in a way that's easy to understand. The dashboards include:
*Sales by state, maker, and category.
*Important stats (KPIs) like total sales and which EV makers are leading in sales.
*Yearly Data Insights and Charts
*I analyzed yearly sales data and created several charts to understand trends:
*Sales of Four Wheeler Vehicles over the Years: Showed how sales of four-wheelers have increased or decreased each year.
*Sales of Heavy Passenger Vehicles over the Years: Displayed the sales pattern of heavy passenger vehicles like buses and larger EVs.
*Total Sales of the Year: Showed the total number of EVs sold in each year.
*Maximum Sales of the Year: Highlighted the year with the highest sales of EVs overall.
*While these charts focus on specific categories like four-wheelers and heavy passenger vehicles, they also help us see changes over time. If we want to explore other categories, we can easily switch the category filter and analyze that data as well.

_Key Insights_
**EV Makers: Certain states have more EV makers than others.
**Charging Stations: Some states have many more public charging stations than others.
**EV Sales Trends: Sales are growing in certain categories, showing changes in what people prefer to buy.
**Top EV Makers: A few companies are leading in terms of sales.
**Four-Wheeler and Heavy Passenger Vehicle Sales: These categories reveal the patterns in EV sales over the years. We can also explore other vehicle categories easily using the same data.

_Files I Created_
*EV_Makers_Per_State.csv
*Top_seven_states_having_PCS.csv
*Top_7_Registration.csv
*Yearly_Data.csv
*Total_Sales_By_Category.csv
*Total_Sales_By_Maker.csv

_Conclusion_
This project helped me understand the EV market in India by analyzing where the makers are located, how charging infrastructure is distributed, and how sales have changed over time. The Power BI dashboards and yearly sales insights make it easier to understand these trends visually, with flexibility to explore other categories as needed.
