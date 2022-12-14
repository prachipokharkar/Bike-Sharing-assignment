# Bicycle-sharing system
> A bike-sharing system is a service in which it made bikes available for shared use to individuals on a short-term basis for a price or free. The company is struggling to cope with the current market conditions. You feel that your business is being crippled by the lockdown, and that it will take a long time to recover once the lockdown is over. You feel you need to do something to prepare yourself for when things get back to normal. The consulting company wants to understand the factors affecting the demand for these shared bikes in the American market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Essentially the company wants :
- To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.
- To identify the variables affecting their revenues i.e. Which variables are significant in predicting the demand for shared bikes.
- To know the accuracy of the model, i.e. How well those variables describe the bike demands

They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Following features best fit the model 
  - work_day
  - temp
  - Sunday
  - Jul
  - winter
  - wind_speed
  - Light_Rain_Snow
  - Mist
  - Year
- This model gives an r-squared score  `0.815 - 0.812` w.r.t test data - training data
- 2019 has higher average number of users as compared to 2018

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.4.4
- matplotlib - 5.5.2
- seaborn - 0.11.2
- statsmodels - 0.13.2
- sklearn - 1.1.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This Assignment was a part of Linear Regression Assignment by Bangalore IIITB and LJMU


## Contact
Created by [Prachi Shivekar](@prachipokharkar) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
