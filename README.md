# ros-differential-robot
Mô tả

Mô phỏng xe 2 bánh vi sai và tay máy trong gazebo và mô tả trong rviz. Xe có thể di chuyển bằng bàn phím (bao gồm cả xe và tay máy), đồng thời có thể đọc được các cảm biến IMU, Lidar, Camera.
1. Setup môi trường

   ROS, Gazebo, Rviz
   Download source: git clone https://github.com/ThanhDuck/ros-differential-robot.git

   Đảm bảo không gian làm việc: catkin_make -> source devel/setup.bash

Các bước thực hiện
1. Chạy Gazebo và Rviz

roslaunch robot_arm_01 my_new_launch.launch 

2. Cấp quyền cho các file python

chmod +x control.py 
3. Điều khiển xe + tay máy

rosrun robot_arm_01 control.py 

4. Link video demo : ttps://www.youtube.com/watch?v=h3ZNki7OOS0
