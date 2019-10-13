# ROS_HW2
Homework with ROS

1. To run a HW you must create a folder inside catkin_ws/src/irf


2. Put all folders and files inside folder "irf"


3. Make compile of the project from home directiry


  $ cd ~/catkin_ws/ && catkin_make
  
  
  $ source ~/catkin_ws/devel/setup.bash
  
  
  $ cd src/irf/
  
  
4. Start roscore


  $ roscore
  
  
5. Now you can run a test using with RViz


  $ roslaunch irf display.launch model:=urdf/IRB14000.urdf
  
  
  
6. You can try to change scrools to be sure that robot's arm have a limits for revolute joints


Gazebo Report



  $ roslaunch irf main.launch


If you have a problem please wrote it to me in Telegram @AydarNazarov
