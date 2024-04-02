---
layout: page
title: Micro Project
permalink: /Micro Project/
---
We will look into crimes in San Francisco from 2003 to mid-2018, with a particular focus on prostitution. This crime has revealed some intriguing patterns discovered during the first few weeks of the class "Social Data" at DTU.

We start by examining a calplot covering the entire data period.

 ![alt text](assets/images/Prosti_calplot03_18.png)

 The calplot depicting prostitution incidents from 2003 to 2018 reveals a fascinating trend. In the initial decade, there is a discernible decline in activity, as indicated by the progressively lighter shades of green each year, suggesting a potential reduction in prostitution crimes. However, the years that follow mark a notable shift. Beginning in 2014, there appears to be an extraordinary spike occurring once a month, with the intensity of the green much darker than even in 2009, which had the highest annual total for prostitution crimes within this data set.

This pattern may imply a strategic change in law enforcement approach, hinting that police operations or raids targeting these crimes might be concentrated into a single day each month, resulting in a significant number of charges being recorded on those specific dates. This shift in enforcement strategy could reflect a more focused or efficient allocation of police resources, potentially aiming for a greater impact by conducting comprehensive sweeps. It’s an intriguing development that warrants further investigation to understand the underlying causes of these enforcement patterns and their effectiveness in crime reduction strategies.
Prostitution from 2003 to 2018

To give us a feeling of the crime prone district we gather all crimes for the districts in San Francisco.
Below we have all crimes by distric. 
 <embed 
       type="text/html" 
       src="../assets/html/map.html"
       width="700"
       height="700"
       >
We can see that the souhern district has the most crimes.

Lets look at number of prostitution crimes by police districts. We can see that the Southern district is relatively low in prostitution.
<embed 
       type="text/html" 
       src="../assets/html/PROSTI_map.html"
       width="700"
       height="700"
       >

We can clearly see that Mission district dominates the other districts in this terrible crime. Although Pie Charts do not get a good reputation in the data science, I think it shows well in this example how dominant the Mission district is and together with the Northern district it makes up for two thirds of prostitution in San Francisco. Showing the dominant districts is the idea here and we think that the Pie Chart does that justice.


For fun you can play around with the pie chart and take out district to see how the proportions change.

<embed 
       type="text/html" 
       src="../assets/html/pie_chart_prostitution_crimes.html"
       width="700"
       height="700"
       >

<embed 
       type="text/html" 
       src="../assets/html/bar_chart_prostitution_crimes.html"
       width="700"
       height="700"
       >

Now, why is the Mission district so distinct from the others? 

Well, from my very limited research, I could see that one of San Francisco's finest brothels is located there. That could be one reason. Although I'm not entirely sure how the police operate in these types of crimes, I'm sure there is at least some correlation.

Often these type of crimes happen at nightclubs. From google maps the Southern district seem to have most nightclubs and could be a factor for being the top crime district but then not a factor for prostitution.

I't seems to be a middle-income district according to numbers from  [this](https://statisticalatlas.com/place/California/San-Francisco/Household-Income) website. It's has a lot of immigrants who migrated from the Latin countries in the 1950's [(More on that here)](https://www.qualityoflife-themovie.com/website/mission.html) so maybe prostitution is more prevalent in the Latino community, something to look into.

Contributions
Sölvi's focus was on the Calplot, pie and bar chart. Þórir focused on the heat map. They both helped each other on everything.