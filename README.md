iptables
========

![](https://badge.imagelayers.io/vimagick/iptables:latest.svg)

- _iptables_: filter ports (allow: 53/UDP, 80/TCP, 443/TCP)
- _tc_: control traffic via [tbf][1]

## RUN

	docker run -d --restart=always --name=iptables --cap-add=NET_ADMIN vank3f3/iptables

[1]: http://linux.die.net/man/8/tc-tbf