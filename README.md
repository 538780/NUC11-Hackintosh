# NUC11
## 适用于 NUC11BTMi7, MacOS Sonoma，Ventura的Hackintosh-EFI引导
## 配置信息
- 计算卡：NUC11BTMI7 i7-11700B
- 有线网卡：Intel® 以太网控制器 i225-LM
- 无线网络/蓝牙：Intel® Wi-Fi 6E AX210
- 声卡：机箱前面板USB声卡
- 显卡：惠普 6600 XT
- 内存：联想 DDR4 16G 3200MHz*2
- 硬盘：西数  512GB
- MacOS版本：Sonoma 14.5
  
## BIOS 设置
- Advanced
  - Advanced > `PCIE Resizable BAR Support: Disabled`
  - Advanced > Video > `Primary Display: PEG Slot`
  - Advanced > Video > `Internal graphics > Auto or Disabled`
- Security
  - Security Features > `Intel VT for Directed I/O(VT-d)：Disabled`
- Boot
  - Secure Boot > `Secure Boot: Disabled`
  - boot Priority > `Fast Boot: Unchecked`
 
 ## 硬件驱动情况
- ✅ CPU正常睿频
- ❌ 11代CPU核心显卡无法驱动
- ✅ 独立显卡HP 6600xt正常
- ✅ USB接口已经定制，所有USB接口均可正常使用
- ✅ 声卡驱动正常
- ✅ 自带无线网卡WIFI、蓝牙正常
- ✅ 有线网卡驱动正常
- ✅ 读卡器无SD卡测试，但读卡器走的USB3.2Hub，理论上可以使用
- ✅ 无雷电硬件测试
- ✅ 睡眠及唤醒正常

##
### RX6600XT 啸叫
 ✅EFI集成RX6600XT定制降频处理，如有问题，可自行使用OCAT移除PP_PhmSoftPowerPlayTable
 > OCAT-DP-PCILists-下方减号删除


## 更改日志

- 2024 年 8 月 8 日
  - 首次提交
  - 更新`OpenCore` `v1.0.1`
  - 支持`Sonama`安装和使用
## 参考工具
- OCAT: https://github.com/ic005k/OCAuxiliaryTools
- WiFi网卡：https://github.com/OpenIntelWireless/itlwm
- 蓝牙：https://github.com/OpenIntelWireless/IntelBluetoothFirmware


### 参考EFI链接：
- https://github.com/zpyangchina/NUC11BTMi7-hackintosh
- https://github.com/xiao-chenxi/NUC11BTMi9-hackintosh

