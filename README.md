Redirect connections from different ports at one ipv4 address to unique random ipv6 address from \64 subnetwork. Based on 3proxy

## Requirements
- Centos 7
- Ipv6 \64

## Installation
1. `bash <(curl -s "https://raw.githubusercontent.com/linucat/proxyv6/main/500-proxy.sh")`

2. After installation copy the file `/home/proxy-installer/proxy.txt` from your server

I do not upload it because I can't trust any file hosting provider.
   * File structure: `IP4:PORT:LOGIN:PASS`

The source : 3proxy
