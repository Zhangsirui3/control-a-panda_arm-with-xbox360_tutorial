# control-a-panda_arm-with-xbox360_tutorial
使用通用的手柄，操作panda机械臂 <br>
# 先决条件 <br>
请先git clone moveit2源代码
# 系统要求 <br>
  ubuntu 22.04
  ros 2 humble
  moveit 2 
  ros 2 joy-linux <br>
# 步骤
  **1.检测手柄** ```sudo apt install jstest-gtk``` <br>
  **2.安装joy-linux**```sudo apt install ros-humble-joy-linux```<br>
  **3.安装机器人摇杆控制功能包**```sudo apt install ros-humble-teleop-twist-joy```<br>
  **4.进入moveit2工作区，进行编译**```cd ws_moveit \ colcon build --executor sequential```<br>
  **5.运行案例启动文件**```ros2 launch moveit_servo servo_example.launch.py```<br>

