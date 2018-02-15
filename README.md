# Machine Learning Assignment 5

###Jonathan Fermin

##Goals:
- Learn basic feature extraction using the accelerometer of the Microbit
- Using Microbit, detect "jerk" which is the rate (derivative) of acceleration 
- Smooth out the values of acceleration in the microbit
- Both of these are on a plane - no tilting

##Tools:
* [Wekinator](http://www.wekinator.org/downloads/)
* [Wekinator Input Helper](http://www.wekinator.org/input-helper/)
* [Micro:Bit](http://microbit.org/guide/)

##Accomplished:
Even when sitting, the microbit's accelerometer values jumped around. The smoothed values provide a better reading of the accelerometer. Perhaps by sending these values to the jerk it could also be useful

The jerk could be useful if using the microbit as a drum hitter, as the acceleration would hit as you were swinging, however the jerk would play a sound when the acceleration peaked. 


##ML Decisions 
For most of the project, I used Linear/Polynomial Regression as it would work better to detect jerk values that are at a high point.

For a classifier project, I probably would have used k-nearest neighbor and only used the jerk values.

