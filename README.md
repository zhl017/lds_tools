# lds_tools
## Need ROS packages
Requires ``hector_slam`` & ``hld_lfcd_lds_driver``.
If not installed, install on Ubuntu with:
```
sudo apt-get install ros-kinetic-hector-slam ros-kinetic-hls-lfcd-lds-driver 
```
## Run
- LDS-01
```
roslaunch hls_lfcd_lds_driver hlds_laser.launch 
```
roslaunch 
- SLAM:
```
roslaunch lds_tools lds01_hector.launch 
```
- View map:
```
roslaunch lds_tools view_map.launch 
```
