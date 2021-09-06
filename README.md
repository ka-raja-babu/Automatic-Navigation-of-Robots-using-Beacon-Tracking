# Autonomous Navigation of Robots using Beacon Tracking

1) Initially, ESP32 mounted on the robot will read RSSI
(Radio Signal Strength Indicator) levels in forward, right and
left direction by suitable in-place rotation.
2) Average of 20 RSSI values are taken while measuring
RSSI level in a particular direction. This is done in order to
read accurate RSSI levels.
3) The robot then rotates towards the direction having the
highest RSSI level.
4) Further, It moves forward with a distance depending on the
free space available in front of it. The free space in front of
the robot is measured using ultrasonic sensor.
5) By repeating above steps again and again, the robot
navigates towards the beacon.

![alt text](https://github.com/ka-raja-babu/Beacon-Tracking-for-Robot-Navigation/blob/main/Images/Beacon_Tracking%20(1).jpeg?raw=true)
![alt text](https://github.com/ka-raja-babu/Beacon-Tracking-for-Robot-Navigation/blob/main/Images/Beacon_Tracking%20(2).jpeg?raw=true)
![alt text](https://github.com/ka-raja-babu/Beacon-Tracking-for-Robot-Navigation/blob/main/Images/Beacon_Tracking%20(3).jpeg?raw=true)
