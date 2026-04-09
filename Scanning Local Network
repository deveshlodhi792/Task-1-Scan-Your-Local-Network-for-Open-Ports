<h1>Scanning Local Network using Nmap</h1>
+ To know our IP address and subnet mask - "ifconfig".
+ I found my IP address was 192.168.29.194.
+ Then I scan my network using command "nmap -sS 192.168.29.0/24".
+ This command gave me alive IP addresses and Open Ports on my network.

<h2>Scan report</h2>
+ Nmap scan report for (192.168.29.1)
Host is up (0.0081s latency).
Not shown: 990 filtered tcp ports (no-response)
PORT     STATE  SERVICE
53/tcp   open   domain
80/tcp   open   http
443/tcp  open   https
1900/tcp open   
2869/tcp closed icslap
7443/tcp open   oracleas-https
8002/tcp closed teradataordbms
8080/tcp open   http-proxy
8200/tcp closed trivnet1
8443/tcp open   https-alt

Nmap scan report for 192.168.29.24
Host is up (0.013s latency).
Not shown: 998 closed tcp ports (reset)
PORT    STATE SERVICE
80/tcp  open  http
554/tcp open  rtsp

Nmap scan report for 192.168.29.194
Host is up (0.000014s latency).
Not shown: 999 closed tcp ports (reset)
PORT     STATE SERVICE
3389/tcp open  ms-wbt-server

XXXEndXXX

+ The IP address 192.168.29.1 had these tcp ports open:
  -  Port 53
  -  Port 80
  -  Port 443
  -  Port 1900
  -  Port 7443
  -  Port 8080
  -  Port 8443

+ IP Address 192.168.29.24 had these tcp ports open:
  - Port 80
  - Port 554
 
+ My device with IP 192.168.29.194 had only this 3389 tcp Port open.
