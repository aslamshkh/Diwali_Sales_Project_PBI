# Diwali Sales Dashboard

### The Table Of Contents

- [Project Overview](#project-overview)
- [Data Source And Preparation](#data-source-and-preparation)
- [Dashboard Building](#dashboard-building)
- [Dashboard Visualiazation](#dashboard-visualiazation)
- [Findings](#findings)


### Project Overview

The project aims to show step by step process on Diwali Sales Dataset to uncover insights and patterns in consumer behavior through visualisation. By analyzing sales data from various catagories, the project seeks to identify trends that can inform future sales strategies and improve customer engagement.


### Data Source And Preparation

1. The data file was uploaded directly to Query Editor to Cleanin the data (if needed) before creating the dashboard.
2. The unwanted columns "Status" and "Unwanted1" were removed from the data set by using "Remove Column" tab on the ribbon.
3. There were 12 null values in the "Amount" column and there was no way to populate the value. Hence, removed them by using "Remove Row" tab on the ribbon.
4. It had 11251 rows and 15 columns initially, which came down to 11239 rows and 13 columns after cleaning the data.
   
### Dashboard Building

**Dashboard Heading:** 
- It was created by using "Text Box" option from the ribbon. 
- The font formatting, box colouring were done through "Format Text Box" general tab option.

**Clustered Column Chart:**
- The chart was used from "Visualisation" tab showing the top performing states based on sale amount.
- Details were placed at X & Y axis on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.
- Top 6 states were filtered through "Filters On The Visual" on the "Filters" tab.

**Stacked Bar Chart:**
- The chart was used from "Visualisation" tab showing the top performing product catagories based on sale amount.
- Details were placed at X & Y axis on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.
- Top 6 product catagories were filtered through "Filters On The Visual" on the "Filters" tab.

**Card:**
- The cards were used from "Visualisation" tab showing the over sales amount, total order sold, and average over all amount.
- Details were placed at "Feilds" on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.
- For average amount, new column was created with the help of DAX formula on the "Table View".
```
Average Value = [Amount]/[Orders]
```

**Donut Chart:**
- The chart was used from "Visualisation" tab showing the top performing zones based on sale amount.
- Details were placed at X & Y axis on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.

**Pie Chart:**
- The chart was used from "Visualisation" tab showing all the sales based on gnders.
- Details were placed at X & Y axis on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.

**Slicer:**
- The slicer was used from "Visualisation" tab showing the dashboard details statewise.
- Details were placed at X & Y axis on the same tab.
- All the formatting was done from the same tab through "Format Your Visual" section.

### Dashboard Visualiazation 
<img src="https://github.com/user-attachments/assets/9aeaa348-8790-45d8-a4b1-437f581be848" width="100%" height="600" alt="Diwali Sale Dashboard">


### Findings

**1. What was the over all sale revenue?**
- 106M

**2. What was the over all product sold?**
- 28K

**3. What was the average value?**
- 56M

**4. Which were the top performing states?**
- UP(19.3M), Maharshtra(14.4M), and Karnataka(13.5M)

**5. Which were the top performing product catagories?**
- Food(34M), Clothing & Apparel(16.M), and Electronics & Gadgets(16M)

**6. What was the overall sales revenue based on genders?**
- Female(74.17M) topping with 70% of over all revenue.
- Male(31.79M) which is 30% of over all revenue.

**7. What was the zonal performance?**
- Central zone leading with the revanue of 41.51M which is 39.17% of over all revenue.
- Southern zone following with 26.49M which is 25% of over all revenue.
- Western zone being 3rd with 18.33M which is 17.29% of over all revenue.

**8. Which were the top sectors impacting the revenue?**
- IT sector topping with 15M.
- Healthcare following with 13M.
- Aviation being 3rd with 13M.

**9. What was the highest and lowest performance based on age groups?**
- The highest revenue was 42M by the age group 26-35.
- The lowest performanc was 3M for the age group 0-17 (Childeren).

> [!NOTE]
> There were deletion of 12 rows due to 12 null values in the "Amount" column.
> There was no option to populate the vlues. Hence, a small variation could be expected in the over all evaluation.


