# Remote Temperature Control System

#### 介绍
课程设计



#### 进度说明：

- 2020-12-4 完成sch设计，完成PCB封装绘制。
- 2020-12-5 sch-v1.1版改动说明：
  1.增加51单片机pin引出
  2.增加对ESP8266-01s的兼容，增加ESPx的烧录模式支持，增加ESPx复位电路
  3.增加去耦电容
  4.原理图美化
- 2020-12-5 v1.2版改动说明：
  1.增加蜂鸣器、sys_LED和两个外部中断按键
  2.优化ESP部分的电路结构
- 2020-12-5 完成v1.2原理图版本的PCB绘制
- 2020-12-9 完成焊接测试，整体功能正常。新发现的问题：1、LCD对比度使用了固定电阻，调试复杂，已飞线可调电阻器解决。2、继电器负载默认连接至常闭引脚。（在此项目中影响不大，非致命问题，若重新投板则更改）