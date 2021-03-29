# amcl_localize

A ROS package realizing localization of a simulated mobile robot using Adaptive Monte Carlo Localization (AMCL). 

In terminal window 1, launch the robot simulation from the `my_robot` package (which uses Gazebo world from `my_world` package):

```bash
roslaunch my_robot world.launch
```

In terminal window 2, launch the `amcl` and `move_base` nodes from this package:

```bash
roslaunch amcl_localize amcl.launch
```