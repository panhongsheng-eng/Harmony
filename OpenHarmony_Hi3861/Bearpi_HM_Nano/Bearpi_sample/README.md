BearPi-HM_Nano案例开发
BearPi-HM_Nano 提供的例程多达 30个，每个例程都有非常详细的注释，代码风格统一，按照基本例程到高级例程的方式编排，方便初学者由浅入深逐步学习。开发者拿到工程后经过简单的编译和下载即可看到实验现象。

这些例程包括四个类别：内核类、基本外设类、驱动类、物联网类。不仅包括了硬件资源的应用，更是提供了丰富的物联网领域的应用示例，帮助物联网开发者更好更快地进行开发。

例程列表如下所示：

编号	类别	例程名	说明
A1	内核	thread	任务交替打印
A2	内核	timer	定时器
A3	内核	event	事件
A4	内核	mutex	互斥锁
A5	内核	semp	信号量
A6	内核	message	消息队列
B1	基础	led_blink	红色 LED 不间断烁
B2	基础	button	按键控制LED灯亮灭
B3	基础	pwm_led	红色 LED 呼吸灯
B4	基础	adc_mq2	ADC读取电压
B5	基础	i2c_bh1750	I2C读取NFC标签
B6	基础	basic_uart	UART自发自收
C1	E53传感器	e53_sf1_example	驱动烟雾传感器 MQ2
C2	E53传感器	e53_ia1_example	驱动温湿度传感器 SHT30
C3	E53传感器	e53_sc1_example	驱动光强传感器 BH1750
C4	E53传感器	e53_sc2_example	驱动 6 轴陀螺仪 MPU6050
C5	E53传感器	e53_is1_example	驱动人体红外传感器
D1	物联网	iot_wifi_ap	Wifi热点创建
D2	物联网	iot_wifi_sta_connect	Wifi联网
D3	物联网	udp_client	使用 Socket 实现 UDP 客户端
D4	物联网	tcp_server	使用 Socket 实现 TCP 服务端
D5	物联网	iot_mqtt	使用 Paho-MQTT 软件包实现 MQTT 协议通信
D6	物联网	iot_cloud_oc_sample	接入华为IoT 云平台
D7	物联网	iot_cloud_onenet_sample	接入中国移动 OneNET 云平台
D8	物联网	iot_cloud_oc_smoke	基于华为IoT平台的智慧烟感案例
D9	物联网	iot_cloud_oc_light	基于华为IoT平台的智慧路灯案例
D10	物联网	iot_cloud_oc_manhole_cover	基于华为IoT平台的智慧井盖案例
D11	物联网	iot_cloud_oc_infrared	基于华为IoT平台的智慧人体感应案例
D12	物联网	iot_cloud_oc_agriculture	基于华为IoT平台的智慧农业案例
D13	物联网	iot_cloud_oc_gps	基于华为IoT平台的智慧物流案例
Z1	开发者贡献例程	hi3861_uart	Hi3861串口收发（带超时功能）@游乐场
Z2	开发者贡献例程	hi3861_flash	Hi3861内部Flash读写 @游乐场
