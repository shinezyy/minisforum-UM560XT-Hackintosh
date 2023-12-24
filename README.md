# minisforum-UM560XT-Hackintosh
minisforum UM560XT Hackintosh

## 电脑配置

|   规格    |                           详细信息                           |
| :-------: | :----------------------------------------------------------: |
| 电脑型号  |                      minisforum UM560XT                      |
| 操作系统  | macOS `Sonoma` / `Ventura` /  `Monterey`  |
|  处理器   |                 AMD 锐龙 R5-5600H 6核12线程                  |
|   内存    |                      64 GB DDR4 3200MHz                      |
|   硬盘1   |                幻隐 HV2000p 2T               |
|   硬盘2   |                  WD blue 3d SATA 1T                   |
|   核显    |      Radeon Vega Graphics<br />显存：8GB       |
|  显示器   |                              无                              |
|   声卡    |                       USB Audio Device                       |
| 无线网卡  | m.2 NGFF插槽，默认出厂为 `Mediatek RZ608` 已更换为 IntelAX200 |
| 有线网卡1 |               Intel Ethernet Controller I225-V               |

# 更新记录
- 12-23-2023
  - Bump AppleALC to fix ryzen
- 12-17-2023
  - Support AX200's WiFi and Bluetooth
  - Support Android's Internet sharing via USB [HoRNDIS](https://github.com/jwise/HoRNDIS)

- 12-13-2023

  - 更新 `OpenCore` 到 `v0.9.6`
  - 提供对 `Sonoma` 的支持
  - 博通网卡请打 [OCLP补丁](https://blog.daliansky.net/OCLP.html)
  
- 9-7-2023

  - 修复声卡驱动，支持麦克风输入

  
