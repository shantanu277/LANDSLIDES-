# LANDSLIDES-
The basic idea of our system is enabling the user to
know whether a landslide can occur in a particular loc‐
ation or not. We are collecting the data regarding the
landslides that have occurred in the past few decades
based on which, we have created a criteria to judge
the parameters of a upcoming landslide. We have
randomly taken the data of some of the past occurred
landslides around the globe where our parameters are
rainfall, elevation and type of soil. So what we have
done is we have coded a program which checks the
data interpreted according to the location provided
by the user and a range has been created for each of
the parameter. If the values of different parameters
fall in our range then the site will automatically give a
approximate chances of occurrence of a landslide.

#POSSIBLE SOLUTIONS

Solution1

Parameter identified that govern landslide-
1. Rainfall
2. Elevation
3. Seismic activity
4. Soil Moisture
5. Soil Type
6. Green Cover


The data set reagarding landslides available over the internet is rather incomplete to supply the required parameter of rainfall, soil type, greencover etc of the place of incident. Hence, we collected the required data separately and tried to make our own data set, providing us with all the data required for the parameters.


On arranging each data type into ranges, and marking the number of occurances of landslides in each range, we define the probability of landslide occuring when the current atmospheric conditons at a place matches with the range.

Hence, on combining the probabilities of all the parameters, we get the net probability of the landslide occuring.

The solution has a statistical approach, which was taken as there is no correlation among the parameters (rainfall, elevation, etc.)

# Working

The web based platform acquires user location and the parametric data using multiple APIs and hence provide the probability of occurance of a landslide.

With adequate amount of data available, we can use linear regression to accurately predict the weightage of each paramater rather than spliting the data into ranges and using statistics.

SOLUTION 2

To alert the people before landslide,we can install systems in landslide prone areas  which detect and transmits the live data
(like Soil moisture and  vibrational activity) of that particular place.Whenever the values cross a particular threshold values 
the system can alarm the buzzer and send an alert to an evacuation team ,which then can evacuate the nearby area.

#Working 
Things required 
1.Micro Controller
2.Soil Moisture Sensor
3.Triaxial accelerometer
4.Rain Gauge
5.Buzzer

Whenever the sensor cross a threshold value the microcontroller can alarm the buzzer which alerts the officer and evacutaion team can be notified.We can also make a website for people to know the live condition of that area .If we add an LTE modem,the system can send emails and sms to people who have registered themselves on the website.This enables the people to evacuate and
save lives.The only problem we face is there isn't data set available for rainfall, green cover and soil type.This disabled us to come to a common ground on which landslide can be identified as the data don't converge but the system that we install can somewhat predict the landslide. 
