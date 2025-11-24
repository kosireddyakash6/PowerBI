# POWERBI-PROJECTS
End-to-end Power BI dashboards with data modeling, DAX measures, and business insights for real-world decision making.
Superstore Sales Analytics Dashboard – Power BI Project
1. Project Name
Superstore Sales Analytics Dashboard

2. Project Purpose / Objective

        The purpose of this project is to analyze sales performance, customer segments, product categories, profit trends, and regional performance using Power BI dashboard.

        This dashboard helps businesses:

         Identify top-selling categories and customer segments.

         Track monthly/ yearly sales performance.

         Understand profit contribution.

         Monitor KPIs like total sales,profit,orders,and monthly patterns.

         Analyze order trends and product performance.

         Make data-driven decisions to improve revenue.

   3.Dataset Details

         Source: Superstore Sales Dataset (Excel/CSV)

         Rows: 9994

         Columns: 20

         Tables Used:

         Orders table(Main Fact Table)

         Category/Sub-Category fields.

         Region,Segment, and Customer fields.

         Date fields for trend analysis.

 4. Key KPIs 

       Total Quantity: 38K

       Total Sales: $2.30M

       Total Profit: $286.40K

       Total Orders: 9,994

       Average Sales: $221.86

5. Charts / Visuals

      Sales by Category (Bar Chart)

      Sales by Month & Year (Line Chart)

      Sales by Consumer (Donut Chart)

      Sales by Corporate (Donut Chart)

      Sales by Home Office (Donut Chart)

      Category by Year Table Summary

      Slicers: Segment, Region, Month, Year.

     These visuals help identify patterns across time, category, and customer segments.

6. DAX Measures

      Total Sales = SUM(Orders[Sales])

      Total Profit = SUM(Orders[Profit])

      Total Quantity = SUM(Orders[Quantity])

      Total Orders = DISTINCTCOUNT(Orders[Order ID])

      Average Sales = AVERAGE(Orders[Sales])

      YoY Sales = CALCULATE([Total Sales], DATEADD('Date'[Date], -1, YEAR))

      Profit Margin = DIVIDE([Total Profit], [Total Sales])
7. Insights

      1. Technology category contributes the highest sales, followed by Furniture and Office Supplies.


      2. Consumer segment shows the highest purchase volume, among all customer segments.


      3. Sales show seasonal trends, high during October–December and low during Feb–March.


      4. Profits remain positive across all years, indicating consistent growth.


      5. Corporate and Home Office segments show lower sales compared to Consumer, suggesting targeted marketing potential.


      6. Some categories show profit dips, indicating discounting or cost issues.


      7. Year-over-year growth trend is visible, with 2019–2020 having stronger spikes.


      8. Large order count (9,994) with stable average sales value indicates strong customer demand.


8. Tools Used

      Power BI Desktop

      Power Query

      DAX

      Excel (Dataset)

     Data Modeling (Star Schema)

9. Author

Akash | Data Analyst
