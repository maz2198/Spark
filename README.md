# Spark

This repo represents work completed during the IE University's Spark course using PySpark.

## Chicago Crimes Analysis: 2014 -2016

The main purpose of this assignment was to choose a large open-source dataset, develop a persona/business case and answer business question using Spark queries taught in class. 

I chose the Chicago Crimes Dataset. This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. This dataset is available for download from [Chicago City Data Portal](https://www.kaggle.com/spirospolitis/chicago-crimes-20012018-november).

The code is outlined in `ChicagoCrimesIndividual.ipynb` and the business case and answers to the business queries are summarized in `MarangSparkAssignment.pdf`. 


## USA Flights Analysis


According to a 2010 report made by the US Federal Aviation Administration, the economic price of domestic flight delays generates yearly costs of USD 32.9 billion to passengers, airlines and other parts of the economy. More than half of that amount comes from the pockets of passengers, as they do not only waste time waiting for their planes to leave, but also in missed connecting flights, money spent not only on food but also sleeping on hotel rooms while they're stranded.

The report, focusing on data from the year 2007, estimated that air transportation delays put a a dent of USD 4 billion in the country's gross domestic product in that year. The full report can be found in the following link: [report](https://isr.umd.edu/NEXTOR/pubs/TDI_Report_Final_10_18_10_V3.pdf).

But which are the causes for these delays?

In order to answer this question, we analyzed the provided dataset, containing up to 1.936.758 different internal flights in the US for 2008 and the causes for their delays, diversions and cancellations; if any.

The data comes from the [U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS)](https://www.bts.gov/content/major-us-air-carrier-delays-cancellations-and-diversions).

This project was completed with Diego Cuartas and Nisrine Ferahi.
