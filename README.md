# weijia
lastlog
//查看被攻击的IP次数
netstat -ntu | awk '{print $5}' | cut -d: -f1 | sort | uniq -c | sort -n

