ProxyBroker + Proxychains config output
===========
* Original repo: https://github.com/constverum/ProxyBroker
Usage:
proxybroker find -f proxychains --types SOCKS5 -o proxy.conf -l 1 && proxychains4 -f proxy.conf curl google.com

