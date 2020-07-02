# ROS-Installation-on-Ubuntu-System

![alt text](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Finsights.ubuntu.com%2Fwp-content%2Fuploads%2Fe203%2FROS.png&f=1&nofb=1)

## 1- What is ROS
ROS is a Robotic framework, and it's an acronym for Robot Operating System.
The main supported operating system for ROS is Ubuntu. ROS contain a huge amount of libraries you can use it in your code.

  هي بيئة عمل تُستخدم لبرمجة الروبوتات ونظام التشغيل الذي يدعمها هو Ubuntu.
  كما تحتوي على عدد كبير من المكتبات الجاهزة للاستخدام.
  
  
  ## 2- ROS Installation:
  1- Setup your sources.list:
  `sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`
  
  2- Set up your keys:
  `sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654`
  
  3-Installation:
  First, make sure your Debian package index is up-to-date:
  `sudo apt-get update`
  
  Desktop-Full Install: (Recommended) : ROS, rqt, rviz, robot-generic libraries, 2D/3D simulators, navigation and 2D/3D perception
 ` sudo apt-get install ros-kinetic-desktop-full`
  
  To find available packages, use:
  `pt-cache search ros-kinetic`
 
  4- Environment setup:
  `echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc source ~/.bashrc`
  
  ![Uploading Screen Shot 2020-07-02 at 2.41.01 AM.png…]()
  
  
  # 3- References:
  <li>https://wiki.ros.org/kinetic/Installation/Ubuntu</li>
  <li>https://roboticsbackend.com/what-is-ros/#What_is_ROS</li>
