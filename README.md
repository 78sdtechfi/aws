## Installation

<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray"></img>
- Commmand :

<img src="https://img.shields.io/badge/Service-Update%20First-green"></img>
 ```html
 apt-get update && apt-get upgrade -y && update-grub && reboot
  ```
 <img src="https://img.shields.io/badge/Install All-VPN%20Batch-green"></img>
 ```html
 wget https://raw.githubusercontent.com/78sdtechfi/aws/main/setup.sh 
 chmod +x setup.sh 
 ./setup.sh
 ```
 <img src="https://img.shields.io/badge/Install%20Only-SSH%2FSSH%20SSL(Stunnel)%20SSH--WS%20Python%20BadVPN--UDPGW-green"></img>
 ```html
 wget https://raw.githubusercontent.com/78sdtechfi/aws/main/install/sshonly.sh
 chmod +x sshonly.sh  
 ./sshonly.sh
 ```
	
	
## Info 
```diff
- PLEASE READ THE SYMBOLIC TEXT ( # )
(to find out what script to install)
```
- Intention guys Important . After Fork , Change this .

```diff
- GitUser="78sdtechfi"
```

## Description

## <img src="https://img.shields.io/badge/-Services%20%26%20Port-brightgreen">

- OpenSSH                    : 22
- WebScket Python OpenSSH    : 100
- WebScket Python Dropbear   : 80
- WebScket Python SSL/TLS    : 443
- OpenVPN-WS Python          : 2099
- OpenVPN                    : TCP 1194, UDP 2200, SSL 442
- Stunnel4 SSL/TLS           : 445, 777
- Dropbear                   : 143,109, 69
- Squid Proxy                : 3128,8000,8080 (limit to IP Server)
- Badvpn                     : 7100-7900
- Nginx                      : 81
- Wireguard                  : 7070
- L2TP/IPSEC VPN             : 1701
- PPTP VPN                   : 1732
- SSTP VPN                   : 5555
- Shadowsocks-R              : 1443-1543
- SS-OBFS TLS                : 2443-2543
- SS-OBFS HTTP               : 3443-3453
- V2RAY Vmess TLS            : 8443
- V2RAY Vmess None TLS       : 8880
- V2RAY Vless TLS            : 2083
- V2RAY Vless None TLS       : 2052
- Trojan                     : 2087



## Credit :
  
-   Original Script by  Horas , SL
-   Modded and update Script by t.me/PrinceNewbie
	
	
	            
	
	<p align="center"><img src="https://img.shields.io/badge/%20COPYRIGHT%20%C2%A9%202022-%20By%20PrinceNewbie%20VPN%2C%20Inc-blue"></p>
