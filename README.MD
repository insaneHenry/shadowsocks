#原福利社或fireSs加速器全套源码
 ##安装步骤（前台+后台）
    1.下载ss-panel-v3-mod.sh 到linux目录
    2.给到ss-panel-v3-mod.sh 权限 chmod 777 ss-panel-v3-mod.sh 即可
    3. ./ss-panel-v3-mod.sh 运行 ，根据提示操作
    4.注意 如遇到download zip 包从github下载失败问题，可以手动rz上传,并去除脚本中响应的wget位置即可
    5.相应资源从github，91vps获取，有mrchang整理
 ##Google BBR 加速 
    1.下载 bbr.sh 到linux 目录
    2.给到 bbr.sh 权限
    3. ./bbr.sh 即可
    4.系统支持：CentOS 6+，Debian 7+，Ubuntu 12+
    5.虚拟技术：OpenVZ 以外的，比如 KVM、Xen、VMware 等
    6.内存要求：≥128M
    7.安装完成后 uname -r 查看系统内核
    8.含有 4.12 就表示 OK 了 sysctl net.ipv4.tcp_available_congestion_control 