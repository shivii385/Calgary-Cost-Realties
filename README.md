# Calgary-Cost-Realties
Comprehensive Analysis of rise &amp; growth in areas like housing prices, labor market dynamics and inflation rates in Calgary from 2017 to 2023,
In final project, a thorough examination is conducted over the transformation of economic indicators in Calgary during the time from 2017 to 2023. This study majorly focuses on the dynamic shifts in inflation, labour market conditions & housing prices providing in-depth understanding of economic perspective in aligned with growth of population. 

## Introduction

The 'Calgary Cost Realities' project initiates an exploration to unveil essential insights into the dynamics of living costs in Calgary. This comprehensive analysis extends beyond numerical figures, delving into the realms of housing, food, and the intricacies of the labor market. Through meticulous examination, the project aims to offer a thorough understanding of the economic tapestry shaping the daily lives of Calgary residents. Stakeholders are invited to navigate through the intricacies of place, food, and labor market reviews to illuminate the economic landscape of this vibrant city.
The initial objectives were:
•	Conduct a comprehensive analysis of the cost of living in Calgary.
•	Explore the nuances of housing expenses.
•	Examine the cost of food and its impact on overall subsistence expenses.
•	Investigate the dynamics of the job market, including employment opportunities, salaries, and labor market trends.
However, during the course of the work, it was observed regarding item 3 that it would be more appropriate to assess inflationary trends instead of solely focusing on food prices, as it is a broader and more suitable indicator for the cost of living.

## Problem Statement

The comprehensive analysis aims to scrutinize the intricacies of living costs in Calgary, focusing on multiple facets. The investigation encompasses a detailed exploration of housing expenses, to understand the financial implications on residents. Additionally, the study delves into the cost of goods and its consequential impact on the overall living expenses, shedding light on the affordability and accessibility of essential commodities. Furthermore, the research investigates the dynamic aspects of the labor market in Calgary, including employment opportunities, wage structures, and prevailing trends, providing a holistic view of the economic landscape influencing the financial well-being of the population.

![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/ea0c12a3-f221-43c8-a385-f0ca55685f4e)
.
## Data Collection

Prior to data acquisition, an intense search for possible data sources was carried out, and in the end it was decided to use only data from government sources, such as Calgary.CA, Alberta.CA and Statistics Canada, as they were more reliable. Despite this, it was necessary to obtain and work with more than 90 different datasets (since some were only available per month or quarter).
To ensure efficient preprocessing and appropriate data extraction, Bash scripting was used. This scripting language was useful in obtaining and aggregating raw data, ensuring its normalization to prepare the data as per the requirements.

Data Sets and Sources:

1. Labor Market Data – It provides a review of changes in Calgary’s labor market within the context of a cross-regional comparison for Canada. Monthly data were used for people over 15 years of age, of both sexes. (https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410001702),
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/3bb155e6-50da-4add-ad43-2562b66deb12)
 
2. Calgary Economic Indicators Data – It includes analysis and statistical illustrations of a set of economic indicators monitored by Corporate Economics that inform our forecasts. Highlighted indicators include employment, the number of EI recipients, natural gas and crude oil prices, home sales, average sale prices, and total building permit values. (https://www.calgary.ca/research/economic-indicators.html)
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/2e04c518-6c9d-4b90-ab66-c73e8a54652e)

3. Alberta Population Data - Alberta's components of population change. (https://open.alberta.ca/dataset/alberta-components-of-population-growth-by-quarter/resource/1ee4699b-772c-4429-ba2c-19139b68b787)
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/18c3b404-1ef5-476a-877e-6fd64e8ebe48)


## Data Exploration and Cleaning

In general, for cleaning and exploring the data, the following were carried out:
1. Using Bash: Obtaining, Consolidating, Ordering and Removing Duplicity
2. Using Excel: Evaluation, previous normalization, filter, grouping, transposition, treatment of invalid and null values, conflict resolution
3. Power BI: Creation of base table, import of datasets, definition of data types, table relationships, creation of visualization.

## Methodology

We chose to use Bash scripting, Excel and Power-BI due to the team's familiarity with these technologies, speeding up the data collection and preparation work.
For the analysis, it was decided to start with the national aspects that could affect the cost of living in Calgary, followed by the provincial aspects and then check the local aspects.

## Data Analysis

## 1.	Data Model 
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/acf9c103-7f05-4d11-9c24-270b125394ab)

 
## 2.	Insights 

### 2.1.	Canada Economy

When checking the national aspects that could have an impact on the cost of living in Calgary, it was observed that:
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/7f9d3290-814e-4532-9284-eaa3f1f5cf7a)

1)	In the period before the COVID-19 pandemic, Canadian GDP growth was 2.43%, however it was significantly reduced in the second quarter of 2020, plunging to a trough of -16.31%.

2)	In response to the economic and social impacts of the pandemic, Canada took several actions, including reducing the interest rate, which decreased from 2% per year to just 0.5% per year during the pandemic period, aiming to stimulate consumption.

3)	It is noted that these measures brought GDP recovery in the following years, however, the increase in economic activity began to result in a significant inflationary increase, increasing from 2.16% per year before the pandemic to a peak of 8.13% in the second quarter of 2022, which has led to a widespread increase in the Canadian cost of living.
 
4)	In response to the increase in inflation, Canada began seeking to curb consumption by increasing the interest rate, which became recurrently high, rising from 0.5% per year in the first quarter of 2022 to 5.25% per year in the third quarter of 2023, making credit more expensive.
 
5)	These measures are gradually reducing the speed of price increases, causing inflation at the beginning of the fourth quarter of 2023 to be 3.12% per year compared to the peak of 8.13% per year in 2022, which is a approaching the pre-pandemic level of 2.16% per year.
 
