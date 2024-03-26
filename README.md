# Kickstarting with Excel 

## **Overview of Project**

The overall objective of this project is to become more comftorable with the Microsoft excel tools. We gathered data from Louise's Kickstarters, attatching visual aid and a comprehsnive breakdown of potential trends and a plan of action to make sure she is able to reach her goals in future campaigns.

### **Purpose** 

The purpose for the data collected is to analyze all of the "Play" Kickstarter outcomes based on launch date and fundraising goals. 
By the end we will have a comprehensive understanding of the data so we can make sure Louise knows what trends 
led to Successful outcomes vs Failed outcomes so she is better equiped to have a succesful campaign for her future Plays. 

## **Analysis and Challenges** 

There weren't many challenges I faced while gathering all of the data, but there were a few while creating the tables. 
The first challenge was while creating the "Theater Outcome by Lanch Date" piviot table, when initiialy placing the "Date created conversion" field in the rows column, 
I had noticed the Years were displaying in the X axis of the chart. When I looked over to the Rows column I seen there were more fields than than just the Date Created Conversion. 
I had to remove the "Years" & "Quarters" by drag and dropping them into an empty cell.
This fixed the issue and showed what cmpaigns for "Theater" were Successful, Failed and Canceled for each month from 2009 - 2017.

The second issue was formatting the Y axis of the "Outcome Based on Goal" chart to show the percentage of the successful, failed and canceled projects. 
It was a failrly easy fix but the chart had orginally showen the numbers in decimals instead of percentage.
When orginally placing the Percentage of Successful, Failed and canceled campaigns into the "Values" colomn, the numbers were defualted to show "General" numbers with 2 decimals places. 
By clicking the "i" icon next to the "sum of Percentages" in the value box, I was able to access the "Number..." box. 
After clicking this box, all I  had to di was scroll down to the "Percentage" and change the decimal places to 0 and this fixed the problem. This issue took about 5 minutes to figure out. 
This excercise was pretty straight forward so there were little to no challenges when curating the data. 

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://github.com/MarquiseProjects/kickstarter-analysis-/assets/158505969/3b20fe13-86aa-476f-98c0-3e7e341aba5b) 

Now there are 2 conlcusions that can be drawn just by looking over the chart.

First Conclusion: If you notice, there is a steady rise of successful campaigns starting in April, with a significant spike in May and June with a subtle decline until August.
Once September hits, the success rates declines all the way until Januarary, closing the gap between Success and Fail rates. 
This clearly suggest that these "Theater" events are more successful in the warmer months. 

Second Conclusion: The Failed and Canceled Rate stay pretty consistent year round. The Success rate as stated above, does change in the warmer months, 
this leaves me to conclude that there is an outside factor that causes this change and not much to do with the events themselves. 
The reason for this is unclear and not captured by the data, but this can be speculated that its due to school being out, 
or maybe thes events are out side, or people find themeselves with more disposable income in the summer months.
The one thing I can be sure of is this is no coincedence since there is 8 years of data being shown in the carts above. 

### Analysis of Outcomes Based on Goals 

![Outcomes_vs_Goals](https://github.com/MarquiseProjects/kickstarter-analysis-/assets/158505969/c4624b51-58d7-4ec6-8391-0adb4f6df5d4)

The conclusion I've come to for this data set is simply put, the lower the goal for the play, the better chance it has to being reached. There is a small spike for goals reached from $35000 - $44999.
There is a total of 9 projects that fall into this Goal amount range. With the information gathered, its unclear why these palys reached their goal and is an issuee with the data collected. 
So to summarize it can be concluded that plays do not recieve much in Pledges magority of the time, except for a few outliers.
The safest approch would to keep the goal at $14,999 or lower to increase your chances at having your goals met. 

### Challenges and Difficulties Encountered 

There is valuable data collected here, but there are a few limitaions to the data set that keep us from seeing the full story here. 
For starters, why is it that in warmer months, more Theater events are seen to be successful in the "Theater Outcomes Based on Launch Date" chart? 
What caused 6 of the 9 Plays to reach their higher set goals highlighted in the "Outcomes Based on Goals" sheet? 

Maybe for the first question, we could list where the event are taken place just to see if weather is a factor at all or if its when school lets out in that area or maybe see if the venues are outside or inside.
For the second, it might be useful to also see when these plays were launched, almost combining the two datasets. 
