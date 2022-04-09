# Regression-Analysis-Using-JMP-Pro

Mount Rainer is an active volcano and is one of the most dangerous volcanos in the world but that does not stop thrill seekers to drive by close to it to just get a glimpse of its magnificent beauty. There is only up to a certain limit that you can drive there, and many climbers take up the challenge to go to the top. Therefore, this makes it very thrilling destination.   Many climbers and tourists leave their car for days while climbing and do not have much information of their vehicle during that time. Thus, calculating the average battery voltage to see whether it is safe enough to leave it in the cold can be productive.



2.	Project Dataset Description:

The dataset being used in this project is Mount Rainer weather data of Sunrise Upper, which is at an elevation of 6400 feet. Sunrise upper is the highest point in Mount Rainer which can be driven by a vehicle. 

Characteristics of the Dataset:

•	The dataset is limited to timeframe of a week between 2021-11-24 (00:00:00) to 2021-11-30 (00:00:00).

•	The data is collected in an hourly basis in the given timeframe and consists total of 145 observations.

•	The data consists of Average Battery Voltage (v), Temperature (deg F), Relative Humidity (%), Wind Speed Average (mph) and Solar Radiation (W/m2) and all of them are continuous data.

•	The data is collected from Northwest Avalanche Center website on Mount Rainer.



3.	Project Goal & Objectives:

The main goal is to use Regression Analysis with given data including both simple linear regression and multiple linear regression.

Project Objectives:

a)	To determine the relationship between Average Battery Voltage (v), taken as Response Variable, and Relative Humidity (%), Temperature (deg F) Wind Speed Average (mph) and Solar Radiation (W/m2), all taken as Regressors using multiple linear regression.

b)	To perform ANOVA and Hypothesis Test of the objective a).



4.	Solution Approach and Analysis:

Now, each objective mentioned will be conducted in the JMP software respectively to determine the output.


Objective A:

To determine the relationship between Average Battery Voltage (v), taken as Response Variable, and Relative Humidity (%), Temperature (deg F) Wind Speed Average (mph) and Solar Radiation (W/m2), all taken as Regressors using multiple linear regression.

Solution and Result:

y ̂=13.1045+0.0042*x_1-0.0014* x_2-0.0149* x_3+0.0046* x_4 

Where, y ̂ is Average battery voltage (v), x_1 is temperature (deg F), x_2 is relative humidity (%), x_3 is wind speed average (mph) and x_4 is solar radiation (W/m2).


Objective B:

To perform ANOVA and Hypothesis Test of the objective a).

Solution and Result:

Now, we do hypothesis test for significance to determine if there is a linear relationship between the Response and any of the regressor variables.

The two hypotheses are:

H_0: β_1= β_2= β_3= β_4=0  

H_1: β_J  ≠0,atleast for one j

F_0=72.0055 
P – Value is < 0.0001*
F_0.05,4,140=2.4363 

Therefore, we reject the null hypothesis.

Thus, we can conclude that average battery voltage is significantly related to Relative Humidity (%), Temperature (deg F) Wind Speed Average (mph) and Solar Radiation (W/m2).

There aren’t any significant departures from the straight line and doesn’t seem to have any potential outliers. Thus, it is good enough to predict the values of the voltage.



5.	Conclusion and Recommendations 

In conclusion, since there we can also compare the predicted value of the battery voltage in the current temperature by displaying the average predicted value of the voltage.

Now, from this we can see that the average of predicted voltage value is 13.258 and the scientifically the optimal battery voltage required for a car is 12.6 and when the engine is running it should be 13.7 to14.7 volts [2], which is not much different than our result.

Therefore, we can conclude that the highest point which we can drive in Mount Rainer, which is Sunrise Upper is safe for car battery voltages despite there being a significant relationship between it and Relative Humidity (%), Temperature (deg F) Wind Speed Average (mph) and Solar Radiation (W/m2).


Future Work:

•	Further statistical analysis can be done using goodness of fit and test of independence.

•	Individual regressors can also be analyzed.

•	Hypothesis Tests can be done by taking climbers data to find the relation between climbing the mountain and the temperature.


6.	Appendix & Reference
[1] Northwest Avalanche Center. “Mount Rainer Weather Station .” Northwest Avalanche Center, 8 Oct. 2020, https://nwac.us/data-portal/location/mt-rainier/. 