7)	This set of factors (high prices, high interest rates) has caused GDP growth to slow down, staying at 0.86% in the fourth quarter of 2023, significantly below the pre-pandemic level of 2.43%.
 
Given these factors, Canada is currently facing a scenario characterized by low economic growth (0.86%), a high interest rate (5.25%), and elevated prices of consumer goods due to cumulative inflation in recent years. While inflation has begun to ease, it remains at a relatively high level (3.12%) by the end of 2023.

### 2.2.	Alberta population growth

When assessing population numbers in Alberta, linear growth is observed from 2017 through the pre-pandemic period (beginning of 2020). This growth slowed significantly during the pandemic, gradually picking up pace in the second half of the following year (2021). Subsequently, rapid growth was noted from the second half of 2022 onward.
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/10f05f1f-e1e3-4aeb-a65a-a460d3025221)

 
By analyzing the type of population growth in Alberta, it was possible to note that:
 
Insight 1 - During the period from 2017 to the beginning of 2021, Alberta witnessed a population outflow to other provinces. However, the resulting population decline was offset by international immigration. This phenomenon was primarily attributed to the adverse impact on the labor market caused by a decline in oil prices. Individuals sought relocation to explore better education and employment opportunities elsewhere, responding to the economic challenges linked to the significant downturn in the oil and gas industry during that timeframe.

Insight 2 - Throughout the pandemic, the worldwide mobility of people encountered substantial barriers, leading to a near-halt in international immigration. Nevertheless, international immigrants already established in Canada capitalized on the adaptability of residency programs. As a result, a considerable surge in international immigrants to Alberta, drawn by favorable conditions, became apparent immediately after the pandemic. Additionally, in 2022, Alberta launched the 'Alberta is Calling' campaign. This initiative not only halted the exodus of residents to other provinces but also reversed the trend.

### 2.3.	Alberta Labour Force

When analyzing Full-Time and Part-Time jobs in Alberta, a robust trend is observed, marked by growth in numerous Full-Time positions (typically offering higher compensation) and a modest increase in certain Part-Time positions.
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/09e9416e-43a1-4397-8d7b-b094eed85b9b)


When analyzing the general number of jobs and the employment rate, it is noted that:
 
Insight 1 – Canada presents a seasonal behavior in relation to the number of jobs, with vacancies being created during the months of May to October, and being demobilized outside this period, this behavior is also repeated in Alberta. The numbers demonstrate continued growth in the number of new positions in Alberta.

Insight 2 - Despite the creation of new positions, it is worth highlighting that the number of new positions created has been lower than the population increase, meaning that the employment rate has suffered a slight decline over recent years. 
### 2.4.	Alberta Economy

When examining economic activity in Alberta, growth is evident in several sectors. However, it is important to note that, with high prices attributed to inflation, an anticipated increase in the financial volume of these sectors may indicate that families face increased expenses to access the same goods. This could potentially lead to a situation of impoverishment of the population, requiring greater assistance.

![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/fccc5795-989e-472f-983e-0519c781d29b)


When looking at the total number of personal bankruptcies in Alberta, a volume after the pandemic is lower than the pre-pandemic volume, however, the volume of bankruptcies in the first 3 quarters of 2023 is 9% higher than in 2022.

### 2.5.	Living Costs in Calgary

At this point in the study, we arrive at a scenario where:
1.	Canada is struggling with high prices due to high inflation in recent years, a high interest rate aimed at controlling price increases and low economic growth.
2.	Alberta has experienced above-average population growth (considering the study period), with a substantial influx of interprovincial and international immigrants. Although new jobs have been created, they lag slightly behind population growth. The number of personal bankruptcies this year is 9% higher than the previous year.
These factors directly influence the cost of living in Calgary, as can be seen below. 
 
![image](https://github.com/shivii385/Calgary-Cost-Realties/assets/145607467/33715420-934d-4855-a74b-c472aeea02d3)


Population growth in Calgary was directly influenced by the increase in immigration to Alberta, with significant population growth observed in the last 2 years.
This has caused an inflationary effect above that observed in Canada. Having reached a peak of 9.56% in Calgary compared to a peak of 8.13% across Canada in 2022.
Considering that inflation takes into account the price variation in a basket of consumer items that includes items such as food, shelter, furniture, clothing, transportation and recreation, it is noted that the impact of high inflationary effects on the Cost of Life in Calgary is meaningful.
This impact could be partially absorbed if there was a significant increase in workers' income, but the numbers show that the increase in income has not followed the increase in prices.
Moreover, population growth has directly impacted the housing costs in Calgary, leading to a substantial rise in property prices in recent years. This increase in prices is further compounded by elevated interest rates. As high-value goods financed at higher rates result in significantly larger installments, this places additional strain on families' budgets.
Residents in Calgary face a complex economic landscape characterized by high interest rates, a growing population, increasing residential average prices, fluctuating average hourly rates, and a historical trend of rising inflation during the last years.

## Conclusion

Calgary is a destination that has been increasingly attractive to immigrants, both national and international, owing to various city advantages and provincial incentives. However, a population surge without meticulous planning at the federal, provincial, and municipal levels has resulted in a significant spike in the cost of living for residents. Additionally, there is a noticeable misalignment between the number of jobs created and the pace of population growth, posing escalating challenges.
Furthermore, it has been observed that Canada is grappling with challenges in controlling inflation, exacerbating the impact on prices in Calgary.
Effective measures are imperative, including robust inflationary control, interest rate reductions, and the formulation of public policies to enhance housing, employment, and income conditions in the city. This is essential for fostering sustainable and long-term economic growth.
