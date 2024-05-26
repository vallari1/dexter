# DEXTER The helper bot

## **Installing Dexter**

- #### Clone this repo into your ROS 2 workspace `src`  directory to get Dexter as a package
```bash
mkdir dexter_ws/src
cd dexter_ws/src
 git clone https://github.com/vallari1/dexter/dexter.git
```

- #### Build the package, source the workspace to terminal
```bash
cd ~/dexter_ws
colcon build --symlink-install
source install/setup.bash
```

## **Running Dexter**
```bash
ros2 launch dexter bot_sim.launch.py world:=~/dexter_ws/src/dexter/worlds/empty_world.world
```

- ####  teleop_twist_keyboard node
```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
