欢迎访问 W600 文档中心
==========================================

`本文档 <https://docs.thingsturn.com>`_ 主要由 `星通智联 <https://www.thingsturn.com>`_ 进行维护，您可以通过 `GitHub <https://github.com/w600/docs>`_ 进行协助编辑。

.. important::
    初次上手，强烈建议您优先阅读  `W600_AT开发入门指导 <at/start>`__ 、   `W600_SDK开发入门指导 <sdk/start>`__ 和 `W600 常见问题 <faq>`__

W600系列产品，是深圳市星通智联科技有限公司开发的一系列基于联盛德W600的UART-WiFi模块，该系列模块支持标准的 802.11 b/g/n 协议，内置完整的 TCP/IP 协议栈。

W600_SoC芯片集成 Cortex-M3 内核，内置 Flash，集成射频收发前端 RF Transceiver，CMOS PA 功率放
大器，基带处理器/媒体访问控制，支持 SDIO、SPI、UART、GPIO、I²C、PWM、I²S、7816 等接口, 支持
多种加解密协议，如 PRNG(Pseudo random Number Generator)/ SHA1/ MD5/ RC4/ DES/ 3DES/
AES/ CRC 等。

W600是一款支持多接口、多协议的无线局域网 IEEE802.11n（1T1R）的 SoC 芯片。适用于智能家
电、智能家居、无线音视频、智能玩具、医疗监护、工业控制等物联网应用领域。
	
W600 特性
==========
1. 内置 288KB SRAM，用户可用RAM超过160KB；
2. 内置 1MB Flash，用户固件大小可达450KB；
3. 支持SWD调试（近期会出教程）；
4. 支持HT40，WiFi速率最高150Mbps；
5. 集成1个高速SPI设备控制器，工作时钟范围0~50MHz；
6. 集成1个I2C控制器，支持100/400Kbps速率；
7. 2个完整UART接口，波特率范围1200bps~2Mbps；
8. 集成双工I²S控制器，支持32KHz~192KHz 编解码；
9. 集成PWM控制器，支持5路PWM输出或2路PWM输入；
10. 集成7816接口，支持EVM2000规范，并兼容串口功能。
11. 集成通用加密硬件加速器，支持PRNG/ SHA1/ MD5/ RC4/ DES/ 3DES/ AES/ CRC等多种加解密协议；
12. 除 wlan.lib 外，其它资源完全开放；
13. 使用 keil 开发环境;
14. 支持 gcc 开发。

选型表
=========
+--------+---------------+---------------+---------------+
|  型号  |     TW-01     |     TW-02     |     TW-03     |
+========+===============+===============+===============+
|  封装  |     DIP-8     |    SMD-22     |    DIP-22     |
+--------+---------------+---------------+---------------+
|  天线  |    PCB天线    |    PCB天线    |    PCB天线    |
+--------+---------------+---------------+---------------+
|  尺寸  |18*17*2.8±0.2mm|15*17.3*3±0.2mm| 24*16*3±0.2mm |
+--------+---------------+---------------+---------------+
|  板层  |       2       |       2       |       2       |
+--------+---------------+---------------+---------------+

.. image:: index.assets/tw_01.png
   :width: 300px

TW-01，兼容ESP-01，8Pin直插

.. image:: index.assets/tw_02.png
   :width: 300px

TW-02，兼容E2S，11Pin 金手指

.. image:: index.assets/tw_03.png
   :width: 300px

TW-03，兼容ESP-12F，22Pin 邮票孔

.. image:: index.assets/tb_01.png
   :width: 300px

TB-01，全IO引出，支持一键下载

联系我们
==========

深圳市星通智联科技有限公司

论坛：http://w600.fun

邮箱：support@thingsturn.com

官网：http://www.thingsturn.com

淘宝：http://shop.thingsturn.com


地址: 深圳市宝安区固戍二路鸿宇商务大厦1118

.. toctree::
   :hidden:

   at/index
   soc/index
   api/index
   third_party/index
   product/index
   download/index
   faq/index