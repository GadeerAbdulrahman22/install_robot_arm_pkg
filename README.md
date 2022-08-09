# install_robot_arm_pkg
Here are the steps of instal robot arm pkg

-Create a workspace

$ rosdep install --from-paths src --ignore-src -r -y



$ sudo apt-get install ros-kinetic-moveit

$ sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui

$ sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control



$ sudo apt-get install ros-melodic-moveit

$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui

$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control


$ sudo apt-get install ros-noetic-moveit

$ sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui

$ sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control


-Configuring Arduino with ROS

$ sudo ./install.sh 

$ sudo chmod 777 /dev/ttyUSB0


-Launch robot arm pkg

$ roslaunch robot_arm_pkg check_motors.launch

![Screenshot from 2022-08-09 13-39-37](https://user-images.githubusercontent.com/108222099/183771554-b6cccc15-6e0f-43b1-bbd6-ac056a8ccb30.png)
