# assignment1_kickstarter
## Overview
After viewing Play **FEVER** come close to its fundraising goal in short duration of time, The Customer Louis wants to compare the performance of other compaigns in comparison to their launch dates and funding goals. The purpose of this project is to provide an analysis of Campaign Outcomes vs launch dates and funding goals . 
## Analysis and Challenges
The initial segment of the Project involved Creating some changes in the Master sheet of the Kickstarter  and extracting the dates from the "Date created conversion" column and using the **YEAR()** to extract the year of launch for each project. 
The analysis was Basically broken down into two parts namely:
* Campaign Outcomes vs Launch dates
* Campaign outcomes vs Funding goals 

The first work was done for Campaign Outcomes vs Launch dates. From the Kickstarted sheet, a new sheet with name "Theater Outcomes by Launch_date" was created(for the reason that "Theatre was the most popular from other parent category" and herein the Pivot tables were created ,as per the filters required ,and from this table the chart for Campaign vs launch dates was generated. 
**No challenges were encountered for the first segment however potential challenges for any other analyst would be to Make sure that while using the pivot table the mulitple itens in teh rows filed for "date launched conversion" column are excluded. **

The second segment was to work on the Campaign outcomes vs Funding goals. The Major challenge over here was to create a simple formula usign **countifs()** to create a ranges for funding goals so that they can be aggregated in a more unsderastandable manner to get the grasp ont eh number of succesful, Failed and cancelled projects based on their reange of funding.

