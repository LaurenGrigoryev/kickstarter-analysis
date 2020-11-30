# An Analysis of Kickstarter Campaigns

## Overview of Project
I analyzed outcomes of Kickstarter campaigns for theater projects based on launch dates and goals. This information is intended to help a Kickstarter user reflect on her past theater campaign and how she fared by comparison to other theater campaigns in relation to their launch dates and goals.

### Purpose
The purpose of this analysis was to identify trends in fundraising for Kickstarter theater projects. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I performed my analysis by pulling data on theater projects that were successful in meeting fundraising goals, failed to meet goals, or were canceled, and I looked for trends over time based on project launch date. I displayed my findings by month in a line chart for quick visualization.
[Theater Outcomes by Launch Date Line Chart](https://github.com/LaurenSonis/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
I performed my analysis by pulling data on theater projects that were successful in meeting fundraising goals, failed to meet goals, or were canceled, and I looked for trends based on what dollar-amount goals each project had set. I displayed my findings by $5,000 increments in a line chart for quick visualization.
[Outcomes by Goal Line Chart](https://github.com/LaurenSonis/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
My first challenge was to display launch dates by time of year using monthly trends instead of year to year. I converted the time stamps given in Unix code for the launch dates to short-form dates and placed the converted numbers under the Rows field when building a pivot table. This populated two additional categories for field options: years and quarters. I then placed years under the Filter field in case a user wanted to evaluate the same data year to year. 

My second challenge was to properly sort the data for the Outcomes by Goal line chart. Basic sorting options made it impossible to accurately show trends in ascending order for the pivot table as some of the goal benchmarks began with letters and others numbers. I discovered that by custom sorting the data on the spreadsheet titled Outcomes Based on Goals first, I could then sort properly when making the pivot table and line chart.

## Results
- What are two conclusions that you can draw about the Outcomes Based on Launch Date?
Two conclusions that I can draw about the Outcomes Based on Launch Date are that the highest number of successful campaigns had a launch date in the months of May and June. I can also conclude that almost half of theater projects failed when launched in December. Based on this information, I would recommend launching a project in May or June and avoid launching a project in December.

- What can you conclude about the Outcomes Based on Goals?
I can conclude from analyzing Outcomes Based on Goals that the lower the fundraising goal, the more likely the campaign was to succeed. For theater projects with goals under $1,000, 76 percent succeeded and for those between $1,000 and $4,999, 73 percent succeeded, whereas the ask for $5,000 to $9,999 saw a success rate drop. Only 55 percent were successful. Based on this information, I would recommend setting a goal of $4,999 or less.

- What are some limitations of this dataset?
A limitation of this dataset is the number of projects to analyze past a certain fundriaisng goal changed significantly. When analyzing outcomes by goals, the grand majority of projects launched had a goal of $14,999 or less, so the measurements of success for projects with a fundraising goal of $15,000 or higher technically gave us a percentage, but those percentages were based on significantly less data than the percentages of cheaper projects. The conclusions drawn for cheaper projects might be more accurate than the conclusions drawn for more expensive projects. Another limitation with the data set included an outlier in the collection of canceled projects with a launch date of January.  

- What are some other possible tables and/or graphs that we could create? 
It would be helpful to visualize outliers, the median, and the mean of outcomes based on goals by creating a box and whisker plot. It would also be helpful to create a table to measure the central tendencies of outcomes based on goals and outcomes based on launch date.
