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

It quickly becomes apparent that the majority of PyBer's ridership can be observed in Urban areas. The Urban rides represent 68.4%, or roughly two-thirds of all rides during the observed period (Jan-April 2019). The remaining third is divided amongst the Suburban and Rural categories, with the latter representing only 5.3% of all rides.

![alt_text](https://github.com/farwaali08/pyber-analysis/blob/9764daf1a95a3ab1089e8b065326dd3fe3670ab0/total-rides.png)
## SUMMARY
