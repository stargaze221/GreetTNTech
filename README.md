# GreetTNTech

## How to start rover from NUC
- rover@rover:~/ros2_ws$ source install/setup.bash
- rover@rover:~/ros2_ws$ ros2 launch roverrobotics_driver pro.launch.py

## Sending cmd_vel using ros2 topic
- rover@rover:~/ros2_ws$ ros2 topic pub /cmd_vel geometry_msgs/msg/Twist '{linear: {x: 0.5, y: 0.0, z: 0.0}, angular: {x: 0.0, y: 0.0, z: 0.0}}' -r 10
  
## To Do Tonigh
- Use joystick to send cmd_vel
