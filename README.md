


view the robot on rviz:

1. in the terminal, cd to the project workspace.
then build:
```
colcon build
```
and source :

```
source install/setup.bash
```

2. launch:(xml)

```
ros2 launch my_robot_description display.launch.xml
```


view the robot on gazebo:
```
ros2 launch my_robot_bringup my_robot_gazebo.launch.py
```
