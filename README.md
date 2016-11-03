# Drone-Linux-ROS

notes:  using this modules must modify some files 
including:  Drone-Linux-ROS/src/dji_sdk/launch/sdk_maniflod.launch
            Drone-Linux-ROS/src/dji_sdk/src/modules/dji_sdk_node_main.cpp


Firstly, needing use your own app_id and enc_key.
The next, changing baud_rate according to your drone's braudrate
Last and most important, amending serial port based on Linux or manifold

for linux, serial port is where /dev/ttyUSB0
for maniflod, serial port in /dev/ttyTHS1
