# project_1

1.	**Team Members:**   		Erica Hoshino
                                        Tuflika Putri
                                        John Nasiakos
                                        Mike Murphy


2.	**Project Description:
The project uses John Hopkins University Covid-19 datasets and related datasets to determine the statistical significance of the relationship between being vaccinated or unvaccinated and the mortality rate from Covid_19.**
  

3.	**Research Questions:**
* **What is the relationship between “unvaccinated” Covid patients versus “vaccinated” Covid patients for the following categories in selected countries?**
* Covid vaccination rates per country
* Total Covid cases
* Total Covid hospitalisations
* Total Covid deaths
* Mortality rates - per 100,000 population
* Mortality rates – case / fatality ratio
* What countries / areas will be most impacted?	 
* What countries / areas will be least impacted?
* The selected countries are Australia, New Zealand, USA, UK, Italy, Israel, Brazil, South Africa, Vietnam. 


4.	**Hypothesis:**
* **The alternative hypothesis (Ha)** is that there is a significant correlation between vaccination status (vaccinated or unvaccinated) and death for Covid patients.
* **The null hypothesis (H0)** is that there is not a significant correlation between vaccination status (vaccinated or unvaccinated) and death for Covid patients.


5.	**Methodology:**

* The project commenced with a one-off download of a dataset covering some 32 days of data from the John Hopkins University Covid datasets identified above.
* It then evolved to dynamically downloading the John Hopkins University Covid Time Series datasets using URLS calls and Wget so that  
        it picks up the most recent data when run.
* It also sourced mortality and vaccination datasets from the sources identified in the “Project datasets” section.
* Further analysis needs to be done to fully complete the assessments we set out to do. 


5.	**Visualisations / Analysis:**
The visualisations used are:
* Pie charts vaccinated vs unvaccinated per country					
* Bar chart vaccination rates per country						
* Bar chart total Covid cases per country						
* Bar chart total Covid hospitalisations per country (if possible)				
* Bar chart total Covid deaths per country						
* Bar chart total mortality rates - per 100,000 population per country				
* Bar chart total mortality rates - case / fatality ratio per country							


6.	**Research Questions: Answers**

**What is the relationship between “unvaccinated” Covid patients versus “vaccinated” Covid patients for the following categories in selected countries?**

* Covid vaccination rates per country
* Covid vaccination rates vary widely with higher vaccination rates in developed countries and lower vaccination rates in less developed countries.

![image](https://user-images.githubusercontent.com/89948865/148156699-bdea8146-c98a-4654-9357-711293847804.png)

* Based on the bar chart that visualises the “Total Number of Fully Vaccinated People by Country”:
* The two countries with highest fully vaccinated numbers are US and Brazil
* The lowest numbers are New Zealand, Israel, South Africa, and Australia
* Simply based on this visualisation, we could be inclined to conclude that Brazil and the US are the most vaccinated countries in the world  
  with the lowest numbers of fully vaccinated people being from New Zealand, Israel, South Africa, as well as Australia.

![image](https://user-images.githubusercontent.com/89948865/148158227-921b34f3-7f20-429f-a5e4-7059eb3a980e.png)


* However, if we look at the bar chart for the actual percentage of the population that is fully vaccinated per country:
* We can see that the countries with the apparently higher number of vaccinated individuals like the US and Brazil (from the previous bar chart)  
  have a lower bar compared to New Zealand and Australia.
* This could initially appear as a discrepancy, but once we consider the difference in population number between the countries, it can be explained.
* The US population is close to 330 million compared to the Australian population, which has a little over 25 million, and New Zealand’s population,  
  which only has 5 million in comparison.
* If we look at South Africa, we can see the percentage of the population that is fully vaccinated is less than half that of Australia,  
  even though based on the previous bar chart, the number of vaccinated individuals was relatively close to that of Australia.
* This again, can be explained by the difference in population number, with South Africa reaching over 59 million and Australia with less than half that, at 25 million.  

 
![image](https://user-images.githubusercontent.com/89948865/148158413-fa02955e-1760-4fd5-a48f-8bb91e653c44.png)

![image](https://user-images.githubusercontent.com/89948865/148158461-aa544bc7-71e0-4b24-8aec-253dabbec7b6.png)

*  We can further visualise these findings looking at these pie charts:
*  As you can see, a significant proportion of the population in Australia (over 75% in fact), are fully vaccinated compared to South Africa,  
   where a whopping 74% of the population are actually unvaccinated.

![image](https://user-images.githubusercontent.com/89948865/148158564-3251dc37-02b4-43ff-bb28-a40f87b780e2.png)


* Total Covid Deaths are highest in countries which were slow to introduce vaccinations and other containment measures like lockdowns (US and UK in our selected set) and are lowest in countries that were quick to introduce lockdowns and ramp up vaccination roll out (in particular New Zealand is the standout with Australia not far behind).

* **Covid cases – Deaths per 100,000 People per Country**

![image](https://user-images.githubusercontent.com/89948865/148158707-47cfae9d-d13e-4dbb-9124-6bd1d66e8a41.png)

* Total Covid Deaths per 100,000 people are similarly highest in countries which were slow to introduce vaccinations and other containment measures like lockdowns (US and UK in our selected set) and are lowest in countries that were quick to introduce lockdowns and ramp up vaccination roll out (in particular New Zealand is the standout with Australia not far behind).

* **Covid cases – Case Fatality Ratio**

![image](https://user-images.githubusercontent.com/89948865/148158764-031814da-8e71-4818-970d-fd0bd78a9450.png)


* The Case Fatality Ratio shows a completely different picture. Australia, Israel and particularly New Zealand show the lowest number of fatalities for the number of cases.  
* These countries all quickly adopted lockdowns and ramped up vaccination rates with commensurate positive outcomes.
* Brazil is by far the worst performed in respect of this measure with South Africa not far behind.  
* Brazil has been notorious for basically ignoring the pandemic and it is reflected in their results.  
* South Africa has an extremely low vaccination rate compared to other countries as show in the pie charts above. It also is a developing country with a significant gap  
  between those who have access to good healthcare and those that do not. 
* The US and the UK rank in the middle in terms of this measure. The respective leaders of these countries were slow to respond to the pandemic with commensurate lower result than the best performing countries on this measure. 


•	**Research Questions: Conclusions / Implications**

* Our analysis is a work in progress. It shows that there is a relationship between vaccination status (vaccinated or unvaccinated) and death for Covid patients.
* At this stage, we would have to say that there is a relationship between Covid vaccination status and Deaths but that it is not the significant relationship  
  that might have been expected.
* Further analysis of the datasets and further statistical analysis needs to be done to quantify the extent of this relationship.
* At this stage, we would also have to say that the null hypothesis (H0) - that there is not a significant correlation between vaccination status (vaccinated or unvaccinated) and death for Covid patients prevails.


6.	**Project Datasets:** 
	
* **The datasets for the project can be found at the following links.**
  
* **“JHU – Time Series Daily Reports”**
https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

* **“JHU – Daily Reports”**
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports

* **JHU link on how to use their data – accesses cases, vaccinations, and testing data**
https://coronavirus.jhu.edu/about/how-to-use-our-data

* **“World population data”**
https://www.worldometers.info/world-population/population-by-country/


https://docs.google.com/document/d/1tC0OtRsRGQUy0AhaMtuViVm6LKWjVgCT8R2ZFsUumcI/edit?usp=sharing
