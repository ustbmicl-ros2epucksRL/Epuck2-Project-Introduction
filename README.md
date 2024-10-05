# Epuck2-Project-Introduction
本项目主要研究内容为基于ROS2实现epuck2群智机器人基础功能及在各类特定场景中发挥多机器人优势，例如多机器人协同定位建图、导航等，已参加相关比赛srtp国家级项目，已获中国大学生计算机设计大赛三等奖。
现有指导教师两名，研究生数名。

学习方向：ROS2基本知识，Epuck多传感器融合建图导航

<img src="1.硬件介绍/e-puck2.jpg" width="30%">



epuck2相关资料：http://www.rosrobot.cn/?tags=36

pi-puck相关资料：http://www.rosrobot.cn/?cate=11

ROS2学习资料：https://www.mubu.com/doc/2KrR_lVv0cs

计设文档链接：https://pan.baidu.com/s/1LhhflCOCaNtV8-GXzQexBA

UWB测距板扩展资料
参考资料：
1. 官方资料：UWB （https://www.gctronic.com/doc/index.php?title=Ultra_Wide_Band_Extension ）+ pi-puck （https://www.gctronic.com/doc/index.php?title=Ultra_Wide_Band_Extension）
2. UWB驱动：
  1. 实验室：https://github.com/the-hive-lab，
    1. Python 库，用于连接 Qorvo（以前的 Decawave）DWM1001。https://github.com/the-hive-lab/pydwm1001
    2.  Qorvo DWM1001 UWB 传感器相关的 ROS2 驱动程序和支持包的文档和源代码：https://github.com/the-hive-lab/dwm1001_ros2
  2. Qorvo
    1. DWM1001c：https://www.qorvo.com/search?key=DWM1001c&mode=1&search-value=1
3. UWB应用：定位等
  1. 用于利用多个机器人同时看到的物体的空间信息来完善超宽带测距。https://github.com/TIERS/uwb-cooperative-mrs-localization
