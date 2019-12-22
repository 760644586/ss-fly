git clone -b master https://github.com/760644586/ss-fly

vim /etc/shadowsocks.json

ss-fly/ss-fly.sh -i QQQ@www@@ 80

ss-fly/ss-fly.sh -bbr

sysctl net.ipv4.tcp_available_congestion_control

停止ss服务：ssserver -c /etc/shadowsocks.json -d stop

启动ss服务：ssserver -c /etc/shadowsocks.json -d start

重启ss服务：ssserver -c /etc/shadowsocks.json -d restart
