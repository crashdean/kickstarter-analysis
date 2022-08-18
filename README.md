# kickstarter-analysis
Analysis of Kickstarter for new theater play.
# Kickstarting with Excel

## Overview of Project
    
    
    The Kickstarter analysis project was designed to help a up and coming play wright 
Louise determine if her play "Fever" will be successful in raising funds.   The overall 
budget for the play was set at $10,000.   The data used for the analysis will provide a 
better idea if the play "Fever" has the same or greater success rate than previous fund 
raisers.   Through the use of Excel, we can manipulate the data of the previous fund 
raisers and chart the outcome data to success and also the outcome percent to projected 
amount of funds raised.   We can then see when is the best time to start a fund raiser 
and the success of the projected budget.
### Purpose

## Analysis and Challenges

     The analysis for this assignment were created using existing data from kickstarter fund raisers existing 
in a Excel spreadsheet.   We used the following categories for our analysis.

* Goals
* Outcomes
* Launched_At
* Category and Subcategory

For the first analysis, the outcome and launch date to create a PivotTable.   In this PivotTable,  the columns 
field were populated with the outcome column.   The rows field with populated using the date created 
column; which was converted from Excel date to standard date first.   Outcomes was selected for value, and 
 the table fitlered using parent category and years after ungrouping it form launch date.   The PivotTable was then 
filtered for the theater subcategory only and all years were used for the launch date.   A PivotChart was then 
created using the finished PivotTable.  A line chart was choosen to represent the data the clearest. Theater Outcomes 
was used on the Y axis and Month Launches was used on the A axis.   The PivotChart showed which months had a greater 
success for fund raising.


For the second analysis,  a new Excel sheet was created.   In the first column, pledge amount ranges were created.  
More columns were added to reflect the  Successful , Failed, and Canceled projects along with the sum of all project categories
and percentages of each category.   We used the COUNTIFS() formula to calculate totals for the goal ranges.   Once the 
goal ranges were complete, the Total Projects column was  populated using the SUM() formula.  A LineChart was then created to show  
Outcomes vs Based on Goals.   A line chart was again the best choise for displaying the data.  The goal outcome percent on the Y axis 
and the Projected Goals Amount on the X axis.   The chart showed the percentage diffences for the three categories.

     


### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results
