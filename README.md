# Challenge_7-8_Project1
Group Project 

_**Group Members: Jordan Kane, Van Hoang, Isha Sharma & Magdalene Singh**_

# Project name: 
**Data Analysis of Real Estate Market in Different Suburbs in South Australia**
--------------------------------------------------

**Research questions**
---------------

The project question is **“Has the price of housing in the Adelaide suburbs changed since before and after COVID?”**

**Overview**
---------------

The objective of this data analysis project is to examine the real estate market in different suburbs of South Australia using the dataset provided by the South Australian Government's Data Portal https://data.sa.gov.au/data/dataset/metro-median-house-sales . The dataset contains information on median house sales prices in various suburbs over a period of time. By analysing this data, we aim to gain insights into the trends and patterns affecting the housing market in different suburbs of South Australia before and after COVID 19.

**Objectives**
---------------

1.	Suburb Comparison: Compare and contrast the median house sales prices in different suburbs to identify high-performing and low-performing areas.
2.	Trends over Time: Analyse the trends in median house sales prices over time to understand the overall market trajectory in South Australia before and after COVID 19.
3.	Correlation with Factors: Explore the potential correlation between house prices and other factors such as location of the suburbs.

**Data Source**
---------------

The primary data source for this analysis will be the dataset provided by the South Australian Government's Data Portal https://data.sa.gov.au/data/dataset/metro-median-house-sales. The dataset includes historical records of median house sales prices in different suburbs in South Australia.

**Methodology**
---------------

1.	Data Collection: The first step will involve collecting the dataset from the provided website.
2.	Data Cleaning: Perform necessary data cleaning steps such as handling missing values and cleaning unnecessary data.
3.	Exploring Data: Conduct exploratory data analysis to gain initial insights into the dataset and visualize trends.
4.	Suburb Comparison: Compare median house sales prices in different suburbs using statistical measures and visualization techniques. Identify top-performing and underperforming suburbs.
5.	Correlation Analysis: Investigate potential correlations between house prices and other factors, such as locations of the suburbs.

  	 _We have splitted the location of suburbs around Adelaide CBD for analysis, starting with Jordan with Easten suburbs, Van with Southen Suburbs, Magdalene with Western Sburbs and Isha with Northen Suburbs:_
  	
  	_- Jordan: Eastern Suburbs (Burnside & Norwood)_
  	
  	_- Van: Southern Suburbs (Flagstaff Hill, Goodwood, Edwardstown, Pasadena, Adelaide CBD)_
  	
      _- Magdalene: Western suburbs (Findon, Grange & Seaton)_
  	
     _- Isha: Northen Suburbs (Modbury, Salisbury, North Adelaide, Enfield)_
  	   
7.	Insights: Summarize the findings from the analysis and provide insights to stakeholders in the presentation.
   
_**Notes: The Data Cleaning Jupyter Notebook includes the steps by steps of Data Collection, Data Cleaning and Exploring Data steps listed below. The Data Cleaning Notebook is using Python Pandas coding to combine data from the downloaded csv files, clean the data, and ensure the final data combinations are reliable for analysis. The Data Analysis and Visualisation Jupyter Notebook includes plotting processing and visualising data.**_


**Data Analysis and Visualisation**
---------------

Below are some of the highlights from our analysis, please find more details information from our report **"Report of Data Analysis of Real Estate Market in Different Suburbs in South Australia"** 

______**Eastern Suburbs**______

“Has the median house price in Norwood and Burnside changed from 2018-2022?”
![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/fca39c95-820c-416c-b604-0bfd5b0c502d)

Both suburbs have sharp increases in median house price from 2018-2022, and even though Burnside’s house sales are on a slow decline, their median house price is increasing at a faster rate than Norwood, to a point where Burnside’s median house price was around $100,000 cheaper than Norwood’s at the start of 2018, and by the end of 2022 they were the same, at between 1.4 and 1.5 million dollars.

______**Southern Suburbs**______

