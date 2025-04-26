[**r2d2** (ros2dorna2)](https://github.com/pinorobotics/r2d2) - set of ROS2 packages which provide support for [Dorna2 robotic arm](https://dorna.ai/).

**r2d2_servo** package contains MoveIt2 Servo node for Dorna2 robotic arm.

NOTE: This is unofficial Dorna ROS2 package. For official Dorna software follow https://dorna.ai/

# Build

Build Dorna2 controller:
```
cd r2d2_control
gradle clean build
```

Build ROS packages:
```
cd <ROS WORKSPACE>
colcon build
source install/setup.zsh
```

# Run

``` bash
ros2 launch r2d2_servo servo_launch.py
```

Edit "servo_launch.py" in order to change Dorna controller default settings.

# Documentation

- [r2d2](https://github.com/pinorobotics/r2d2)

# Contacts

aeon_flux <aeon_flux@eclipso.ch>
