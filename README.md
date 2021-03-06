# DIY-LiDAR
Homemade LiDAR with minimum budget and components

LiDAR is a method for determining ranges (variable distance) by targeting an object with a laser and measuring the time for the reflected light to return to the receiver. LiDAR is an acronym for "light detection and ranging" or "laser imaging, detection, and ranging" Typically, light is reflected via backscattering, as opposed to the pure reflection one might find with a mirror. Different types of scattering are used for different LiDAR applications: most commonly Rayleigh scattering, Mie scattering, Raman scattering, and fluorescence. 

LiDAR technology is being used in robotics for the perception of the environment as well as object classification. The ability of LiDAR technology to provide three-dimensional elevation maps of the terrain, high precision distance to the ground, and approach velocity can enable the safe landing of robotic and manned vehicles with a high degree of precision. LiDAR is also widely used in robotics for simultaneous localization and mapping and is well integrated into robot simulators. The technology is also used in the control and navigation of some autonomous cars. Systems such as those by Siemens, Hella, Ouster and Cepton use a lidar device mounted on the front of the vehicle, such as the bumper, to monitor the distance between the vehicle and any vehicle in front of it. In the event, that the vehicle in front slows down or is too close, the ACC(Adaptive Cruise Control) applies the brakes to slow the vehicle. When the road ahead is clear, the ACC allows the vehicle to accelerate to a speed preset by the driver.

The goal of this project was to make a homemade LiDAR with a minimum budget and components. After tedious testing and fine-tuning we had a functional LiDAR which could map for obstacles within a certain range of the LiDAR( approx 2m ). Further applications of this project could be obstacle detection/avoidance RC cars and mapping of the surrounding environment which can be further extended to path planning and automated navigation using SLAM in ROS.

References:
Homemade LIDAR sensor with Arduino & Processing: https://www.youtube.com/watch?v=fQ2iB7qkrUg
https://lastminuteengineers.com/28byj48-stepper-motor-arduino-tutorial/	
Arduino Processing and  Bluetooth : https://www.youtube.com/watch?v=VGJCj0Hr1vQ
Serial Communication with Processing :: Video #2 :: Arduino Serial Communication Series: https://youtu.be/69EJkn65T_8
https://www.teachmemicro.com/arduino-bluetooth/	
Measure Distance with VL53L0X 6 pin Laser module with Arduino : https://www.youtube.com/watch?v=S2jaAQEv3Yo
https://www.arduino.cc 
