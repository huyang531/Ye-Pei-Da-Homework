# 智能机器人课程作业
## 简介
本模拟实现了一个拥有五个自由度的机械手结构。活动关节分别为joint1~joint5。使用了一个Mesh文件来美化模型。
## 运行
### 准备环境
- ROS Melodic
- Gazebo
- RViz
- ros-melodic-effort-controllers
  - 可使用 `sudo apt-get install ros-melodic-effort-controllers` 安装
### 运行方式
1. 克隆仓库
2. 在仓库根文件夹运行 `catkin_make` 来初始化 ROS 项目
3. 然后，执行 `source ./devel/setup.bash` 来配置终端
4. 执行 `roslaunch mrm_description rviz.launch` 可在 RViz 中查看机器人，可在 RViz 中加载 `mrm_description/launch/config.rviz` 配置或自定义配置；同时会打开 `Publisher` 窗口调参
5. 执行 `roslaunch mrm_description spawn.launch` 可在 Gazebo 中运行模拟；同时会打开 `Publisher` 和 `Configure` 窗口调参
## 小组成员
- 胡杨
- 贺龙柱
## 参考资料
[The Construct 教程](https://www.theconstructsim.com/my-robotic-manipulator-1-basic-urdf-rviz/)