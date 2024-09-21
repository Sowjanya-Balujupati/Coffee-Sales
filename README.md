# Coffee Sales Dashboard Project
In this Coffee Sales Dashboard project, an exploratory data analysis was performed on the Coffee Sales Data available on Youtube video. The main aim of the project is to compare the total coffee sales from 2019 to 2022.


## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#Prerequisites)
- [Cleaning and Processing the data](#Cleaning_and_Processing_the_data)
- [Usage](#Usage)
- [Visualization](#Visualization)

### Introduction

This project helps in visualizing and comparing the Coffee sales split by 4 different coffee types Arabica, Excelsa, Libreca, Robusta and also to compare the total sales by country. In this project, we are comparing the sales in 3 countries - US, Ireland and UK. After cleaning and processing the data using few excel formulas like X LOOKUP, INDEX and MATCH, the profits trends were visualized by country, roast type, size, loyality card and timeline(months).

Additionally, Top 5 customers were also identified.

### Prerequisites

* Knowledge in Microsoft Excel formulas
* Usage of Bar charts, Pivot tables

###  Cleaning and Processing the data

1. Used XLOOKUP formula to get the information like customer name, email and country from customer sheet to orders sheet in Coffee orders data file.
2. Used IF(XLOOKUP) formula to remove any fields with "0". This can be used for any text.
3. Used INDEX and MATCH formula to get the information like Coffee type, roast type, size and unit price from products sheet to orders sheet.
4. Finally, sales is calculated by multiplying the Unit price with Quantity in the orders sheet and you will get all values.
5. We need to check for any duplicates by selecting the entire sheet and click remove duplicates in the data tab.

### Usage

* The data which we have collected will now be used in creating the Pivot tables and charts.
* These charts helps us to analyse and visualize the data.

### Visualization

* Pivot chart with graph is created based on the total sales over time by coffee type and adjust the design based on your interest.
* Created a timeline which calculates the orders based on the months and adjusted the design.
* Created 3 splicers for Roast type, Size and Loyality card respectively.
* Other 2 pivot charts are used for Total sales by country and Top 5 customers.
* Arrange the charts, timeline and splicers in the orderly manner and create a dashboard
* ```Last and main step is to click report connections for each chart/table/graph in the dashboard so that the data can be visualized by filtering the fields```.
  
** Final dashboard look below **
  ![Capture](https://github.com/user-attachments/assets/612ca02c-3a64-4ec9-aada-92f6d1be352f)
 
