# SydneyHousePricesCovid
Impact of Covid on Sydney House Prices

Question: Are suburbs of Sydney related when it comes to changes in house prices. If so, which?

To answer this question we will take the following steps:
(a) Getting the data set
1. Obtain a list of auction results from scraping the domain.
2. Add in: LGA regions from the postcode
3. Add in: Distance of house from train stations (in km).
4. Output complete data file.

(b) Analysing the data set
1. Decide how we are going analyse houses:
   i. By LGA Region or by Suburb. Latter requires significantly more data to be satatistically significant and was eventually dropped.
   ii. What time period should we group under - quarter or monthy. Latter requires significantly more data to be satatistically significant and was eventually dropped.
   iii. How dow we compare - absolute price or percentage of change. Absolute price was eventually chosen.
   NOTE: the by setting variables in the code we can decide how we are going to do the analysis (8 options)
2. Create our consolidated data set with a "average proprty price" for each [region] and [time-period]. The average price is created by using LinearRegression over key features for each property and then calculating the price of the "average property" for that data point.
3. 


