# Containerized robot_localization package

Fuses sensor measurements from a wide range of sensors with an EKF or UKF. 

Main repo: https://github.com/cra-ros-pkg/robot_localization  
Documentation: http://docs.ros.org/en/noetic/api/robot_localization/html/index.html


## Usage

On host:
```
./build.sh #Builds and tags Docker image
./run.sh   #Runs Docker image with correct options 
```
    
Inside container:
```
build   #Alias to build colcon_ws as root user
run     #Alias to run ROS package as correct user
```
