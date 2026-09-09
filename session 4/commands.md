piyush@piyush-LOQ-15IAX9:~$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: enp7s0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc fq_codel state DOWN group default qlen 1000
    link/ether 40:c2:ba:51:e4:0c brd ff:ff:ff:ff:ff:ff
    altname enx40c2ba51e40c
3: wlp8s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether c0:35:32:18:73:cd brd ff:ff:ff:ff:ff:ff
    altname wlxc035321873cd
    inet 192.168.6.164/19 brd 192.168.31.255 scope global dynamic noprefixroute wlp8s0
       valid_lft 20755sec preferred_lft 20755sec
    inet6 fe80::f64c:828b:6a73:c026/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
