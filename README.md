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

The results for the first part of the analysis are as follows:

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/7a7c6f235fe04ef779c1b2a9657866a4692dbf8d/pyber_summary_df.png)



### TOTAL RIDES, DRIVERS, AND FARE

The individual data for each city type is summarized in the table above.

   * Total Number of Rides:   `2,375`
   * Total Number of Drivers: `2,973`
   * Total Fares:             `$63,538.64 USD`



### TOTAL RIDES BY CITY TYPE

It quickly becomes apparent that the majority of PyBer's ridership can be observed in Urban areas. Urban ridership represents 68.4%, or roughly two-thirds of all rides during the observed period (Jan-April 2019). The remaining third is divided amongst the Suburban and Rural categories, with the latter representing only 5.3% of all rides.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/9764daf1a95a3ab1089e8b065326dd3fe3670ab0/total-rides.png)




### TOTAL DRIVERS BY CITY TYPE

More than 80% of all PyBer drivers conducted business in the Urban areas, as illustrated in the figure below. This, coupled with the ride data in the image above, demonstrates a higher demand for ride-sharing services in urban areas. In accordance with basic economics, the higher supply of drivers is necessary to fulfill the higher demand for rides. It will also impact pricing, which will be discussed later on.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/c9c6319723a4f40fe3bf6f008dda72feae064c6d/total_drivers.png)




### TOTAL FARES BY CITY TYPE

Nearly 63% of all fares, or revenue, for this period was collected in Urban areas. This is likely to due to the higher number of rides overall. Interestingly, Surburban drivers and rides represented 16.5% and 26.3% of their respective data populations, and 30.5% of total fares. This is likely to due to the higher costs of rides in low

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/abde4f6cb9f45de6641f819cef3e723b11d49459/total_fares.png)




### AVERAGE FARE PER RIDE AND DRIVER 

The lowest average fares per ride and drivers were in the Urban city type. The average ride in an Urban city is $24.53, and the average fare per driver is $16.57. This was the only category where the fare per ride was higher than the fare per driver. One possible explanation for this could be a saturation of the Urban market. Although there is a high demand for drivers in Urban areas, there also seems to be a higher supply. This would result in a lower cost per ride. Assuming that PyBer's business practices follow those of [comparable competitors](https://help.lyft.com/hc/en-ca/articles/115013080008-How-ride-earnings-are-calculated#calc), ride earnings are calculated based on a set base earning, the time, and distance travelled. It is possible that due to the number of drivers, there is a lower base pay in Urban cities. Generally speaking, urban areas also have better amenities or facilities, which are in closer proximity to the population. As a result, this would shorten the distance travelled, and the travel times for those wanting to access these amenities. With respect to PyBer drivers, this would result in lower wages.

The same logic can be applied towards drivers in Suburban and Rural areas, as longer trips (with respect to both time and distance,) would increase the cost per ride. A lower supply of drivers would also impact the fare price, making it higher.



### TOTAL WEEKLY FARES BY CITY TYPE

Finally, when examining the weekly fares per city type, it is clear that the majority of revenue is due to Urban ridership, which consistently surpasses all other city types. PyBer is best suited for the Urban market.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/2d8c53cbd48c520280f22a518a84a69902929465/Final_Line_Graph.png)

## SUMMARY & NEXT STEPS
