# n1 coreelec更新（保留配置）
## 开启系统，ssh连接，执行下面的命令
mount -o remount,rw /flash
## 将新版固件写入u盘，并拷贝以下四个文件到N1
1. dtb.img
2. SYSTEM
3. kernel.img
4. ulnitrd
## 重启即可
