Redirect connections from different ports at one ipv4 address to unique random ipv6 address from \64 subnetwork. Based on 3proxy

## Requirements
- Centos 7 Without Selinux
- Ipv6 \64

## Installation

1. `yum -y install epel-release`

2. `yum -y update`

3. `bash <(curl -s "https://raw.githubusercontent.com/linucat/proxyv6/main/500-proxy.sh")`

## Download Proxy List

I do not upload it because I can't trust any file hosting provider. So copy the proxy list from your server:

1. `nano /home/proxy-installer/proxy.txt`

2. Copy all the proxies here

* File structure: `IP4:PORT:LOGIN:PASS`

The source : 3proxy
