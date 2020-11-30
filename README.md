# An Analysis of Kickstarter Campaigns

## Overview of Project
I analyzed outcomes of Kickstarter campaigns for theater projects based on launch dates and goals.

### Purpose
The purpose of this analysis is to identify trends in fundraising for Kickstarter theater projects. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I performed my analysis by pulling data on theater projects that were successful in meeting fundraising goals, failed to meet goals, or were canceled, and I looked for trends over time based on project launch date. I displayed my findings by month in a line chart for quick visualization.
[Theater Outcomes by Launch Date Line Chart](https://github.com/LaurenSonis/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
I performed my analysis by pulling data on theater projects that were successful in meeting fundraising goals, failed to meet goals, or were canceled, and I looked for trends based on what dollar-amount goals each project had set. I displayed my findings by $5,000 increments in a line chart for quick visualization.
[Outcomes by Goal Line Chart](https://github.com/LaurenSonis/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
My first challenge was to display launch dates by time of year using monthly trends instead of year to year. I converted the time stamps given in Unix code for the launch dates to short-form dates and placed the converted numbers under the Rows field when building a pivot table. This populated two additional categories for field options: years and quarters. I then placed years under the Filter field in case a user wanted to evaluate the same data year to year. 

My second challenge was to properly sort the data for the Outcomes by Goal line chart. Basic sorting options made it impossible to accurately show trends in ascending order for the pivot table directly as some of the goal benchmarks began with letters and others numbers. I discovered that by custom sorting the data on the spreadsheet titled Outcomes Based on Goals first, I could then sort properly when making the pivot table and line chart.

## Results
- What are two conclusions that you can draw about the Outcomes Based on Launch Date?
Two conclusions that I can draw about the Outcomes Based on Launch Date are that the highest number of successful campaigns had a launch date in the summer months of May, June, and July. I can also conclude that the highest number of failed campaigns were launched in the fall months of September, October, and November.

- What can you conclude about the Outcomes Based on Goals?
I can conclude about the Outcomes Based on Goals that the lower the fundraising goal, the more likely the campaign was to succeed. For theater projects with goals under $1,000, 76 percent succeeded and for those under between $1,000 and $4,999, 73 percent succeeded, whereas the ask for $5,000 to $9,999 had a success rate drop to only 55 percent.

- What are some limitations of this dataset?
Some limitations of this dataset include 

- What are some other possible tables and/or graphs that we could create? 

The purpose of this analysis is to 
Performing analysis on kickstarter projects to identify trends
Chart and Graph
Recommendations based on findings
Descriptive commit message
