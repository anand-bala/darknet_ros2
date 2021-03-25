# Real-Time Object Detection for ROS2

This package is a thin wrapper around [darknet], a neural network platform for the You
Only Look Once (YOLO) object detection module. 


While this repository was initially a fork of [`darknet_ros`] to attempt to rectify some
[bugs] with OpenCV 4, I realized that the design for `darknet_ros2` can be simplified
for maintainability. The original [`darknet_ros`] definitely has more features, and you
should probably use that for most cases.

[darknet]: https://github.com/AlexeyAB/darknet
[`darknet_ros`]: https://github.com/leggedrobotics/darknet_ros
[bugs]: https://github.com/leggedrobotics/darknet_ros/search?q=opencv4&type=issues

