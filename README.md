# T_REX_I2C
Bringing ROS and T'Rex together

Use an arduino, p[robably a nano, to interface from ROS to the T'Rex controller via I2C.
The reason for integrating it this way is to keep the load off the motor controller so 
it can monitor the motors and impact detections accurately.
Using the i2c HLI it can send direction and speed commands as well as receive diagnostic 
data such as error codes, motor current, battery voltage etc
