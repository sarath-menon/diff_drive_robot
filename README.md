# diff_drive_robot
ROS package for two wheel differential drive robot with laser scanner attached in a variety of maze environments

To launch the robot with a laser scanner in a maze like environment agebo environment
```python
roslaunch diff_wheeled_robot_gazebo diff_wheeled_gazebo_with_laser.launch 
```
For keyboard teleoperation of the robot
```python
roslaunch diff_wheeled_robot_control keyboard_teleop.launch  
```
