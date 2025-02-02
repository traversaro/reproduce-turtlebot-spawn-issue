# reproduce-turtlebot-spawn-issue

Reproduce the issue discussed in https://github.com/RoboStack/ros-humble/issues/265 .

To reproduce, install pixi and then:

~~~
git clone https://github.com/traversaro/reproduce-turtlebot-spawn-issue
cd reproduce-turtlebot-spawn-issue
# Run with ros2-distro-mutex==0.6.0
pixi run -e mutex06 launch_sim
# Run with ros2-distro-mutex==0.5.0
pixi run -e mutex05 launch_sim
# Run with ros2-distro-mutex==0.3.0
pixi run -e mutex04 launch_sim
~~~
