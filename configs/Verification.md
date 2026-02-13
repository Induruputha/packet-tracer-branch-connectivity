# Verification & Testing

## On R1 and R2
### Check interfaces
- show ip interface brief

### Check routing table
- show ip route

### Ping tests
From R1:
- ping 10.0.0.2
- ping 192.168.20.1
- ping 192.168.20.10

From R2:
- ping 10.0.0.1
- ping 192.168.10.1
- ping 192.168.10.10

## On PCs
PC-A:
- IP: 192.168.10.10
- Mask: 255.255.255.0
- GW: 192.168.10.1

PC-B:
- IP: 192.168.20.10
- Mask: 255.255.255.0
- GW: 192.168.20.1
