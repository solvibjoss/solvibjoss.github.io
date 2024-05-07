---
layout: page
title: Final Project
permalink: /Final Project/
---
Let's go


<embed 
       type="text/html" 
       src="../final/Crime_Map.html"
       width="700"
       height="700"
       >

Let's examine the country of origin for individuals found guilty of all crimes in 2022. Notably, Poland, Romania, Turkey, Syria, Lebanon, and Iraq stand out, each with over 2.000 crimes committed. However, it's important to consider that these figures are often related to immigration patterns. Therefore, we will also explore the top 10 source countries for immigration to Denmark to provide further context.

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

What catches the eye is that Ukrain is the third most migrated country from. 
It of course has a logical explaination that we are all aware of but it is interesting how drastically the migration has changed in last five years.
Below we can see a normalized of how much the residents from these countries has grown in last five years. As suspected Ukrain tops the list by almost quadruplling in size since 2019.

![norms_def][defa]



Now back to the crime data.
We would like to take a look at the ratio between crimes and residents by country.
![crime][def]

This tells us that Lebanon and Kuwait people have the most trouble with the law with over . The residents of Lebanon is complicated as it is belived that 2/3 of the immigrants are stateless [Palestians](https://vb.is/skodun/kostnadur-vegna-innflytjenda-danmork-og-sosialistar/)

Now we are interested to know what type of crimes the two countries have been committing the most.
![crime][kule]
"Road Traffic Act, other" leads as the most frequent crime in both Kuwait and Lebanon. Following closely in both countries are "Shoplifting, etc.," "Euphoriants Act," and "Other special laws," which occupy the next three positions, respectively. However, the fifth most common crime diverges; in Kuwait, it is "Common assault," whereas in Lebanon, it is the "Firearms Act." This indicates notable similarities in the crime patterns of both countries, albeit with some variations in specific types of less frequent crimes.

It is however no surprise that "Road Traffic Act, other" tops the charts since it is also the most frequent crime for Danes.

# Regions in Denmark
Now we would like to take a closer look at the highest crimes per. population by municipalities of Denmark.

<embed 
       type="text/html" 
       src="../final/dk_map_crimerate.html"
       width="840"
       height="550"
       >

Tårnby leads with the highest reported crime to population ratio at 15.43%, followed closely by Copenhagen at 14.17%. Other areas like Glostrup, Herlev, and Hvidovre show lower but significant ratios, demonstrating varied crime distributions relative to their populations.

[kule]: ../final/png/kuw_leb.png
[def]: ../final/png/crime_res_ratio.png
[defa]: ../final/png/norm_cange_immi.png
