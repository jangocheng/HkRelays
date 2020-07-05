# HkRelays
支持Modbus的继电器改装方案，支持homekit、modbus、mqtt适配homeassistant、iobroker智能平台

![HkRelays](https://github.com/huexpub/HkRelays/blob/master/Png/20200705123129.png?raw=true)

# TODO


- STM32固件无法外接点控问题，目前只能翻转

- WEB设置参数独立，目前与继电器状态同步，会导致还没保存后又复原

- Homekit 单一操作过快会导致死循环


# 声明
DIY有风险，该版本STM32贴装芯片较小，测试前请确定焊接到位并使用万用表测试是否有短路，否则烧坏，短路均可能造成永久性损坏及触电炸板事件。

