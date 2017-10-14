#

linux常用一键安装脚本

一键安装BBR

wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh

chmod +x bbr.sh

./bbr.sh


uname -r

查看内核版本，含有 4.13 就表示 OK 了

lsmod | grep bbr

返回值有 tcp_bbr 模块即说明bbr已启动。


客户端一键安装酸酸乳命令：

wget -N --no-check-certificate https://raw.githubusercontent.com/mmmwhy/ss-panel-and-ss-py-mu/master/ss-panel-v3-mod.sh && chmod +x ss-panel-v3-mod.sh && bash ss-panel-v3-mod.sh



