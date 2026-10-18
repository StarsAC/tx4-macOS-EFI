# 华硕天选4锐龙版 macOS 黑苹果 EFI
## 机型配置：
- MODEL: FA507XV
- CPU: AMD Ryzen 9 7409H with Radeon 780M Graphics
- Mem: 24GB DDR5 4800MHz
- GPU: NVIDIA GeForce RTX 4060 Laptop 8 GB
- Disk: Seagate ZP1000GV30012
- Ethernet: Realtek RTL8168H/8111H PCI Express Gigabit Ethernet
- Wi-Fi/Bluetooth: Realtek MT7921（未驱动，可自行更换为AX210）

## Files：
提供两个版本EFI，分别适配macOS Sequoia 15.8.1 和 macOS Tahoe 26.7.1，根据系统版本进行选择

## Notice：
- 本EFI由1401生成版本经过多轮修改而来，仅针对上述配置进行了实际验证，不保证其他型号硬件可用
- 安装前务必前往奥创中心（Armoury Create）将显卡模式切换为独显直连
- 首次安装时请使用WithoutNvidiaDriver相关选项，避免显卡驱动导致的安装失败
- 安装后可关闭调试、修改三码方可正常使用

## Working：
- 耳机
- 扬声器
- 麦克风
- DP视频输出
- 键盘
- 触摸板
- 键盘上方快捷键
- USB
- 摄像头
- 休眠和唤醒
- 充电状态

## Not Working：
- Wi—Fi/Bluetooth（需要更换网卡，联发科网卡驱动仍在完善中）
- DP热插拔（切换显示器需要重启电脑）
- 部分图形加速场景仍有问题（需要等待NullMoth显卡驱动更新）
- Virtualization（AMD 平台无解，Docker 等需要虚拟 linux 的软件不可用）

## Links(Docs/Helpers/Tools)：
- [OpenCore Official Docs](https://github.com/acidanthera/OpenCorePkg/releases)
- [OpenCore Configurator Official](https://mackie100projects.altervista.org/opencore-configurator/)
- [Hackintool](https://github.com/benbaker76/Hackintool/releases)
- [1401 Project/NV Driver](https://nullmothsystems.com/)
- [Codex/ChatGPT Intel mac version](https://chatgpt.com/codex/)

## Thanks:
- Hackintosh community
- CNIC
- ChatGPT 6 Astra / ChatGPT desktop



