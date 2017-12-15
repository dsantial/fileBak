192.241.223.150

nohup sslocal -c /etc/shadowsocks.json  </dev/null 2>&1 &

systemctl start privoxy

ps aux |grep sslocal |grep -v "grep"
