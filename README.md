# Hotel Performance Dashboard (Power BI)

An end-to-end Power BI project analysing the performance of a hotel chain, built as part of my data science course.

## Business problem
The hotel chain is losing market share and revenue to competitors. The goal of this dashboard is to show how revenue, occupancy, bookings and cancellations vary across cities, hotels, room classes and booking platforms, so management can see where to improve.

## What I did
1. Loaded 5 CSV tables (dates, hotels, rooms, bookings, aggregated bookings)
2. Cleaned and transformed the data in Power Query
3. Built the data model with 6 relationships
4. Wrote 24 DAX measures, including revenue, ADR, RevPAR, occupancy, cancellation rate, realisation and week-over-week changes
5. Designed a 3-page dashboard

## Dashboard pages

### 1. Home: key KPIs
![Home page](page1_home.png)

### 2. Revenue & Occupancy
![Revenue and Occupancy page](page2_revenue_occupancy.png)

### 3. Bookings & Cancellations
![Bookings and Cancellations page](page3_bookings_cancellations.png)

## Key insights
- Occupancy across the chain is around 58%, so more than 4 in 10 sellable room nights go unused.
- About a quarter of bookings are cancelled, which is a significant source of lost revenue.

## Files
- [Power BI file (.pbix)](Hotel_Analysis.pbix)
- [PDF export of the dashboard](Hotel_Dashboard.pdf)

## Tools
Power BI Desktop, Power Query, DAX

Data and project idea from the Codebasics end-to-end data analyst project.
