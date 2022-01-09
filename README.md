# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose

Louise wants to start her own play called 'Fever'. Her play did not meet its target by a short amount. Now she wants to take a look 
at other fundraising campaigns for theatres and see how well they did based on certain factors. The two main factors we will be focusing on are 
"Outcomes based on Goals" and "Outcomes based by Launch date". For this, we will need to work on the "Kickstarter" sheet which is contained in
Kickstarter_Challenge.xlsx workbook. By extracting relevant information and making use of graphs and Pivot tables, we will help Louise in making
an informed decision regarding how she should proceed with the fundraising campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For this part of the project, I first added a Years Column in the "Kickstarter" sheet and populated that column with the Years in which the 
campaign was launched. Then I made a pivot table from the date in this sheet and moved it to a new sheet. I filtered the pivot table based on
"Parent Category" and "Years" as that is the relevant information needed. After filtering the Parent Category column to show only Theatres, I
sorted the campaign outcomes in descending order to show successful outcomes first. Then I created a line chart of this table to notice the trend
of the outcomes throughout the entire year. 

### Analysis of Outcomes Based on Goals


For this part, I created a new sheet for "Outcomes Based on Goals" data. After creating relevant headings for the columns, I used countifs()
function to extract data from the "Kickstarter" sheet. Other functions used to complete the table were Sum() and Round(). Then I selected the Goals 
columnns and all the Percentage Columns to make a line chart. This line chart showed the percentage of campaigns which failed, succeeded and got canceled 
based on their goal amounts. 

### Challenges and Difficulties Encountered

One difficulty which could have been encountered was that someone could have accidentally put the wrong columns in the countif function as it got 
very long and there were many columns in the main Kickstarter sheet.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?


