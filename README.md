# RT-Thread

此项目为参照RT-Thread官方文档完成的桌面mini时钟的源码，方案为:ESP8266+OLED+DHT11+正点原子探索者STM32F407ZGT6

接线为：
ESP8266 TXD PA3
ESP8266 RXD PA2
OLED SCL PB6
OLED SDA PB7
DHT11 OUT PG9

需要注意：目前此代码烧录进去之后，需要在终端窗口输入msh命令 oled_display才会开始循环显示，等后期熟悉了RT-Thread的指令后再实现上电自动循环显示

# 参考资料
https://blog.csdn.net/m0_53488817/article/details/118461208
