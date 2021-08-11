# **Kickstarting with Excel**

## **Overview of Project**

### **Purpose**
>The goal of this project is to continue our analysis of [Kickstarter data](https://github.com/annaS000/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx) for the playwright, Louise. First, we helped her start a crowdfunding campaign for her play **_Fever_**, with an estimated budget to be **over $10,000**. That analysis included giving Louise accurate information/recommendations backed by research to set up her campaign for success. This was done by gathering data from other campaigns on the crowdfunding website Kickstarter and conducting an analysis on different variables using tables and charts to find trends that can affect the outcome. These results were used as guidelines for what makes an effective and profitable campaign.
>>Now that Louise has raised close to her funding goal in a short time frame, she has come to us again to find out how other campaigns turned out in relation to their **launch dates** and **funding goals**. This a written analysis of those variables along with visualizations.

---

## **Analysis and Challenges**
This section will walk through the process I took to analyze this data for Louise and explain any challenges I had during the project.

---
### **Analysis of Outcomes Based on Launch Date**
To begin the analysis of campaign launch dates, I created a line graph that displays the number of successful, failed, and canceled campaigns throughout the months of the year. This was done by creating a PivotTable with the rows populated with **Date Created Conversion**, columns labeled **outcomes**, and showing the values for the **Count of Outcomes**. I added filters for **Parent Category** and **Years** and then set the Parent Category to **Theater** so I can see the results for those specific data points. After looking the graphs over, I added data labels to point in the graph I found to be interesting.
### Table 1:
![Table 1](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/Outcomes_v_launch.png)

### Chart 1: 
###### [Results](#outcomes-based-on-launch-date)
![Theater_Outcomes_vs_Launch](https://raw.githubusercontent.com/annaS000/mywork/main/challenges/kickstarter/resources/Theater_Outcome_vs_Launch.png)
##### A Look at Chart 1:
 >This line graph depicts a small spike in successful outcomes in February followed by a short lull in March, but quickly increases to a very obvious peak of 111 cases in successes during the month of May. We then continue to see elevated numbers of success in the rest of the summer months, but are declining as we approach September. There is also a slight increase in October just to decline again after. I found this to be interesting so, I used the **Years** filter to see if this was a common occurrence throughout the years.

### Chart 2:
###### [Results](#outcomes-based-on-launch-date)
![Theater_Outcomes_vs_Launch2](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/Theater_Outcomes_vs_Launch2.png)
##### A Look at Chart 2:
>I broke up the data into two smaller intervals of years to see if I would yield similar results. This chart is displaying the results for the years 2015-2017. We can see the same peak in February appear along with a high peak in May. In this time frame, the spike in October was lost, but we still have a slight increase in November.

### Chart 3:
###### [Results](#outcomes-based-on-launch-date)
 ![Theater_Outcomes_vs_Launch3](https://raw.githubusercontent.com/annaS000/mywork/main/challenges/kickstarter/resources/Theater_Outcome_vs_Launch3.png)
 ##### A Look at Chart 3:
>This graph is displaying the results for the years 2009-2014. It is surprising to see there were *only* successful Theater campaigns during these years. It was even more surprising to see that there were no campaigns in February or May! There is not as much Theater data for these years, but we can still see that familiar peak right before summer, decline towards fall, and pick up near October/November. At first, I was considering maybe plays were not as popular during this time, but then it dawned on me that 2009 was when this website launched. So, this is data from the first 6 years of Kickstarter's existence which explains the minimal amount of data in these years.

### **Analysis of Outcomes Based on Goals**
For this analysis, I had to create ranges of funding goals and then use the **COUNTIFS()** function to count play campaign outcomes based on the goal range. After I collected those numbers, I summed the rows for the totals of projects per range and then found the percentages of each outcome. Using a PivotTable, I made the line graph representing the percentages(Chart 4) along with a bar chart of the totals per range (Chart 5).
### Table 2:
![Table 2](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/outcomes_v_goal_table.png)
### Table 3:
![Table 3](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/outcomes_v_goal_p.png)
### Chart 4:
##### [Results](#outcomes-based-on-goals)
![Outcomes_vs_Goals](https://raw.githubusercontent.com/annaS000/mywork/main/challenges/kickstarter/resources/Outcomes_vs_Goals.png)
##### A Look at Chart 4:
>Looking at this line graph, I located the funding goal ranges that have the highest and lowest success rates. The highest rates would be the campaigns less than $1000, $1000 to $4999, $35000 to $39999, and $40000 to $44999. The lowest rates belonged to the ranges $25000 to $29999 and $45000 to $49999.
### Chart 5:
##### [Results](#outcomes-based-on-goals)
![plays-per-goal](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/plays-per-goal.png)
##### A Look at Chart 5:
>Here, I made a chart that shows the total number of projects per goal range. I did this to help determine which ranges had substantial data to make any claims. We can see majority of the play campaigns had a funding goal between $1000 to $4999. As the goal ranges get more expensive the number of campaigns go down.

### **Challenges and Difficulties Encountered**
#### **Chart Limitations** 
* The biggest challenge I encountered was figuring out how I wanted to word the conclusions for this analysis. Since the challenge only asks us to make two charts to form our opinions, I felt very limited on what I could say about the outcomes of these campaigns with confidence. There are many variables that affect the outcomes. When making any statements about data, I want to make sure what I am saying is not misleading in any way. I decided to create a few more charts with other variables for my analysis to get a better understanding of the data as well as reformatting one of the original charts I made. This helped me get a clearer picture of the results and be more confident in my claims.  

#### **Formatting/Design Decisions**
* Deciding how I was going to format my graphs and charts was another challenge for me. I spent arguably too much time deciding how I wanted them to look. This was not required for the project, but I enjoy making my work look inviting for the viewer. Additionally, when I am providing evidence for my claims, I want to make sure the graph I am presenting highlights the conclusions that are being made while still displaying the whole story. So, I found a few [books](https://github.com/annaS000/kickstarter-analysis/blob/main/References.pdf) on portraying data to help me represent my results by seeing examples of effective charts.

    **Some of the suggestions I found helpful were:**

    * Trying out different charts to decide which one is the most effective style for presenting your data. Not all charts display certain data as well as others.
    * Avoiding clutter in charts, too much noise in a graph can be distracting and can overload the viewer with information. 
    * Being conscious of where the eyes are drawn to in the chart. For example, color can be used to emphasize different parts of the chart you want to discuss.

    With this information, I tried my best to take what I learned to create charts that I felt represented my data well. I am still hoping to improve these skills and be able to produce impressive visualizations.


---

## **Results**
This section will discuss my conclusions from the data and make recommendations for other visualizations.

---

#### **Outcomes Based on Launch Date**
1. What are two conclusions you can draw about the Outcomes based on Launch Date?
    
    * In [Chart 1](#chart-1) and [Chart 2](#chart-2), we saw that May was a very successful month for Theater campaigns. In general, right before/beginning of summer seems to be a great time to start a Theater campaign. This outcome stayed consistent throughout the years which leads me to believe it can be considered the safest campaign launch month and yielded the most successful projects for the Theater category.

    * Inversely, September consistently experienced a drop in successful campaigns. From this speculation, it could be said the most failed theater campaigns were launched at the end of summer. 

    * October appeared to be somewhat of a revival month for Theater campaigns based on these charts. It is possible that these campaigns may be for plays that are related to the upcoming holiday season which may be more desirable for people to support. 

    * [Chart 3](#chart-3) shows that all Theater campaigns did well in the first 6 years of Kickstarter being a website. Perhaps the fact that it was a new platform caused a lot of buzz which influenced people to support campaigns. 


#### **Outcomes Based on Goals**
2. What can you conclude about the Outcomes based on Goals?

    * Looking only at [Chart 4](#chart-4), it seems that the most successful campaigns had funding goals that were less than $1000, $1000 to $4999, and $35000 to $45000 because they had the highest percentages of successful campaigns. If we compare Chart 4 with [Chart 5](#chart-5), we can see that the ranges from $35000 to $39999 and $40000 to $44999 had very few data points. Too small of a sample can cause results to be unreliable. So, instead of making assumptions about the ranges with few data points, we can look at campaigns with funding goals that are less than $1000 and $1000 to $4999. These goal ranges had a lot more cases as well as having high success rates. So, I can confidently say those ranges saw more successful campaigns, but it may not necessarily mean lower funding goals *cause* success. It seems that most plays on Kickstarter have smaller budgets which I think is most likely due to these productions being done independently.

#### **Limitations of the Data**
3. What are some limitations of this dataset? 

    While this data set has many useful variables, I did notice a few limitations:

    * Starting with the 'goal' and 'pledged' columns, the data points here are labeled with the $ symbol, but a few columns down we can see some of these points are labeled as currencies other than USD. Since there is a mix of different currencies in this data set, I am not sure if they have been converted to USD to make accurate comparisons.
    
    * With the information in this data set, we were able to calculate an average donation per campaign, but we are not aware of how evenly these donations were given. We only know how many backers and total amount of money pledged for each campaign. What if there were backers that donated large sums that inflated the average?

    * Part of Kickstarter's business model is when backers pledge towards a campaign they receive rewards. We are not given what rewards were offered for each campaign. Perhaps some campaigns were more successful than others because they offered more appealing rewards.
    
    * Another limitation of this data is the genres of the plays we are using are not readily available. I suppose we can go through the blurbs of each title and decide, but it would be very useful to be able to have a column with that information and see if there is any relationship between outcomes and certain genres.

#### **Other Possible Charts**
4. What are some other possible tables and/or graphs that we could create?
    #### **Duration of Campaigns**:
    * Another way to use the Launch Date for analysis is by also use the End Date of the campaigns. I created a new column in the spreadsheet to show how many days each campaign lasted by using the function **DAYS()** and labeled it **Duration**. I was curious to see if the longer a campaign runs the more likely it will be successful because the longer time would allow more opportunities for backers to donate funds. I created charts and PivotTables similar to the ones for Outcomes Based on Goals by counting the number of outcomes per range of days using the **COUNTIFS()** function.  
    
#### **Count of Campaigns Based on Duration**
![Outcomes_vs_Duration](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/Outcomes_vs_Duration.png)

#### **Count of Campaigns Based on Duration**
![Outcomes_vs_Duration2](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/Outcomes_vs_Duration2.png)
##### Outcomes Based on Duration:
>In these two charts above, you can see that thought is actually not the case here. In fact, the sweet spot of how many days the campaigns ran is between 20-39 days. Not only is there a substantial amount of cases for these amounts of days, these ranges also have higher success rates.

#### **Charts Based on Backer Count**
* Other charts I made in relation to the Launch date used the **backers_count** and **country** columns.

#### **Count of Backers by Country**
![Backers by Country](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/backers-vs-country.png)
##### Backers by Country
>I wanted to display where in the world majority of the backers for plays were from. It is very evident that the US and GB were the leading countries in supporting plays. Next, I created charts to show the count of backers each month.

#### **Count of Backers per Month (All)**
![Backers per Month All](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/backer-per-month.png)

 #### **Count of Backers per Month (US)**
![Backers per Month US](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/backers-vs-months.png)

#### **Count of Backers per Month (GB)**
![Backers per Month GB](https://raw.githubusercontent.com/annaS000/kickstarter-analysis/main/resources/backers-per-monthGB.png)
##### Backers Throughout the Year
> As I suspected, these graphs look similar to the ones made for Theater Outcomes vs. Launch Date, specifically the line representing the successful campaigns. This makes sense that the months with higher counts of backers would also be the months with most successful campaigns. Something I found interesting about these graphs is usually October only shows a small spike in successful campaigns in the Outcomes vs. Launch Date graphs, but here October often has an impressive amount of backers relative to the graphs, especially in the chart for the US. 

#### **Reformatting Goals Chart**
* Lastly, I felt I could benefit from making a different style chart for Outcomes based on Goals.

#### **Variation of the Outcomes vs. Goals Chart**
![Outcomes_vs_Goals2](https://raw.githubusercontent.com/annaS000/mywork/main/challenges/kickstarter/resources/Outcomes_vs_Goals2.png)
##### Goals Chart Variation:
>While analyzing the line graph of Outcomes vs. Goals, I decided I wanted to see the data presented in a different way. After trying out a few different graphs, I found that I really liked the look of 100% stacked bar charts. I prefer seeing the percentages displayed as bars because it is clearer for me to see the values.

---

# References
[Click here](https://github.com/annaS000/kickstarter-analysis/blob/main/References.pdf) for references.
