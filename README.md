# HkRelays
支持Modbus的继电器改装方案，支持homekit、modbus、mqtt适配homeassistant、iobroker智能平台

![HkRelays](https://github.com/huexpub/HkRelays/blob/master/Png/20200705123129.png?raw=true)

# TODO


- STM32固件无法外接点控问题，目前只能翻转

- WEB设置参数独立，目前与继电器状态同步，会导致还没保存后又复原

- Homekit 单一操作过快会导致死循环


# 声明
DIY有风险，该版本STM32贴装芯片较小，测试前请确定焊接到位并使用万用表测试是否有短路，否则烧坏，短路均可能造成永久性损坏及触电炸板事件。


# 刷机

![FLASH](https://github.com/huexpub/HkRelays/blob/master/Png/20200705142328.png?raw=true)

> STM32烧写

需要使用ST-LINK或者J-Link工具烧写，具体方法请百度即可

> ESP32烧写

项目中已经有FLASH_TOOL文件夹，该部分为ESP32烧写工具，固件仅为v1.0，后期你可以替换后烧录或者烧录完成后配网OTA升级