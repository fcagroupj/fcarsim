# fcarsim
Client example of Carla simulator with cv2 or OpenCV in python.
CARLA is an open-source simulator for autonomous driving research. 

# how to use
 1) download carla simulator from https://github.com/carla-simulator/carla
 2) compile carla following steps in https://carla.readthedocs.io/en/latest/how_to_build_on_linux/
 3) start server by running  ./CarlaUE4.sh
 4) start jupyter notebook and open manual_control10.ipynb

# list of keyboard control
          F1      restart
          F5      toggle _autopilot_enabled
          F9      recording
          F11     next_weather    reversed
          F12     next_weather
          0-9     set_sensors
          w           throtle
    a         d       steer 
       z              reverse control
         
          s       brake
          h       hand-brake
          tab     toggle camera