The suburbs of southern area include Goodwood, Edwardstown, Pasadena and Flagstaff Hill. The selection of suburbs for analysis adheres to a linear trajectory extending southward from the CBD, roughly encompassing distances of 1, 5, 10, and 20 kilometers from the CBD, respectively.

![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/747a1e59-7b01-48ed-8231-8fef0611d2a7)

When we examine the median house prices in selected suburbs in comparison to Adelaide CBD, it becomes apparent that both Goodwood and Adelaide started at similar price points in 2017. However, during 2019 and 2020, Goodwood gained a slightly higher price advantage over Adelaide. Notably, a significant leap occurred in Quarter 1 of 2021, propelling Goodwood's median house price from 1 million to 1.7 million. While there are instances in 2022 and 2023 where Goodwood and Adelaide share similar median house prices, the overall trend clearly demonstrates that Goodwood's housing market consistently holds a higher position than that of Adelaide. Among Pasadena, Edwardstown, and Flagstaff Hill, it appears they share the same trend line, with Pasadena having a slightly higher median house price from 2018 to 2022. However, it has slightly dipped below Flagstaff Hill and Edwardstown in the first two quarters of 2023.

![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/afbe2f37-561d-402b-adf0-9145d803cbff)

This graph presents a slight variation from the CBD pattern, the impact of COVID-19 in 2020 manifested during Quarter 4 of 2019 and Quarter 1 of 2020. Subsequently, the market exhibited a gradual and steady recovery, ultimately leading to a median house price of approximately 800 thousand dollars in 2023. Notably, this represents a remarkable price increase for Flagstaff Hill from 550 thousand dollars before the onset of COVID-19, marking a notable progression over the span of four years."

______**Western Suburbs**______

“Have the median house prices in Findon, Grange and Seaton changed from 2017-2023?”

The trend lines in the graph below, indicate that median house prices for all 3 suburbs are increasing on average.
Out of the 3 selected suburbs, Grange has experienced the highest price appreciation over the past 6½ years.  There was a significant increase in the median price for this suburb, starting off at $762.5k in 2017 and ending off in the 2nd quarter of 2023 at almost $1.2m.  

Findon and Seaton maintained steady and consistent price increases, starting off in 2017 at $512.5k and $525k respectively and ending off at $780.7k and $785k respectively.  Both suburbs were almost on par, increasing gradually.  

Median prices in these 3 suburbs started dropping from the 1st quarter of 2021, with Grange declining by $200k.  However, prices started increasing again in Q3 of 2022, despite the RBA increasing its cash rate from May 2022. 

![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/a632b00d-1582-49dc-9d34-69df957916f6)


______**Northern Suburbs**______

How the median house price in selected Northen Suburbs changed from 2017 to quarter 2 2023?

![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/c0c6a006-7788-499e-b6f3-4efeb4325c62)

For the analysis of the northern suburbs, we will examine North Adelaide, Enfield, Modbury, and Salisbury. These suburbs are arranged in increasing distances from the CBD. Given that North Adelaide is adjacent to the CBD, we can anticipate higher prices. Enfield is slightly closer to the CBD compared to Modbury, resulting in a higher price as well. However, from 2022 to 2023, the house prices in Modbury are catching up with Enfield. Salisbury is the farthest suburb in this analysis, suggesting that it likely has the most affordable house prices among the others.

**Conclusion**

![image](https://github.com/VanHg33/Challenge_7-8_Project1/assets/135322223/249cc83a-46a2-4fe1-ad0a-f9fcd15c03c3)

In conclusion, Modbury stands out with the most affordable median house price, followed by Seaton and Flagstaff Hill. On the whole, North Adelaide and Norwood are positioned at the highest median house price level in our analysis. Although Burnside has experienced a decline from its peak, it still maintains a higher price point compared to Adelaide and Grange.

**References**

Department of Planning, T. and I. (2023). Metro median house sales. data.sa.gov.au. [online] Available at: https://data.sa.gov.au/data/dataset/metro-median-house-sales.

Australian Bureau of Statistics, 2021 Census All Persons QuickStats, Available at: https://abs.gov.au/census/find-census-data/quickstats/2021/SAL40534


