# Exploring Monkey Pox Fatality 2022

![](https://github.com/PauloDaguvnor/Monkey-Pox-Fatality-2022/blob/main/Monkeypox_fatality_2022.png)

#Research Question
What is the overall mortality of Monkeypox in different locations and how did it change over time in 2022?
##Rationale For the Research Question /Aims**
To show whether the virus is deadly, especially in countries that had a high number of cases and also in countries thought to be endemic to the virus i.e. West and Central African countries.
We will also delve into the countries with high mortality to question patterns and also look at endemic countries to see if they have the highest deaths

## Introduction
The world was just starting to recover from the deadly covid 19 pandemic which had crippled the global economy and changed the way people converged when the news of another outbreak - Monkeypox emerged.
Monkeypox according the WHO is an infectious disease caused by the monkeypox virus. Generally, most people recover from it but in some instances, it can be deadly and also fatal. Seeing as covid 19 changed the way the world looked at human immunity against viruses, people had the cause to be scared.
Monkeypox can be spread through close contact with infected individuals.
The f
Data Acquisition
In order to consider the mortality, data was collected from Our World in Data who sourced it from the World Health Organization and the information is updated regularly.
https://ourworldindata.org/monkeypox

Our World in Data gets the latest version of WHO data on monkeypox and adds a transformed version on GitHub.

GithubCSV: https://monkeypox/owid-monkeypox-data.csv

Direct Raw Data: https://raw.githubusercontent.com/owid/monkeypox/main/owid-monkeypox-data.csv

For the analysis, the method to connect the data was via web in PowerBI. PowerBI connected directly to the GitHub link in order for the data to be refreshed to reflect the accuracy and any updates made by the data aggregators.

The columns relevant to the analysis are listed below with their metadata:

Location: This shows the Country. I renamed it to Country in the PowerBI report
iso_code: This is the iso code for each country. We need this column to create a continent column.
Total Cases: The daily cumulative addition of each case per country
Total Deaths: The daily cumulative addition of each death per country
New Case: The daily number of cases per day in a country
New Deaths: The daily number of cases per day in a country
![image](https://github.com/PauloDaguvnor/Monkey-Pox-Fatality-2022/assets/20201164/28fe15e6-bbe3-4161-b78b-8df7307c3061)


![image](https://github.com/PauloDaguvnor/Monkey-Pox-Fatality-2022/assets/20201164/871beecf-a703-443c-b52a-1ec92e34596f)

**View PowerBI Report Here👇**
https://app.powerbi.com/view?r=eyJrIjoiMzJhNDljM2UtZTcxYi00YmRmLWJiMDktMTgyYjE0MDg1ZWRmIiwidCI6Ijg2NTNhOTQwLTQ3MTItNDc5ZC04NzBlLWY5NTdhMTQzMjFlMCJ9


## Conclusion

The Monkeypox virus although not large scale as the covid 19 virus created a panic as the world was barely recovering from the disastrous effects of the pandemic and it was necessary to understand the scale of this virus and how deadly it is.

From the analysis, we can conclude that the Case Fatality Rate is not enough to justify decisions without context and more data. This was evident in Mozambique’s case. For the United States that had it would be useful to take a look of their health mechanism in handling affected patients as the cases appeared to be more fatal around October to November despite cases reducing.

Other metrics to take into consideration was the global proportion of cases and deaths to discover countries that are having a massive spread and whether there was an increase in deaths as a result.

For Africa being an endemic location of the Monkeypox virus, it had a surprising low level of cases and deaths unlike Americas and Europe. 

While the overall fatality of the virus was less than 1 percent, it would be useful to bolster health procedures and mechanisms to tackle the spread and death in order to prevent another global pandemic.



