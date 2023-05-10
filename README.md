# Bike sharing casestudy
> BoomBikes is a US bike-sharing provider. They use a bike share system which allows people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock of BoomBikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Final model from linear regression](#final-model-from-linear-regression)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem statement
> BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. It has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end.
> The company wants to know:

> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
> season vs cnt:
> -	Season 3 which is the fall has maximum number of bookings. (Season 3>2>4>1)
> year vs cnt:
> -	2019 has a greater number of bookings than previous year which is a good sign of company's growth.
> Month vs cnt
> -	Total number of bookings are more during May-Sep/Oct but then there is a noticeable drop. Same observed during univariate analysis
> Week vs cnt
> -	Total number of bookings mostly same for all the days in week. There is little more demand on Thursday, Friday and Saturday. Little less on Sunday.
> weathersit vs cnt:
> -	'1' which represent clear or partly cloudy weather has more bookings. (Weathersit-1>2>3)
> holiday vs cnt:
> -	During the holidays, there is a dip in total number of bookings, if you compare 25-50 percentile.
> workingday vs cnt:
> -	 Workingday or not, they is no noticeable different.
## Final model from linear regression
> - total_bookings(cnt) = 0.0750 + 0.2331 * (year) + 0.0561 * (workingday) + 0.5499 * (temp) - 0.1552 * (windspeed) + 0.0886 * (season_summer) + 0.1307 * (season_winter) -0.0800 * (weathersit_2) - 0.2871 * (weatthersit_3) + 0.0974 * (mnth_sep) + 0.0675 * (weekend_6)



## Technologies Used
- Jupyter notebook - version 6.4.12
- Python - version 3.10.0
- Pandas - version 2.0
- Numpy - version 1.24.2
- Matplotlib.pyplot - version - 3.7.1
- seaborn - version - 0.12.2
- statsmodel - version - 0.14.0
- sklearn - version - 1.2.2

## Acknowledgements
- Upgrad
- Google in general


## Contact
Created by [@suryabandari247] - feel free to contact me!
