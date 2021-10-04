# Amazon_Vine_Analysis
## Overview

The general purpose of the study is to utilize Google colab, SQL, and python in order to analyze Amazon reviews that were written by the paid for Amazon vine program. Are utilizing Amazon‘s databases we can tap into there reserve of data based on these reviews and utilize pyspark and SQL in order to run an ETL analysis of the data sets to check for biases from Vine. This process will allow cell by stakeholders to understand whether the service is a worthwhile investment.

## Results

Going over the results we found the following data:

![results](https://github.com/nicbrownrigg/Amazon_Vine_Analysis/blob/main/results.PNG)

- There were 40,471 unpaid reviews, and 94 paid reviews.

- Of those reviews, 15,663 of the unpaid reviews were five stars. Of the 94 paid reviews, 48 were five stars.

- Which leads us to the percentages. 51.1% of the paid reviews were five stars versus 38.7% unpaid.

## Summary

As you can see based on the results of the ETL process, there could be an argument made for some positivity bias. Almost 13% more positive reviews is a staggering percentage to look at when it comes to the amount of paid five star reviews versus the unpaid 38%.   However as you can see from the results above there is an argument to be made at the data for the total paid reviews rest of the total on paid reviews can’t be very comparable because we see that the unpaid reviews total is on a magnitude of almost 10,000 times more than that of the paid for reviews. Any positive review in the paid for review section could have a staggering impact on the five star percentage just based on the small total they have versus the amount that would be needed to cause that same change the unpaid percentage. So intern I would say that there is a positivity bias in the Vine program but we’d perhaps have to run a comparison across multiple different product categories that are more representative of the SellBy company’s products. Perhaps also conduct some statistical analysis such as a distribution/standard deviation across these platforms to see how much this differs from the norm in terms of variance.
