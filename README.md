## L-shape Fitting for 3D LiDAR Point Clouds
An ROS implementation for L-shape fitting for 3D LiDAR point clouds

![Ubuntu](https://img.shields.io/badge/OS-Ubuntu-informational?style=flat&logo=ubuntu&logoColor=white&color=2bbc8a)
![ROS](https://img.shields.io/badge/Tools-ROS-informational?style=flat&logo=ROS&logoColor=white&color=2bbc8a)
![C++](https://img.shields.io/badge/Code-C++-informational?style=flat&logo=c%2B%2B&logoColor=white&color=2bbc8a)

![demo_1](media/demo_01.png)


## Reference
* Efficient L-Shape Fitting for Vehicle Detection Using Laser Scanners
* Autoware: core perception

## Features
* slow

**TODOs**
* imporove the running speed

**Known Issues**
* the fitting is slow

## Dependencies
* pcl

## How to use
    # clone the repo
    mkdir -p catkin_ws/src
    cd catkin_ws/src
    git clone https://github.com/HMX2013/L-shape-fitting-3D-LiDAR-ROS
    cd ../
    catkin build -DCMAKE_BUILD_TYPE=Release 
    or catkin_make
    roslaunch l_shape_fitting run_rviz.launch

## Contribution
You are welcome contributing to the package by opening a pull-request

We are following: 
[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html), 
[C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#main), 
and [ROS C++ Style Guide](http://wiki.ros.org/CppStyleGuide)

## License
MIT License
