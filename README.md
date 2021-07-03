# show

 1985  cd show_ws/
 1986  roscore 
 1988  roslaunch hector_slam_launch tutorial.launch 
 1990  rosrun JoyStick joystick /dev/input/js0
 1993  rosrun move_robot move_robot /dev/ttyACM0 115200
 1995  rosrun sick_tim sick_tim551_2050001 "10.0.0.2" "10.0.0.3"
 1997  rosrun AnhungControl AnhungControl "192.168.72.198" 9930

 1998  cd Desktop/
 1999  python3 udp_send.py
