## BearPi-HM_Nano 开发

BearPi-HM Nano提供多个案例，案例以A、B、C、D进行不同类别进行分级，方便初学者由浅入深逐步学习。您拿到工程后经过简单的编程和下载即可看到实验现象。下面依次对A/B/C/D类进行介绍：

* `A1 - A99`：内核类
* `B1 - B99`：基础外设类
* `C1 - C99`：E53传感器类
* `D1 - D99`：物联网类
* `Z1 - Z99`：开发者贡献

例程列表如下所示：

| 编号 | 类别   | 例程名           | 说明                                                         |
| ---- | ------ | ---------------- | ------------------------------------------------------------ |
| A1   | 内核   | thread           |   [任务交替打印](/applications/BearPi/BearPi-HM_Nano/sample/A1_kernal_thread/README.md)  |
| A2   | 内核   | timer            |  [定时器  ](/applications/BearPi/BearPi-HM_Nano/sample/A2_kernel_timer/README.md)                                                      |
| A3   | 内核   | event            |   [事件](/applications/BearPi/BearPi-HM_Nano/sample/A3_kernel_event/README.md)|
| A4   | 内核   | mutex            |   [互斥锁](/applications/BearPi/BearPi-HM_Nano/sample/A4_kernel_mutex/README.md)|
| A5   | 内核   | semp             |   [信号量](/applications/BearPi/BearPi-HM_Nano/sample/A5_kernel_semaphore/README.md)|
| A6   | 内核   | message           |    [消息队列](/applications/BearPi/BearPi-HM_Nano/sample/A6_kernel_message/README.md)|
| B1   | 基础   | led_blink        |   [红色 LED 不间断烁](/applications/BearPi/BearPi-HM_Nano/sample/B1_basic_led_blink/README.md)|
| B2   | 基础   | button           |   [按键控制LED灯亮灭](/applications/BearPi/BearPi-HM_Nano/sample/B2_basic_button/README.md)|
| B3   | 基础   | pwm_led          |   [红色 LED 呼吸灯](/applications/BearPi/BearPi-HM_Nano/sample/B3_basic_pwm_led/README.md)|
| B4   | 基础   | adc_mq2          |   [ADC读取电压](/applications/BearPi/BearPi-HM_Nano/sample/B4_basic_adc/README.md)|
| B5   | 基础   | i2c_bh1750       |   [I2C读取NFC标签](/applications/BearPi/BearPi-HM_Nano/sample/B5_basic_i2c_nfc/README.md)|
| B6   | 基础   | basic_uart       |   [UART自发自收](/applications/BearPi/BearPi-HM_Nano/sample/B6_basic_uart/README.md)|
| C1   | E53传感器   | e53_sf1_example        |       [驱动烟雾传感器 MQ2](/applications/BearPi/BearPi-HM_Nano/sample/C1_e53_sf1_mq2/README.md)|
| C2   | E53传感器   | e53_ia1_example              |   [驱动温湿度传感器 SHT30](/applications/BearPi/BearPi-HM_Nano/sample/C2_e53_ia1_temp_humi_pls/README.md)|
| C3   | E53传感器   | e53_sc1_example             |   [驱动光强传感器 BH1750](/applications/BearPi/BearPi-HM_Nano/sample/C3_e53_sc1_pls/README.md)|
| C4   | E53传感器   | e53_sc2_example        |   [驱动 6 轴陀螺仪 MPU6050](/applications/BearPi/BearPi-HM_Nano/sample/C4_e53_sc2_axis/README.md)|
| C5   | E53传感器   | e53_is1_example              |   [驱动人体红外传感器](/applications/BearPi/BearPi-HM_Nano/sample/C5_e53_is1_infrared/README.md)|
| D1   | 物联网 | iot_wifi_ap        |   [Wifi热点创建](/applications/BearPi/BearPi-HM_Nano/sample/D1_iot_wifi_ap/README.md)|
| D2   | 物联网 | iot_wifi_sta_connect    |   [Wifi联网](/applications/BearPi/BearPi-HM_Nano/sample/D2_iot_wifi_sta_connect/README.md)|
| D3   | 物联网 | udp_client       |   [使用 Socket 实现 UDP 客户端](/applications/BearPi/BearPi-HM_Nano/sample/D3_iot_udp_client/README.md)|
| D4   | 物联网 | tcp_server       |   [使用 Socket 实现 TCP 服务端](/applications/BearPi/BearPi-HM_Nano/sample/D4_iot_tcp_server/README.md)|
| D5   | 物联网 | iot_mqtt             |   [使用 Paho-MQTT 软件包实现 MQTT 协议通信](/applications/BearPi/BearPi-HM_Nano/sample/D5_iot_mqtt/README.md)|
| D6   | 物联网 | iot_cloud_oc_sample     |  [接入华为IoT 云平台](/applications/BearPi/BearPi-HM_Nano/sample/D6_iot_cloud_oc/README.md)|
| D7   | 物联网 | iot_cloud_onenet_sample         |   [接入中国移动 OneNET 云平台](/applications/BearPi/BearPi-HM_Nano/sample/D7_iot_cloud_onenet/README.md)|
| D8   | 物联网 | iot_cloud_oc_smoke         |   [基于华为IoT平台的智慧烟感案例](/applications/BearPi/BearPi-HM_Nano/sample/D8_iot_cloud_oc_smoke/README.md)|
| D9   | 物联网 | iot_cloud_oc_light         |   [基于华为IoT平台的智慧路灯案例](/applications/BearPi/BearPi-HM_Nano/sample/D9_iot_cloud_oc_light/README.md)|
| D10   | 物联网 | iot_cloud_oc_manhole_cover         |   [基于华为IoT平台的智慧井盖案例](/applications/BearPi/BearPi-HM_Nano/sample/D10_iot_cloud_oc_manhole_cover/README.md)|
| D11   | 物联网 | iot_cloud_oc_infrared         |   [基于华为IoT平台的智慧人体感应案例](/applications/BearPi/BearPi-HM_Nano/sample/D11_iot_cloud_oc_infrared/README.md)|
| D12   | 物联网 | iot_cloud_oc_agriculture         |   [基于华为IoT平台的智慧农业案例](/applications/BearPi/BearPi-HM_Nano/sample/D12_iot_cloud_oc_agriculture/README.md)|
| D13   | 物联网 | iot_cloud_oc_gps         |   [基于华为IoT平台的智慧物流案例](/applications/BearPi/BearPi-HM_Nano/sample/D13_iot_cloud_oc_gps/README.md)|
| Z1   | 开发者贡献例程 | hi3861_uart         |   [Hi3861串口收发（带超时功能）@游乐场](/applications/BearPi/BearPi-HM_Nano/sample/Z1_hi3861_uart_ylc/README.md)|
| Z2   | 开发者贡献例程 | hi3861_flash         |   [Hi3861内部Flash读写 @游乐场](/applications/BearPi/BearPi-HM_Nano/sample/Z2_hi3861_flash_ylc/README.md)|
||||


