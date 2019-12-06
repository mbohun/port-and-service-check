#### simple verification of port status (nmap)
```
linux-lrp0:/home/mbohun # nmap -P0 mbohun.github.io
Starting Nmap 7.80 ( https://nmap.org ) at 2019-12-06 14:07 AEDT
Nmap scan report for mbohun.github.io (185.199.109.153)
Host is up (0.068s latency).
Other addresses for mbohun.github.io (not scanned): 185.199.111.153 185.199.110.153 185.199.108.153
Not shown: 995 filtered ports
PORT     STATE SERVICE
21/tcp   open  ftp
80/tcp   open  http
443/tcp  open  https
554/tcp  open  rtsp
1723/tcp open  pptp

Nmap done: 1 IP address (1 host up) scanned in 19.54 seconds
```
