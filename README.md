# HUANANZHI-B85-ITX-Hackintosh

华南金牌B85itx黑苹果EFI引导，适用于MacOS Monterey

## 配置列表
* CPU：i7-4790
* 显卡：核显方案 HD4600
* 主板：华南金牌 B85-itx
* 内存：8Gx2
* 硬盘：华南金牌 Nvme 128G

## 运行情况
* 显示：4k下测试
  * DP接口：有3840x2160、1920x1080(HIDPI)、1780x720(HIDPI)、960x540(HIDPI)几个档位（均为60hz）
  * HDMI接口：可以4K但是只能30hz（HD4600 HDMI输出的极限了）
  * VGA：未测试
* 声音：测试OK，支持前面板+后面板
* 网络：Intel AX210 WIFI6E + 有线双口
* USB：2xUSB3.0、4xUSB2.0
* 蓝牙：Monterey下暂时还有问题，等驱动更新，BigSur没问题

## 系统环境

* MacOS Monterey 12.2.1
* 主板BIOS
  * 关闭CFG Lock
  * 关闭CSM
  * 帧缓冲最好别改64M，卡出翔，但是32M下会导致4k显示不完整（读条阶段，进系统之后没问题）
