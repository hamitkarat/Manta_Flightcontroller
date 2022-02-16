# Manta_Flightcontroller
This is my latest project. It was made for Teknofest Unmanned Underwater Vehicle contest. It is a pcb board for an AUV. IT collects data from an IMU and a pressure sensor, communicates with Jetson Nano, runs PID control and controls the motors of the vehicle.
This pcb has stm32l152ret6 microcontroller. It can be programmed with ST-Link V2. It has headers for motor drivers, lights, MPU 6050 IMU sensor, MS5837-02BA pressure sensor.
It also has a 5V power port, a voltage regulator for 5V to 3.3V. This board can communicate with Jetson Nano with usb-ttl. It also has extra headers for the future ideas.
