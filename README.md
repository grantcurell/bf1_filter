I got tired of Dice being too derpy to match me to servers in my region. Not sure why. Maybe they don't understand basic geoip location. It's beyond me. So I put together this nice script to just filter out the approximately 5 billion German servers I was getting matched to so my ping wouldn't be terrible.

Seriously, half their servers are in Hessen Germany. For a while there, it only ever matched me to them. I live in Texas so suffice it to say, ping was a pretty big issue. Oddly enough, their servers in Portland Oregan were also quite slow. Overall, the script should be pretty solid for anyone in the US.

### Useful wireshark filter for seeing BF1 traffic (tailored for me)
!(ip.addr == 52.17.36.46) and !arp and !http and !ssl and !mdns and !ip.addr==23.76.193.104 and !dns and !smb and !ip.addr==172.230.194.179 and !ip.addr==104.224.46.199 and !ip.addr==34.235.245.195 and !ip.addr==34.202.228.100 and !tcp.port==80  and !tcp.port==443 and !ip.addr==192.168.1.5 and !dhcpv6 and!ip.addr==54.174.7.237 and !nbns and !ssdp and !ip.addr>=224.0.0.0 and !ip.addr==192.168.1.99 and !ip.addr==134.213.244.177 and !ip.addr==159.153.75.142 and !ip.addr==159.153.42.87 and !ip.addr==185.179.200.219 and !ip.addr==185.179.203.76 and !ip.addr==159.153.244.222 and !ip.addr==159.153.166.152 and !(ip.addr==35.157.160.126) and !(ip.addr==43.239.136.238) and !(ip.addr==109.200.215.134) and !(ip.addr==109.200.221.170) and !(ip.addr==159.153.42.88) and !(ip.addr==185.50.104.231) and !ip.addr==64.233.168.125 and !ip.addr==173.193.186.4 and!ip.addr==155.133.254.132 and !ip.addr==23.229.5.250

### This is just a list of all the servers I found as I went. Apparently, half of BF1's servers are in Hessen Germany.
162.245.204.50 (North America - California)
162.245.204.50 (North America - California)
104.153.84.238 (North America - California)
104.153.84.233 (North America - California)
104.153.84.238 (North America - Virginia)
54.190.36.34 (North America - Portland)
34.214.8.213 (North America - Portland)
18.194.239.198 (Germany - Hessen)
54.93.44.79 (Germany - Hessen)
35.158.139.63 (Germany - Hessen)
18.195.159.212 (Germany - Hessen)
54.93.224.238 (Germany - Hessen)
54.93.70.111 (Germany - Hessen)
54.93.249.135 (Germany - Hessen)
18.195.216.49 (Germany - Hessen)
54.93.187.61 (Germany - Hessen)
52.59.200.142 (Germany - Hessen)
54.93.210.202 (Germany - Hessen)
18.195.119.38 (Germany - Hessen)
54.93.173.122 (Germany - Hessen)
54.93.219.123 (Germany - Hessen)
18.194.53.240 (Germany - Hessen)
35.158.139.103 (Germany - Hessen)
18.197.62.95 (Germany - Hessen)
18.194.173.233 (Germany - Hessen)
54.93.211.44 (Germany - Hessen)
31.204.143.109 (Netherlands - Zuid-Holland)
31.204.143.146 (Netherlands - Zuid-Holland)
54.64.49.176 (Japan - Tokyo)

