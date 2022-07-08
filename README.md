# Assignment1_kickstarter
## Overview
After viewing Play **FEVER** come close to its fundraising goal in short duration of time, The Customer Louis wants to compare the performance of other compaigns in comparison to their launch dates and funding goals. The purpose of this project is to provide an analysis of Campaign Outcomes vs launch dates and funding goals . 
## Analysis and Challenges
The initial segment of the Project involved creating some changes in the Master sheet of the Kickstarter and extracting the dates from the "Date created conversion" column and using the **YEAR()** to extract the year of launch for each project. 
The analysis was Basically broken down into two Segments namely:
* Campaign Outcomes vs Launch dates
* Campaign outcomes vs Funding goals 

### Campaign Outcomes vs Launch dates
The first work was done for Campaign Outcomes vs Launch dates. From the Kickstarted sheet, a new sheet with name "Theater Outcomes by Launch_date" was created(for the reason that "Theatre was the most popular from other parent category" and herein the Pivot tables were created ,as per the filters required ,and from this table the chart for Campaign vs launch dates was generated. 

**No challenges were encountered for the first segment however potential challenges for any other analyst would be to make sure that while using the pivot table  mulitple itens such as quarters and years in the rows filed for "date launched conversion" column are excluded in the Rows field in pivot table.** 

### Campaign outcomes vs Funding goals
The second segment was to work on the Campaign outcomes vs Funding goals. The Major challenge over here was to create a simple formula to import number of projects  with a definite range of funding goals filtered by the required range requirement,subcategory requirement (plays) and the outcome.
This was overcome by using **countifs()** in the following manner, For example for getting the number of succesfful "play" projects in the funding goal range of 1000 to 4999 :
```
=COUNTIFS( Kickstarter!$F$2:$F$4116,"failed",Kickstarter!$D$2:$D$4116,">=15000",Kickstarter!$D$2:$D$4116,"<20000",Kickstarter!$R$2:$R$4116,"plays")
```