## 五、源码目录简介

小熊派的源码目录延续OpenHarmony官方目录结构，以下是源码目录的说明：

<a name="table3815144702820"></a>
<table><thead align="left"><tr id="row198162047192810"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p690319291299"><a name="p690319291299"></a><a name="p690319291299"></a>目录名</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p5903122962918"><a name="p5903122962918"></a><a name="p5903122962918"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1981674719280"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p69031429162912"><a name="p69031429162912"></a><a name="p69031429162912"></a>applications</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p090352912914"><a name="p090352912914"></a><a name="p090352912914"></a>BearPi-HM_Nano应用程序样例</p>
</td>
</tr>
<tr id="row5816747132817"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p99031129112918"><a name="p99031129112918"></a><a name="p99031129112918"></a>base</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p790472962914"><a name="p790472962914"></a><a name="p790472962914"></a>基础软件服务子系统集&amp;硬件服务子系统集</p>
</td>
</tr>
<tr id="row1134218692910"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p4904112910295"><a name="p4904112910295"></a><a name="p4904112910295"></a>build</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1090482942911"><a name="p1090482942911"></a><a name="p1090482942911"></a>组件化编译、构建和配置脚本</p>
</td>
</tr>
<tr id="row1841618902919"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p1390462902910"><a name="p1390462902910"></a><a name="p1390462902910"></a>domains</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1390432914296"><a name="p1390432914296"></a><a name="p1390432914296"></a>增强软件服务子系统集</p>
</td>
</tr>
<tr id="row841620912298"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p119041629182919"><a name="p119041629182919"></a><a name="p119041629182919"></a>drivers</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p9904629132911"><a name="p9904629132911"></a><a name="p9904629132911"></a>驱动子系统</p>
</td>
</tr>
<tr id="row164164992915"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p79042298298"><a name="p79042298298"></a><a name="p79042298298"></a>foundation</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p18904132922915"><a name="p18904132922915"></a><a name="p18904132922915"></a>系统基础能力子系统集</p>
</td>
</tr>
<tr id="row1441610922915"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p490402916299"><a name="p490402916299"></a><a name="p490402916299"></a>kernel</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1904112932912"><a name="p1904112932912"></a><a name="p1904112932912"></a>内核子系统</p>
</td>
</tr>
<tr id="row194175972917"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p1904132912910"><a name="p1904132912910"></a><a name="p1904132912910"></a>prebuilts</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p390492919296"><a name="p390492919296"></a><a name="p390492919296"></a>编译器及工具链子系统</p>
</td>
</tr>
<tr id="row841718942913"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p12904929202919"><a name="p12904929202919"></a><a name="p12904929202919"></a>test</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p4904152912297"><a name="p4904152912297"></a><a name="p4904152912297"></a>测试子系统</p>
</td>
</tr>
<tr id="row24175915294"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p13904162992916"><a name="p13904162992916"></a><a name="p13904162992916"></a>third_party</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p6904829112917"><a name="p6904829112917"></a><a name="p6904829112917"></a>开源第三方组件</p>
</td>
</tr>
<tr id="row334210652914"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p1390442918299"><a name="p1390442918299"></a><a name="p1390442918299"></a>utils</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p690412296297"><a name="p690412296297"></a><a name="p690412296297"></a>常用的工具集</p>
</td>
</tr>
<tr id="row73421664298"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p7905172920292"><a name="p7905172920292"></a><a name="p7905172920292"></a>vendor</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p290510290293"><a name="p290510290293"></a><a name="p290510290293"></a>厂商提供的软件</p>
</td>
</tr>
<tr id="row734319617292"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p09056291290"><a name="p09056291290"></a><a name="p09056291290"></a>build.py</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1790542912290"><a name="p1790542912290"></a><a name="p1790542912290"></a>编译脚本文件</p>
</td>
</tr>
</tbody>
</table>

## 六、开发板图片预览[（淘宝链接）](https://item.taobao.com/item.htm?id=633296694816)

[![](/applications/BearPi/BearPi-HM_Nano/docs/figures/00_public/BearPi-HM_Nano_Info.png)](https://item.taobao.com/item.htm?id=633296694816)


## 七、联系我们



![](/applications/BearPi/BearPi-HM_Nano/docs/figures/00_public/bearpi_club_wechat.jpg)