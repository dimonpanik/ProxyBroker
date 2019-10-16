ProxyBroker 
* Original repo: https://github.com/constverum/ProxyBroker

Adding:
+ Proxychains config output -f proxychains
+ IP:PORT output -f ipport
===========

Usage:
proxybroker find -f proxychains --types SOCKS5 -o proxy.conf -l 1 && proxychains4 -f proxy.conf curl google.com

