# Pizza Sales-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/34fabcfb-2387-4603-a57d-8e1f73870e97/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps the Pizza company understand their sales better. It helps the company to know the trends and their best and worst selling product. Through category , they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the total sale by size and category , thus since by using this dashboard we can easy come with the data which can retain our sale as well as improve our sale of those categories which are underperforming according to likes of the customers.

Classic category is on top with (almost 26.91 %) of sale following it we have Supreme category (at 25.46) and then chicken category(at 23.96)

Orders are maximum in the month of July & Jan with thrs fri sat with maximum number of sales. 


### Key metrics in the dashborad include:

1. Total Revenue: sum(pizza_sales[total_price]) 
2. Avg Order Value = [Total Revenue]/[Total Orders]
3. Total Pizzas Sold = Sum(pizza_sales[quantity])
4. Total Orders = distinctcount(pizza_sales[order_id])
5. Avg Pizzas Per Order = [Total Pizzas Sold]/[Total Orders]

6. Order DAY = upper(left(pizza_sales[Day Name],3))
7. Order Month = upper(left(pizza_sales[Month Name],3))
