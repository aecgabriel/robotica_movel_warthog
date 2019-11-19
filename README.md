# robotica_movel_warthog

First unzip the repository into a catkin workspace and run:

```console
rosdep install --from-paths src --ignore-src -r -y
```

After instaling all the dependencies run:

```console
catkin_make
source your_workspace/devel/setup.bash
```

With a builded repo you can use the Robotica_movel package running:

```console
roslaunch robotica_movel warthog_world.launch
roslaunch robotica_movel simulation.launch
roslaunch robotica_movel mission.launch
```
