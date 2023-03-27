---
layout: post
title:  "How did the financial crisis affect crime?"
date:   2023-03-26 18:33:41 +0200
categories: jekyll update
---
1、Time series analysis

By observing the statistics of crime types in 2003-2010, we found some interesting phenomena. The selection of time refers to the two years around 2008 as the observation object and the first three years before the economic crisis began to roll up waves as the comparison year. We select crime types based on their yearly amount distribution:
(1) peaks around year 2008;
(2) is generally stable from 2003 to 2010 but have a significant increase/decrease before and after the economic crisis.
Through the above conditions, we screened out 5 types of crimes as follows:
['PROSTITUTION','ROBBERY','BURGLARY','DRUNKENNESS','DRUG/NARCOTIC']

Based on the sharp decline in the Dow Jones Industrial Average starting in December of 2007 as a sign of the onset of the financial crisis, we plotted the monthly growth rates of the five crimes relative to December 2007 crime numbers:

![](https://raw.githubusercontent.com/RuoxiSpace/RuoxiSpace.github.io/main/image/figure_6.jpg)

Interestingly, the first three types are all related to "acquisition of property", while the latter two are related to crimes fueled by alcohol and drug abuse, which might be driven by psychological desire. In the property acquisition category, the growth rate of ‘PROSTITUTION’is the most obvious, reaching a growth rate of 100% in the highest period. Coincidentally, this month was the period when the economic crisis broke out, and as time went by, the growth rate gradually slowed down.


For "DRUNKNESS" and "DRUG/NARCOTIC", in the article “Cultural Stereotypes About Income and Addiction”, the author proposed the relationship between income and alcohol and drug addiction. He found that although there are many influencing factors, high-income families will also be affected by social needs. alcohol and drug intake, but poverty is a more risky factor for substance abuse, as individuals living in poverty are more likely to experience stress, trauma, and social isolation, which can increase the likelihood of engaging in substance abuse as a coping mechanism.

2、Geographic migration of crimes of ‘opportunity’

Robbery and burglary are crimes of opportunity, meaning that they may be more likely to occur when criminals perceive a weakness in security or an easy target. During the financial crisis, businesses and individuals may have been more vulnerable to crime due to reduced security measures or other factors.
We already know that in the time series analysis, the amount of "ROBBERY" has increased by about 25%, but "BURGLARY" has decreased by about 20% during the same period. This caught our attention. In order to further explore, we plotted the regional distribution of the average number of crimes in "ROBBERY" and "BURGLARY" before and after the financial crisis, and found that the location of crimes has ‘migration phenomenon’! Both the changes occurred in the southeast of San Francisco, but there is also an exception, district "NORTHERN".


![](https://raw.githubusercontent.com/RuoxiSpace/RuoxiSpace.github.io/main/image/figure_3.png)

<embed type="text/html" src="file:///Users/zhoulihui/Desktop/my_map.html" width="800" height="600">

<embed type="text/html" src="https://raw.githubusercontent.com/RuoxiSpace/RuoxiSpace.github.io/main/image/my_map.html" width="800" height="600">


3、Crime relative frequency by hour

This is a 24-hour crime probability map for five crime categories potentially affected by the financial crisis between 2006 to 2009. You can see their trends within a day by switching types. "ROBBERY" and "BURGLARY" not only generate crime migration phenomena in space, but also "complement each other" in the time distribution of a day. This means that before and after the financial crisis, potential criminals will choose a more suitable place and time to commit crimes according to the current situation. Explore the comparison further. Unsurprisingly, after comparing the 24-hour distribution of "PROSTITUTION", "DRUNKNESS", and "DRUG/NARCOTIC" from 2003 to 2018, the 24-hour distribution during the financial crisis also followed this distribution trend, which shows that even these three categories Crime always tends to increase during the period, but does not affect the distribution of crimes during the day.




![](https://raw.githubusercontent.com/RuoxiSpace/RuoxiSpace.github.io/main/image/figure_4.png)
