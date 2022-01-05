# project_1

1.	Team Members:   		Erica Hoshino
                        Tuflika Putri
                        John Nasiakos
                        Mike Murphy

2.	Project Description:
The project uses John Hopkins University Covid-19 datasets and related datasets to determine the statistical significance of the relationship between being vaccinated or unvaccinated and the mortality rate from Covid_19.

3.	Research Questions:
•	What is the relationship between “unvaccinated” Covid patients versus “vaccinated” Covid patients for the following categories in selected countries?
o	Covid vaccination rates per country
o	Total Covid cases
o	Total Covid hospitalisations
o	Total Covid deaths
o	Mortality rates - per 100,000 population
o	Mortality rates – case / fatality ratio
•	What countries / areas will be most impacted?	 
•	What countries / areas will be least impacted?
•	The selected countries are Australia, New Zealand, USA, UK, Italy, Israel, Brazil, South Africa, Vietnam. 

4.	Hypothesis:
•	The alternative hypothesis (Ha) is that there is a significant correlation between vaccination status (vaccinated or unvaccinated) and death for Covid patients.
•	The null hypothesis (H0) is that there is not a significant correlation between vaccination status (vaccinated or unvaccinated) and death for Covid patients.


5.	Methodology:

•	The project commenced with a one-off download of a dataset covering some 32 days of data from the John Hopkins University Covid datasets identified above.
•	It then evolved to dynamically downloading the John Hopkins University Covid Time Series datasets using URLS calls and Wget so that it picks up the most recent data when run.
•	It also sourced mortality and vaccination datasets from the sources identified in the “Project datasets” section.
•	Further analysis needs to be done to fully complete the assessments we set out to do. 


5.	Visualisations / Analysis:
The visualisations used are:
•	Pie charts vaccinated vs unvaccinated per country					
•	Bar chart vaccination rates per country						
•	Bar chart total Covid cases per country						
•	Bar chart total Covid hospitalisations per country (if possible)				
•	Bar chart total Covid deaths per country						
•	Bar chart total mortality rates - per 100,000 population per country				
•	Bar chart total mortality rates - case / fatality ratio per country							

6.	Research Questions: Answers / Findings / Conclusions

•	What is the relationship between “unvaccinated” Covid patients versus “vaccinated” Covid patients for the following categories in selected countries?

o	Covid vaccination rates per country
	Covid vaccination rates vary widely with higher vaccination rates in developed countries and lower vaccination rates in less developed countries.

![image](https://user-images.githubusercontent.com/89948865/148156699-bdea8146-c98a-4654-9357-711293847804.png)

	Based on the bar chart that visualises the “Total Number of Fully 
Vaccinated People by Country”:
	The two countries with highest fully vaccinated numbers are US and Brazil
	The lowest numbers are New Zealand, Israel, South Africa, and Australia
	Simply based on this visualisation, we could be inclined to conclude that Brazil and the US are the most vaccinated countries in the world with the lowest numbers of fully vaccinated people being from New Zealand, Israel, South Africa, as well as Australia.

![image](https://user-images.githubusercontent.com/89948865/148158227-921b34f3-7f20-429f-a5e4-7059eb3a980e.png)


	However, if we look at the bar chart for the actual percentage of the
population that is fully vaccinated per country:
	We can see that the countries with the apparently higher number of vaccinated individuals like the US and Brazil (from the previous bar chart) have a lower bar compared to New Zealand and Australia.
	This could initially appear as a discrepancy, but once we consider the difference in population number between the countries, it can be explained.
	 The US population is close to 330 million compared to the Australian population, which has a little over 25 million, and New Zealand’s population, which only has 5 million in 
comparison.
	If we look at South Africa, we can see the percentage of the population that is fully vaccinated is less than half that of Australia, even though based on the previous bar chart, the number of vaccinated individuals was relatively close to that of Australia.
	This again, can be explained by the difference in population number, with South Africa reaching over 59 million and Australia with less than half that, at 25 million.
 
![image](https://user-images.githubusercontent.com/89948865/148158413-fa02955e-1760-4fd5-a48f-8bb91e653c44.png)

![image](https://user-images.githubusercontent.com/89948865/148158461-aa544bc7-71e0-4b24-8aec-253dabbec7b6.png)

	 We can further visualise these findings looking at these pie charts:
	 As you can see, a significant proportion of the population in 
Australia (over 75% in fact), are fully vaccinated compared to South Africa, where a whopping 74% of the population are actually unvaccinated.



https://docs.google.com/document/d/1tC0OtRsRGQUy0AhaMtuViVm6LKWjVgCT8R2ZFsUumcI/edit?usp=sharing
