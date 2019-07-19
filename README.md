# turtlebot_laccan
Project for autonomous mapping to the laccan (Laboratory of Scientific Computation and Numerical Analysis) of the Federal University of Alagoas

Contains launch files that launch the Turtlebot. 

To conveniently install this package along, follow these instructions:

1. Make sure that wstool is installed

```sudo apt install python-wstool```

2. Create a new catkin_workspace

```
mkdir ~/catkin_ws
cd ~/catkin_ws
```

3. Use wstool to install the packages

```
wstool init src https://raw.githubusercontent.com/nfopma/turtlebot_laccan/master/turtlebot_exploration.rosinstall
```

4. Compile and source the workspace

```
catkin_make
source devel/setup.bash
```
