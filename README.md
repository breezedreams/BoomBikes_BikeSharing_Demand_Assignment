# Boom Bikes Bike Sharing Demand Assignment
> BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Table of Contents
*  Used Python for Coding
*  Used Linear Regression Model

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- The Data set is provided contains different number of variables like instant	dteday	season	yr	mnth	holiday	weekday	workingday	weathersit	temp	atemp	hum	windspeed	casual	registered	cnt and data dictionary is also given .


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We can infer that atemp predictor is having positive correlation having co-efficient of 0.47  with the demand. Other predictors which are having positive correlation are weather - Year,Clear Few Clouds ,Mist and Cloudy,weekday . Predictors having negative correlation are spring ,windspeed . 
In conclusion we can say when the Temperature Increases we can expect  increase in demand for bikes. If the weather is favorable with clear skys and no winds and there will be demand for bikes. In its Weekday  i.e working day we can see there is increase in demand
 Bad Weather days with heavy winds , cold and rains the demand will be less.
 Also we have seen positive correlation in the year so we can say demand will increase in the future years.



## Technologies Used
we Used different libraries like numpy ,pandas ,matplotlib.pyplot,seaborn ,
statsmodels,sklearn,RFE
For building the model I have used both Automated and manual process to arrive at the best fit model
