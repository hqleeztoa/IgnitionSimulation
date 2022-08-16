#### 相关依赖
-   环境依赖
电脑环境： Linux （推荐使用ubuntu22.04 64bit）

sudo ubuntu-drivers devices
sudo ubuntu-drivers autoinstall

安装ROS2 Humble (https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)
sudo apt install python3-pip
sudo pip3 install rosdepc
sudo rosdepc init & rosdepc update
sudo apt install python3-colcon-ros
sudo apt install python3-colcon-common-extensions

安装Ignition  (https://gazebosim.org/docs/fortress/install_ubuntu)
sudo apt install ros-humble-ros-ign  (https://github.com/gazebosim/ros_gz/tree/ros2#from-source)
sudo apt install ~nros-humble-rqt*
sudo apt install collada-urdf-tools
sudo apt install meshlab
sudo apt install ros-humble-gazebo-*
sudo apt install ros-humble-xacro
sudo apt install ros-humble-turtle-tf2-py ros-humble-tf2-tools
sudo pip3 install transforms3d
sudo apt install python3-opencv
sudo pip3 install --upgrade setuptools 
sudo apt install ros-humble-usb-can
sudo apt install python3-tk python3-pip 
pip3 install xlwt
pip3 install matplotlib
pip3 install python-docx
pip3 install mammoth 
sudo apt-get install  python3-openpyxl
sudo apt-get install liburdfdom-tools
sudo apt-get install ros-humble-urdf-*

-   其他依赖
```shell
sudo apt-get install ros-melodic-gazebo-*
以下为自动生成测试报告工具安装:
包括 
1. 日志轨迹生成  
gedit ./.bashrc  添加  alias python='/usr/bin/python3.6'  
sudo apt install python3-tk python3-pip  
安装excel： pip3 install xlwt  
安装图形软件： pip3 install matplotlib  
安装setuptools：   
wget --no-check-certificate  https://pypi.python.org/packages/source/s/setuptools/setuptools-19.6.tar.gz  
tar -zxvf setuptools-19.6.tar.gz  
cd setuptools-19.6  
python3 setup.py build  
sudo python3 setup.py install  
2. word报告生成工具  
安装docx：pip3 install python-docx  
3. word报告转网页工具  
pip3 install mammoth  
4. 生成EXCL报告工具  
sudo apt-get install python-openpyxl python3-openpyxl   
```
# IgnitionSimulation
