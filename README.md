# pyber-analysis

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/4796dc8c3d14b6a5c595430828bd277bf8bcf3cd/ridesharing_future.png.webp)

[Source](https://www.theengineblock.com/uber-lyft-and-the-culture-of-ridesharing-can-it-survive/)

## OVERVIEW

This exploratory analysis aims to assist PyBer in improving access to rideshare services, and determining affordability for underserved areas by identifying trends in ridership and fare data. 

The data provided categorized each service region by type (Urban, Suburban, and Rural). Each type was then analyzed based on the following criteria:

* The total rides (%)
* The total drivers (%)
* The total fares (%)
* The average fare per ride and driver
* The total fare by city type

In the second part of the analysis, the weekly fares for each city type were plotted over a period of 5 months in order to determine trends in usage and revenue.

The data was analyzed using the Pandas and Matplotlib libraries in Python 3.9.3, and visualized in Jupyter Notebook 6.3.0.

## QUICK LINKS

[City Data](https://github.com/farwaali08/pyber-analysis/blob/c756bf2e18c8f727e5f3b5a21dd6413296f45aa2/Resources/city_data.csv)

[Ride Data](https://github.com/farwaali08/pyber-analysis/blob/c756bf2e18c8f727e5f3b5a21dd6413296f45aa2/Resources/ride_data.csv)

[PyBer Ride Data](https://github.com/farwaali08/pyber-analysis/blob/c756bf2e18c8f727e5f3b5a21dd6413296f45aa2/Resources/PyBer_ride_data.csv)

[PyBer Analysis](https://github.com/farwaali08/pyber-analysis/blob/c756bf2e18c8f727e5f3b5a21dd6413296f45aa2/Resources/PyBer_Challenge_starter.ipynb)

## RESULTS & ANALYSIS

The results for the first part of the analysis are summarized below:

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/7a7c6f235fe04ef779c1b2a9657866a4692dbf8d/pyber_summary_df.png)

### TOTAL RIDES

It quickly becomes apparent that the majority of PyBer's ridership can be observed in Urban areas. Urban ridership represents 68.4%, or roughly two-thirds of all rides during the observed period (Jan-April 2019). The remaining third is divided amongst the Suburban and Rural categories, with the latter representing only 5.3% of all rides.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/9764daf1a95a3ab1089e8b065326dd3fe3670ab0/total-rides.png)



### TOTAL DRIVERS

More than 80% of all PyBer drivers conducted business in the Urban areas, as illustrated in the figure below. This, coupled with the ride data in the image above demonstrates, a higher demand for ride-sharing services in urban areas. In accordance with basic economics, the higher supply of drivers is necessary to fulfill the higher demand for rides. It will also impact pricing, which will be discussed later on.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/c9c6319723a4f40fe3bf6f008dda72feae064c6d/total_drivers.png)



### TOTAL FARES

Nearly 63% of all fares, or revenue, for this period was collected in Urban areas. This is likely to due to the higher number of rides overall. Interestingly, Surburban drivers and rides represented 16.5% and 26.3% of their respective data populations, and 30.5% of total fares. This can speak to the cost of

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/abde4f6cb9f45de6641f819cef3e723b11d49459/total_fares.png)

## SUMMARY
