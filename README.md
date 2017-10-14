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
