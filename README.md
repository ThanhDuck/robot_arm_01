# MID-TERM 
# Mô tả

Mô phỏng xe 2 bánh vi sai và tay máy trong gazebo và mô tả trong rviz. Xe có thể di chuyển bằng bàn phím (bao gồm cả xe và tay máy), đồng thời có thể đọc được các cảm biến IMU, Lidar, Camera.
# 1. Setup môi trường

   ROS, Gazebo, Rviz
   Download source: git clone https://github.com/ThanhDuck/ros-differential-robot.git

   Đảm bảo không gian làm việc: catkin_make -> source devel/setup.bash

# Các bước thực hiện :
# 1. Chạy Gazebo và Rviz

roslaunch robot_arm_01 my_new_launch.launch 

Lưu ý : Do chưa save nên add topic bằng tay từ mục by topic

![Screenshot from 2025-04-01 23-38-49](https://github.com/user-attachments/assets/30ab2ed7-f5c5-4f1e-8568-8f94a0b8ff96)

(camera là image)
Hình ảnh mô phỏng 
![Screenshot from 2025-04-01 23-34-48](https://github.com/user-attachments/assets/a5470871-2462-4375-9ab7-d336a9049458)

# 2. Cấp quyền cho các file python

chmod +x control.py 

# 3. Điều khiển xe + tay máy

rosrun robot_arm_01 control.py 

Hình ảnh : 
![Screenshot from 2025-04-01 23-36-47](https://github.com/user-attachments/assets/063f2ec0-11d0-44e7-9471-874b7fd29fb4)

# 4. Link video demo : 
https://www.youtube.com/watch?v=h3ZNki7OOS0
