# IP Addressing Plan (Two Branch Network)

## WAN Link (Point-to-Point)
- Network: 10.0.0.0/30
- R1 WAN: 10.0.0.1/30
- R2 WAN: 10.0.0.2/30

## Branch A LAN
- Network: 192.168.10.0/24
- R1 LAN Gateway: 192.168.10.1
- SW1 Mgmt IP: 192.168.10.2
- PC-A: 192.168.10.10
- Default Gateway (PC-A): 192.168.10.1

## Branch B LAN
- Network: 192.168.20.0/24
- R2 LAN Gateway: 192.168.20.1
- SW2 Mgmt IP: 192.168.20.2
- PC-B: 192.168.20.10
- Default Gateway (PC-B): 192.168.20.1

## DNS (Optional)
- 8.8.8.8 (if you add internet simulation later)
