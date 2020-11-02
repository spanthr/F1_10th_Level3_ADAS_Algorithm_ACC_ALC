For ACC

Firstly, the Exponential filter and Servo library was imported in the code to use it in the next steps.
Variables were defined for exponential filter and PID controller and initial values were set for the steering and throttle.
Time data received from the ultrasonic sensor is sampled and converted to distance in real time.
Exponential Filter is implemented in Adaptive cruise control.
PD controller implementation for throttle control with the implementation of dead zone at 30cm from the wall so that the car does not fluctuate when stopped by an obstruction. PWM is also implemented to make the car run slower on the slope so that the car can steer well. Also, duty cycle was increased for the case when car has to climb the slope in reverse direction.

(Filtered_distance)[n] = w × (sensor_distance)[n] + (1 – w) × (Filtered_distance)[n–1] where, w is the weight factor from 0 to 1
Weight factor of 80% was selected to compromise between desired performance and system lag.


For Lane keeping

Firstly, the Exponential filter and Servo library was imported in the code to use it in the next steps.
Variables were defined for exponential filter and PID controller and initial values were set for the steering and throttle.
Time data received from the ultrasonic sensor is sampled and converted to distance in real time.
PD controller implemented for steering control.

