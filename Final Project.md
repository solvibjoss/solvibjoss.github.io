---
layout: page
title: Final Project
permalink: /Final Project/
---
# Introduction
In this notebook, we'll delve into the dynamics of crime in Denmark using a couple of datasets. Firstly, we'll examine the crime rates across different regions, followed by an analysis of population demographics to understand the disparities. Here's the link to the data we've [source](https://www.statbank.dk/10059.)

Since we've recently relocated, exploring the crime landscape in Denmark seems like an intriguing idea. Our approach begins with pinpointing areas with the highest crime rates to gain a comprehensive understanding. Subsequently, we'll conduct a thorough investigation to uncover the underlying reasons behind these patterns. Finally, we'll compare Denmark's crime rates with those of other countries for comparative insights.

## Reported Crime in Denmark
Denmark is known as one of the [safest countries](https://studyindenmark.dk/news/copenhagen-ranks-highest-in-the-safe-cities-index-2021#:~:text=A%20new%20report%20by%20the,82.4%20points%20out%20of%20100.) in the world, praised for its peaceful cities and high levels of security. However, even in such a safe place, there's still some crime happening. Let's take a closer look at the crime situation in Denmark to understand how safety and crime can coexist.

Let's start by examining the top 14 reported crimes in Denmark over the last decade. Notably, the number one crime, "Other kinds of theft," has dropped by half. This suggests that improved documentation might be contributing to a decrease in these incidents, since the total number of crimes year-to-year has remained stable. We also observe that bicycle theft ranks as the second most common crime, which aligns with the common advice in Denmark: avoid buying expensive bicycles. Contrarily, bicycle theft is nowhere near the top 20 when it comes to identifying guilty individuals, which indicates that the police rarely manage to identify the perpetrators in these cases. More on guilty persons later.

# Regions in Denmark
Now we would like to take a closer look at the highest crimes per. population by municipalities of Denmark.

<embed 
       type="text/html" 
       src="../final/dk_map_crimerate.html"
       width="840"
       height="550"
       >

Tårnby leads with the highest reported crime to population ratio at 15.43%, followed closely by Copenhagen at 14.17%. Other areas like Glostrup, Herlev, and Hvidovre show lower but significant ratios, demonstrating varied crime distributions relative to their populations.

# Comparison Among the Nordic Countires
In this section, our aim is to examine the variations in crime rates across the Nordic countries. We'll focus on total offenses per population within each country. This analysis will allow us to evaluate Denmark's performance relative to its Nordic counterparts. Given the reputation of the Nordic countries for safety, it's intriguing to observe how they stack up against each other.

<embed 
       type="text/html" 
       src="../final/total_offenses_by_country_and_year.html"
       width="840"
       height="415"
       >
As illustrated by the graph, there is a consistent trend in the crime rates for all three countries. Notably, the crime rates for each country remain well below the global average of 5.61, recorded in 2020 ([Average Crime rates](https://www.macrotrends.net/global-metrics/countries/WLD/world/crime-rate-statistics)). If we compare among the nordic countires, Denmark and Norway, in particular exhibit exceptionally low crime rates, highlighting their favorable security environments compared to neigboring nations.

As, Sweden's elevated crime rates stand out when compared to those of its neighbors, which aligns with recent challenges the country has faced about the ability to manage crime, particularly those associated with individuals with different origin. Reports indicate that a substantial proportion of these crimes, particularly gang-related activities in major urban centers like Stockholm, Malmö and etc. are attributed mostly to individuals of non-native origin. A recent article highlights a troubling trend about the number of fatal shootings in Sweden has more than doubled since 2013, largely attributed to law enforcement's struggle to maintain control over certain criminal factions ([read more](https://www.theguardian.com/world/2023/nov/30/how-gang-violence-took-hold-of-sweden-in-five-charts)).

This situation in Sweden raises questions about Denmark's status concerning crimes committed by individuals born outside the country. We are now exploring how different crimes correlate with different origins to hopefully uncover some insightful patterns.


# Crimes by Country of Origin
In recent years, Denmark, like many other countries, has experienced significant demographic changes due to both migration and shifts in national policies. These changes have had profound effects on various societal aspects, including the landscape of criminal activity. This section explores the interplay between the origins of criminal offenders and crime rates. By analyzing data on the nationality of individuals involved in criminal activities, we can glean important insights into the patterns of crime relative to the diverse backgrounds of the offenders. 

![norms_def][DvsW]

This plot illustrates the shifting dynamics of crime ratios in Denmark from 2009 to 2022, based on the origin of the offenders. The blue line represents the ratio of criminal decisions involving Danish nationals relative to the total, which shows a significant decline over the period. Conversely, the red line indicates the ratio of criminal decisions involving non-Danish nationals, which has risen correspondingly. This trend reflects changing demographic patterns and possibly evolving law enforcement focus or reporting practices in Denmark, indicating a noteworthy shift in the origin of crime over the past decade.

Let's now examine the country of origin for individuals found guilty of all crimes in 2022.
<embed 
       type="text/html" 
       src="../final/Crime_Map.html"
       width="700"
       height="700"
       >

 Notably, Poland, Romania, Turkey, Syria, Lebanon, and Iraq stand out, each with over 2.000 crimes committed. However, it's important to consider that these figures are often related to immigration patterns. Therefore, we will also explore the top 10 source countries for immigration to Denmark to provide further context.

<embed 
       type="text/html" 
       src="../final/top10_countries_res.html"
       width="700"
       height="700"
       >

And here is the development for past 14 years.
<video width="680" height="540" controls>
  <source src="../final/vid/population_growth_by_country_cividis.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

What catches the eye is that Ukraine is the third most migrated country from. 
It of course has a logical explaination that we are all aware of but it is interesting how drastically the migration has changed in last five years.
Below we can see a normalized of how much the residents from these countries have grown in last five years. As suspected Ukraine tops the list by almost quadrupling in size since 2019.

![norms_def][defa]



Now back to the crime data.
We would like to take a look at the ratio between crimes and residents by country.
![crime][def]

This tells us that people from Lebanon and Kuwait have the most trouble with the law, with their crime-resident ratios higher than 20%. The situation of residents in Lebanon is complicated, as it is believed that 2/3 of the immigrants are stateless [Palestinians](https://vb.is/skodun/kostnadur-vegna-innflytjenda-danmork-og-sosialistar/), which may contribute to the complex socio-economic challenges and higher crime rates among this demographic 

Now we are interested to know what type of crimes the two countries have been committing the most.
![crime][kule]

"Road Traffic Act, other" leads as the most frequent crime in both Kuwait and Lebanon. Following closely in both countries are "Shoplifting, etc.," "Euphoriants Act," and "Other special laws," which occupy the next three positions, respectively. However, the fifth most common crime diverges; in Kuwait, it is "Common assault," whereas in Lebanon, it is the "Firearms Act." This indicates notable similarities in the crime patterns of both countries, albeit with some variations in specific types of less frequent crimes.

It is however no surprise that "Road Traffic Act, other" tops the charts since it is also the most frequent crime for Danes.


[DvsW]: ../final/png/danesvsworld.png
[kule]: ../final/png/Kuw_leb.png
[def]: ../final/png/crime_res_ratio.png
[defa]: ../final/png/norm_cange_immi.png
