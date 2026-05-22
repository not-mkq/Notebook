# Notebook

## LuaLaTex
```LaTex
\usepackage{luatexja-fontspec}
\setmainjfont{Sarasa UI SC}
```
## Dnsmasq
```
sudo ip addr add 192.168.1.1/24 dev enp2s0 && sudo ip link set enp2s0 up
dnsmasq -i enp2s0 --bind-interfaces -p0 --dhcp-range=192.168.1.50,192.168.1.150,1h -d --dhcp-option=6,8.8.8.8,1.1.1.1
```
