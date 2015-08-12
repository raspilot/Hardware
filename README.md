#树莓派飞控RasPilot#

###RasPilot硬件参数###
特性
* 支持树莓派1 A+/B+；树莓派2 B+
* STM32F103 failsafe co-processor
* ardupilot飞控代码
* pixhawk接口兼容
* USB(RPi) / Servo Rail BEC / Power Module三路电源输入

传感器
* ST Micro L3GD20H 16位陀螺仪
* ST Micro LSM303D 14位加速度计/磁力计
* Invensense MPU 6000 3轴陀螺仪/加速度计
* MEAS MS5611 气压计

接口
* 2x UART
* 1x CAN
* 8x PWM
* Spektrum DSM / DSM2 / DSM-X® Satellite 兼容接收机
* Futaba S.BUS® 兼容输入输出
* PPM sum 接收机
* RSSI（PWM或电压）输入
* 1x I2C
* 3.3V & 6.6V A/D输入
* 安全开关
* 蜂鸣器接口
* 板载三色LED

###硬件安装和接线###
1 安装外壳。如下图，用铜柱和螺母将树莓派固定在底壳上。插上飞控扩展板，再用螺丝固定上壳。<br>
![](https://github.com/raspilot/docs/blob/master/raspilot_p1.jpg)
![](https://github.com/raspilot/docs/blob/master/raspilot_p2.jpg)<br>
<br>
2 接口说明：<br>
![](https://github.com/raspilot/docs/blob/master/connectors.jpg)<br>
