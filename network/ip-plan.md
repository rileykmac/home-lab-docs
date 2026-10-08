# IP Addressing Plan

## Network

Subnet: 192.168.4.0/24 (Based on the eero gateway)
Gateway: 192.168.4.1 

## Addressing policy

Static (DHCP Reservation): Switches, AP, Future router
DHCP: Laptops, thin client

## Device assignments

| asset_tag | name | ip_address | static/DHCP |
|---|---|---|---|
| HL-0001 | Core switch | 192.168.4.2 | Static* |
| HL-0002 | PoE switch | 192.168.4.3 | Static* |
| HL-0003 | Wi-Fi AP | | | 

## Switch port assignments

### Core switch (HL-0001)

| Port | Connected to | Notes |
|---|---|---|
| 1 | | |
| 2 | | |
| 3 | | |

### PoE switch (HL-0002)

| Port | Connected to | Notes |
|---|---|---|
| 1 | | |
| 2 | | |
| 3 | | |

## Future: VLAN plan (phase 2/3)

<!-- placeholder for when you get there -->