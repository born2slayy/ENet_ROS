# ENet_ROS

STEPS

git clone https://github.com/born2slayy/ENet_ROS.git

roslaunch usb_cam usb_cam-test.launch

rosrun lane_detect ros_lane_detect.py --model-path /home/hyeji/catkin_ws/src/lane_detect/models/model_best_enet.pth

rqt_image_view  or rviz
