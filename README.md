# ROS-install
 Installation steps Ros1

1.	Download  virtual box

2.	Download Ubuntu 20.04

3.	Install ubunto on a virtual box

4.	Typing Ros commands in Terminal
1. Add Official Noetic repo to Ubuntu
o	$ echo "deb http://packages.ros.org/ros/ubuntu focal main" | sudo tee /etc/apt/sources.list.d/ros-focal.list’

2. Add official ROS keyring
o	$ sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

3. Update the ROS package index
o	$ sudo apt update

4.Install ROS Noetic on Ubuntu 20.04

5.Install ros-noetic-desktop-full
o	$ sudo apt install ros-noetic-desktop-full

6.Install ros-noetic-desktop
o	$ sudo apt install ros-noetic-desktop

7.Install ros-noetic-base
o	$ sudo apt install ros-noetic-base
8.Install ros-noetic-core
o	$ sudo apt install ros-noetic-core
9.Set up ROS Noetic environment
o	$ echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
o	$ tail ~/.bashrc
o	$  source ~/.bashrc
o	$ roscd
o	$ roscore
