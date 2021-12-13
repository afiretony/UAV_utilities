# UAV_utilities
## Read and play bag files from realsense camera:
```
python read_bag.py -i example.bag
```

Step 0: Power connection and calibration

Step 1: Open terminal and type:
```
roscore
```
Step 2: Open new terminal, connect to drone PC by secure shell and initiate localization algorithm:
```
sh connection.sh
roslaunch cerlab_uav mavros_l515_t265_octomap.launch
```
Step 3: Open new terminal and launch inspection software:
```
roslaunch cerlab_uav rviz_inspection.launch
```
Step 4: Open new ternimal and start interactive algorithm:
```
roslaunch robot_explorer inspection_interactive.launch
```
