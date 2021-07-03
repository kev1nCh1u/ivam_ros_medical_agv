# show

## start car
    cd show_ws/
    roscore 
    roslaunch hector_slam_launch tutorial.launch 
    rosrun JoyStick joystick /dev/input/js0
    rosrun move_robot move_robot /dev/ttyACM0 115200
    rosrun sick_tim sick_tim551_2050001 "10.0.0.2" "10.0.0.3"
    rosrun AnhungControl AnhungControl "192.168.72.198" 9930

## udp send
    cd Desktop/
    python3 udp_send.py
