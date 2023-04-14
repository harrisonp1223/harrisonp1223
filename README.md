# **Portfolio**

## About

I'm currently a student at Cal Poly SLO studying my Master's of Science in Business Analytics. I'm searching for a role as a Data Analyst, Business Analyst, Financial Analyst, or Data Scientist. I've taken part in multiple analytical & industry collaborated projects that are outlined below. Additionally, my technical skills and familiarity with programming platforms is listed. 

## Technical Skills

<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/r/r.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/5c058a388828bb5fde0bcafd4bc867b5bb3f26f3/topics/jupyternotebook/jupyternotebook.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/tableau/tableau.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/powerbi/powerbi.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/aws/aws.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/googleanalytics4/googleanalytics.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/excel/excel.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/microsoftword/word.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/powerpoint/powerpoint.png"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/googlecolab/googlecolab.png"></code>


# **Projects**

## P1: *Snapchat*

In my Cloud Computing class in my MSBA program our professor collaborated with Snapchat and received some pre-Covid data for us to forecast with. Our data encompassed a multi-year time period up until mid-March 2020, consisting of user engagement metrics. Our data was collected for Snapchat users in the Nordic countries.

Our task was to forecast Q1 2020 average user engagement and a range for Q2 2020 average user engagement. 

Unfortunately I cannot disclose the exact code I used on the project considering that it used confidential Snapchat data. 

To overview our process, we cleaned the provided data then created a training set. We used the fbprophet package in Python to create our forecasting model. In our model we treated the two weeks of lockdown affected data as a holiday, and then added seasonality effects for pre-Covid and post-Covid as well. We used this method for both predictions. 

We introduced some external data to aid in our exploratory analysis and identify potential trends in our forecasting model. We found relevant data on Netflix monthly user engagment in Denmark and commented on the apparent increases in user engagment post_Covid. To further aid our exploratory analysis, we evaluated daily power consumption data in Norway to consider a measure for daily electronic use - possibly correlated with mobile Snapchat usage. 



## P2: *Salesforce* 

In our MSBA program we partnered with Salesforce to work on a project for them.

Salesforce tasked us, a group of four MS Business Analytics students to solve this problem: They have hired many employees during covid that are scattered across the country, not necessarily near their 10 Salesforce headquarters. Our job was to build an analytical tool that takes an input of employee locations and recommend the optimal headquarters location for that group of employees to congregate at in terms of travel cost and travel time (Salesforce pays for the employees' travel costs and time). 

As a group we tackled this issue using Python and R to collect data, clean it, wrange it, and summarize it. In addition, we used Tableau to create visualizations and to be used as a dashboard for Salesforce to interact with (Tableau being the end user tool with inputs and an output recommendation). Additionally we used Dijkstra's Algorithm to find the optimal Salesforce Headquarters locations for employees to congregate at.  

Unfortunately, I'm unable to share the final deliverables because they involve confidential Salesforce data & information. 


## P3: *AT&T*

For our final quarter of the MSBA program, we partnered with AT&T to work on a project involving analysis of macroeconomic trend segmentation and geographic customer behaviors. 

Our task is to develop geographic segments that are differentiated by how macroaeconomic trends impact customer and purchasing behaviors. Additionally, we'll need to compare the segments against each other at the national level, and accounting for population changes. Using this analysis, we'll then apply it to recommend optimal strategies for AT&T to promote products and services for their subcribers (using target marketing essentially) and to aid AT&T in retaining their current customers. 

Our data from AT&T was provided through AWS services and we will be working with the data within EC2 instances. We will use Python and R to achieve the tasks outlined above. 

Again, unforunately I'm unable to share our exact processes and code because they involve confidential AT&T data & information. 



## P4: *Housing Market Analysis*

The project aims to investigate how employee migration resulting from remote work affects housing market prices. The project's hypothesis stated that an increase or decrease in county residents due to relocation from different counties would result in a corresponding increase or decrease in county median housing prices. California county data was chosen for the project due to its familiarity and abundance of data. 

To measure the state of the housing market in California, median household prices for every county were obtained from Zillow. In the project we also looked at variables such as residents that worked from home, residents who moved in or out of the county from within or outside California, population, and employed residents. New constructed home sales data from redfin.com was also used for exploratory analysis.

In the project we used correlation plots to analyze the relationship between the main variables of interest and their correlations with home price change YoY. Regression analysis was also performed, including variables related to newly constructed homes ratio and income change. Our analysis found that the indirect supply and demand factors, such as net relocation ratios and work from home ratios, had a moderate effect on home price changes. However, it was found that external factors, such as new construction and income change, were integral variables in explaining the variability in housing prices.

The code and resulting graphics can be viewed on my Github repository "Housing Market Analysis". 

## P5: *Congressional District Analysis*

This project aimed to answer two questions: Are Democrats or Republicans better investors? And did Democrats or Republicans receive more COVID unemployment funding? The null hypotheses for both questions were that Democrats and Republicans, on average, are equally profitable investors and received an equal amount of unemployment funding during COVID. The project collected data from the census on household incomes for every congressional district in each state, and the dataset from the Internal Revenue Service included variables such as gross income, total income, taxed income, number of returns, amounts of returns, and many other variables.

The first hypothesis was tested by analyzing the total capital gain (or loss) in each district to characterize the investing performance of congressional parties with differing political designations. The results indicated that, on average, Democrats were more profitable investors than Republicans. The second hypothesis was tested by analyzing the total unemployment compensation received per district in 2020. The results showed that, on average, Democrats generally received more unemployment benefits than Republicans.

The conclusion of the project was that Democrats are more profitable investors than Republicans on average and that Democrats generally received more unemployment benefits than Republicans on average. The statistical analysis confirmed that Republicans and Democrats have different average Net Capital Gains, as well as having different amounts of COVID Unemployment Benefits. The project used data from the IRS and the census, and the results may be useful for policymakers and investors. 

The code and resulting graphics can be viewed on my Github repository "Congressional Analytics". 
