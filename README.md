# Hackintosh_Asus-UX501JW_Mojave
-------------------------------------
配置清单

CPU：intel i7-4720HQ

内存：4+8GB

硬盘：128GB SSD + 512GB SSD

显卡：Nvidia GTX960M 4GB / intel HD4600

声卡：瑞昱Realtek @ Intel Lynx Point 

网卡：intel Dual band wireless-AC 7260

--------------------------------------

已驱动
 
核心显卡intel HD4600 (已修改AppleIntelFramebufferAzul.kext的显存为你2GB）

声卡

有线网卡

摄像头

触摸板

蓝牙

电池

--------------------------------------
未驱动

无线网卡

--------------------------------------
未测试

读卡器

--------------------------------------
存在的问题

Clover引导界面需要选择config_HD4600_4400_4200.plist配置文件启动。

如果将该配置文件改成默认，可能无法启动。
