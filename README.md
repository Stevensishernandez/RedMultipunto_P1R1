# Multipoint Network

## Topology 2

### VLMS Subnetting 📄

| VLAN | 	Netmask | Network address | F. A. address | L. A. address | D. broadcast  | H. needed | H. number |
| ------------- |------------- | ------------- | -------------| ------------- | -------------| ------------- | ------------- |
| 30 VENT | 255.255.255.128/25 | 192.168.116.0 | 192.168.116.1 |  192.168.116.126 | 192.168.116.127 | 123 | 128|
| 40 INFO | 255.255.255.192/26 | 192.168.116.128 | 192.168.116.129 | 192.168.116.190 | 192.168.116.191 | 37 | 64|
| 10 RRH | 255.255.255.224/27 | 192.168.116.192 | 192.168.116.193 | 192.168.116.222 | 192.168.116.223 | 21 | 32 |
| 20 CONT | 255.255.255.240/28 | 192.168.116.224 | 192.168.116.225 | 192.168.116.238 | 192.168.116.239 | 8 | 16 |

### PortChannel
| PortChanne | betwen | Links | Ports |
| ------------- | ------------- | ------------- | ------------- |
| Po1 | betwen ESW3 & ESW4 | 2 Links | f1/1 - 2 |
| Po2 | betwen ESW4 & ESW2 | 2 Links | f1/3 - 4 |
| Po3 | betwen ESW2 & ESW5 | 2 Links | f1/5 - 6 |
| Po4 | betwen ESW3 & ESW5 | 2 Links | f1/7 - 8 |
| Po5 | betwen ESW3 & ESW2 | 3 Links | f1/9 - 11 |
| Po6 | betwen ESW2 & SW1 | 2 Links | f1/12-13 to Eth/1-2 |
| Po6 | betwen ESW4 & SW2 | 2 Links | f1/12-13 to Eth/1-2 |
| Po6 | betwen ESW3 & SW3 | 2 Links | f1/12-13 to Eth/1-2 |
| Truncal | betwen ESW5 & R1 | 1 Link | f1/0 to Eth0/0 |
| Truncal | betwen R1 & SW5 | 1 Link | Eth0/1 to Eth1 |

### Esquemas
![Esquema](https://github.com/jmansilla-2014056/galery/blob/master/Nueva%20carpeta/52a5ae1e-2e17-43a7-a940-ec839d1cea14.jpg)
