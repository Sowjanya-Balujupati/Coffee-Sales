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

* The data which we have collected will be used in creating the Pivot tables and charts.
* 
