
## 前言
自用想要更加稳定，因此非必须不会轻易升级相关组件。。。喜欢尝鲜的就别使用该EFI了
下一次更新预计是OC 0.6.4 正式版发布

## Build Info
- OpenCore: 0.6.4
- CPU: AMD Ryzen 7 5800X
- GPU: RX 580 8G
- Motherboard: X570 AORUS PRO WIFI
- RAM: 光威（Gloway）8GB DDR4 3000频率 台式机内存条 弈Pro系列 * 4
- OS: MacOS Big Sur
- HardDrive: 970 EVO PLUS 256G
- Wifi/Bluetooth: Motherboard comes with 

## 功能

- 4K解码 正常
- 蓝牙 正常
- WIFI/有线 正常
- imessage/apple store/hand off 正常
- USB 正常
- 睡眠唤醒 正常
- HiDPI/165HZ：使用一键脚本无效，最后用了Hackintool定制解决
- 音量/显示器亮度调节：使用第三方软件[MonitorControl](https://github.com/MonitorControl/MonitorControl)

## 缺陷

- 系统盘显示为外置盘，加了 'ExternalDiskIcons' 参数仍然无解
- 麦克风未测试，没有该需求，日常使用AUX音箱正常输出

## Notes:

- BIOS: "Above 4G XXX" 关闭 (这里重点，和其他主板不一样，我这里需要关闭，自己在启动参数加0x200才可以)
- BIOS: CMS 关闭
- BIOS: fast boot 关闭
- BIOS: Secure boot 关闭
- OC: 填写你的机器型号 "Platform Info"

## Remark

[OpenCore-Install-Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[AMD-OSX](https://forum.amd-osx.com/index.php)

[GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
