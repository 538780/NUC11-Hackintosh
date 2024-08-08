# NUC11
## 适用于 NUC11BTMi7, MacOS Sonoma，Ventura，
# 配置信息
- 计算卡：NUC11BTMI7 i7-11700B
- 有线网卡：i225-LM
- 无线网卡：AX210-6E
- 声卡：机箱前面板USB声卡
- 显卡：惠普 6600 XT
- 内存：联想 DDR4 16G 3200MHz*2
- 硬盘：西数  512GB
### BIOS 设置

- Advanced
  - Advanced > `PCIE Resizable BAR Support: Disabled`
  - Advanced > Video > `Primary Display: PEG Slot`
  - Advanced > Video > `Internal graphics > Auto or Disabled`
- Security
  - Security Features > `Intel VT for Directed I/O(VT-d)：Disabled`
- Boot
  - Secure Boot > `Secure Boot: Disabled`
  - boot Priority > `Fast Boot: Unchecked`
