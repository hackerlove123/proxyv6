# Tested on 2024-May-18 Working on [Vultr VPS](https://www.vultr.com/?ref=8936554)

### You can get [Free $100 Credit Here](https://www.vultr.com/?ref=9001246-8H)

## Requirements
- Centos 7 Without Selinux
- Enable Ipv6 \64 (free)

## Installation

**Log In the server as root user** and run these commands:

1. `yum -y install epel-release`

2. `yum -y update`

3. `bash <(curl -s "https://raw.githubusercontent.com/linucat/proxyv6/main/500-proxy.sh")`

When it asks for **"How many proxy do you want to create? Example 500"**, enter the number of proxy you want to create.

## How To Download Proxy List

Proxies are stored in this file `/home/proxy-installer/proxy.txt`

1. In you computer, open a new terminal window \
`scp root@your-server-ip:/home/proxy-installer/proxy.txt .` 
<br>
<br>
for example, if your server IP address is **192.23.34.111**:
<br>
`scp root@192.23.34.111:/home/proxy-installer/proxy.txt .`


2. File structure: `IP4:PORT:LOGIN:PASS`

## If you need support, contact me @[Telegram](https://t.me/+aWqfCqk9VL41MDBl)

<br>
The source : 3proxy
