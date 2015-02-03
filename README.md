# geotrace
(Only *nix machines for now)

Locate or "traceroute" IP address/domain name.
Geotrace gives info of the geographical location and creates map based on that info.

#Depencies
argparse, pygeoip, pygmaps, scapy, ansicolors
Installation with pip:
sudo pip install argparse pygeoip pygmaps scapy ansicolors

#Usage:

locating ip or domain:
python geotrace.py -t [ip/domain]

geo traceroute:
python geotrace.py -gT [ip/domain]

update/download maxmind's database:
python geotrace.py -d
