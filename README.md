# vpn-script
testing phase
for Debian 9/10, Ubuntu 18/20

apt update && apt upgrade -y && update-grub && sleep 2 && reboot

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/akiraafudo/vpn-script/master/setup.sh?token=AQVYALOE5WK7HZT2WHVVYBDBBPGUM&& chmod +x setup.sh && screen -S setup ./setup.sh
