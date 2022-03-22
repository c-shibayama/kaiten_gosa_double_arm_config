配置
~/ws_moveit/src/kaiten_gosa_double_arm_config
実行コマンド
$ roslaunch kaiten_gosa_double_arm_config demo.launch

(
Install ROS and Catkin
 Once you have ROS installed, make sure you have the most up to date packages:
  $ rosdep update
  $ sudo apt-get update
  $ sudo apt-get dist-upgrade
 Install catkin the ROS build system:
  $ sudo apt-get install ros-melodic-catkin python-catkin-tools
Install MoveIt
 $ sudo apt install ros-melodic-moveit
)

~/ws_moveit/src は以下のサイトを参考に生成
http://docs.ros.org/en/melodic/api/moveit_tutorials/html/doc/getting_started/getting_started.html