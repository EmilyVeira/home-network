# Home Network Simulation - Cisco Packet Tracer

## Overview
A simulated home network bult in Cisco Packet Tracer demonstrating 
NAT, DHCP, DNS, Wi-Fi, and basic routing.

# Topology
<img width="668" height="720" alt="topology" src="https://github.com/user-attachments/assets/a51d5cda-518d-4d9e-b018-def2e9c7abe1" />

## Devices Used
| Device | Model | Role |
|--------|-------|------|
| ISP Router | Cisco 4331 | WAN Gateway |
| Home Router | Cisco 4331 | NAT + DHCP |
| Switch | Cisco 2960 | LAN Distribution |
| ...    | ...   | ... |

## IP Addressing Table
| Device | IP | Subnet | Gateway |
|--------|----|--------|---------|
| Home Router (LAN) | 10.0.0.1 | /24 | — |
| Home Server | 10.0.0.100 | /24 | 10.0.0.1 |
| PCs | DHCP 10.0.0.10+ | /24 | 10.0.0.1 |

## Configurations
See `/configs/` folder for router CLI configs.

## Skills Demonstrated
- NAT / PAT configuration
- DHCP pool setup
- Static vs dynamic IP assignment
- Wireless AP and WPA2
- DNS and HTTP services
- Network simulation and testing
