
# Approach
Sampling of time data from the ultrasonic sensor.
Calibration to map the time data into real distance using a fitting function.
Localization to calculate the x and y coordinates of the object. (Used Distance formula)
Filtering the noise in position data using a Kalman filter.
Output the distance in real time and flash an LED and sound a buzzer when filtering is done.(after convergence)

# Hardware 


![](Code/Images/4.png )

The hardware used for this task are: Arduino Uno board, two HCSR04 sensors, breadboard and wires to connect everything, resistor, LED and buzzer. The given figure explains the connections used in the setup.


![](Code/Images/Picture8.png )
