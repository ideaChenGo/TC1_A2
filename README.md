# TC1_A2
斐讯TC1智能排插私人固件，在学校无聊搞了一下，移植于A1版(https://github.com/a2633063/zTC1)

此版本使用的是汉枫的LPT-230wifi模块

> 固件基于官方SDK进行的二次开发
## 使用方法

### 1.接线：

把第10号引脚（复位引脚）接跟线出来，串口接第5（tx）和第6引脚(rx)，电源供电引线最好接5V（测试点）

通过串口工具连接到电脑，打开secureCRT软件，设置参数230400,8,none,1 ，连接上模块。


### 2.烧录固件

按住板上的按键，另一只手把复位引线碰一下GND(测试点)，接着在1秒内按电脑上的空格键（鼠标光标要在接收窗口上）。

看到有打印出Bootloader的信息，接着按照输入‘S’，再输入‘Y’,  点击菜单栏的"发送"(Transfer)，选择“发送Xmodem”，然后就选择XXX_gcc.bin文件，打开。

等待传输完成即可。

