# Challenges in Sensor Data
Most like data will be like time serious
1. The value of sensor data in t will strongly influence sensor at time t+1. => GPS
2. Every sensor has sampling rate -> the data is disparate -> no idea of what happens between sampling rate.
3. Don't have enough data point.
4. Remove noise -> may lose some information of data.


### Mean Filter

Create the window of a given size, wait till window full, each value will be replaced by the mean value in the given window.


Two problems: 

wait till window full -> delay of the computation. 

No sharp edges. -> Highly outliers data will effect the accuracy?


### Weighted Mean Filter

The old measurement still has effect, the newer, the larger effect.

### Median Filter

Except for outliers. computing/pick the median. Always use the value exist on the window -> doesn't create the data.    good for have the sharp edge

---

trajectory smooth, minimize the difference.


### Kalman Filter

underlying velocity

1. Make prediction most like value based on dynamic model.
2. measure, use sensor data to correct the prediction.

Dynamic model of the system
No lag
Tunable trade-off between model and measurement.
Uncertainty estimate
parameters are not intuitive
Overshooting

Bayesian
Gaussian
Linear
Online



### Particle Filter

Bayesian

Gaussian or not

Linear ot not

Online

General

Continuous or discrete vars

Great results

Memory usage

Slow

