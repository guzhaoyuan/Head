#EX106驱动程序
---
使用python的serial进行串口通信，对Dynamixel的EX106进行驱动。
##Usage
---
	python head.py

##Structure
---
- head.py #主程序入口,PID控制电机保持某一姿态
- EX106.py #底层驱动，串口通讯
- pid.py #pid算法实现
- readIMU.py #读取IMU数据并且使用
- home.py #测试文件,用于将电机返回中值

##Dependency
---

- pySerial
- time

##当前完成度
可以使用head.py 读取IMU数据控制EX106保持PID平衡