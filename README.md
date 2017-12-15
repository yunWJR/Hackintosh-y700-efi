# Hackintosh-lenovo-y700-efi
Deskmini-efi for Hackintosh
> `Now available for 10.12.6、10.13.1`

# 1. 主机配置
* lenovo-y700
* I5 6300Hq
* HD630核显（CPU自带）
* BCM94352Z（淘宝买的，当前使用）
* 8G 2133 DDR4 金士顿笔记本内存

# 2. BIOS设置
* Vt-d 关闭
* 安全启动模式 关闭

# 3. Clover信息
clover：r4318
## 正常功能：
* CPU 变频正常
* BCM94352Z 正常
* 声卡-AppleALC原生驱动
* USB正常

## 待解决：
* 睡眠
* 关机、重启

# 更新记录
2017-12.15

1. 更新 clover
2. 更新 kext（lilu-1.2.1，以及相关 kext）
3. 升级到10.13.2