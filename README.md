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
columnns and all the Percentage Columns to make a line chart. This line chart shows the percentage of campaigns which failed, succeeded and got canceled 
based on their goal amounts. 

### Challenges and Difficulties Encountered

One difficulty which could have been encountered was that someone could have accidentally put the wrong columns in the countifs() function as it got 
very long and there were many columns in the main Kickstarter sheet.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first and foremost conclusion which can be drawn is that most campaigns that succeeded were in the month of May. So it would be a great idea
for Louise to start her fundraising campaign in May.

Second conclusion which can be clearly drawn is that most failed campaigns started in October. This tells us that October is not a really good time to 
start the campaign. 

- What can you conclude about the Outcomes based on Goals?

From the graph, we can conclude that it is a bad idea to keep a goal of higher than $50,000 as most of the campaigns in that range failed. Secondly, projects which had a goal of less than $1000 mostly succeeded. This tells us that if Louise decreses her fundraising goal, she will have a much better chance of reaching the target. 

We can also see from the graph and table that very few people kept a goal of greater than $25,000.

- What are some limitations of this dataset?

I think there should have been more data for projects which had a goal greater than $25,000. Due to this, we can not see a proper trend for goal amounts higher than $25,000. A line graph does not properly give us the whole image for the dataset in "Outcomes based on Goals" sheet. 

Secondly, in the 'Theatres Outcomes by Launch Date' sheet, we do not have a subcategory field. It would be helpful to filter the data according to sub categories so that we could see Launch dates for only plays and not the other two sub categories of Theatre category. 

- What are some other possible tables and/or graphs that we could create?

For the "Outcomes based on Goals" sheet, it would be a good idea to create a Box and Whisker plot. This would give the different statistical values such as Mean, Mode and Median and would help Louise make an informed decision. 

In the 'Theatres Outcomes by Launch Date' sheet, we could add a subcategory filter so that we can view data for only the plays. 

