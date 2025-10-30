# VLANs & ACLs in Cisco Packet Tracer

## Overview
This project demonstrates how to segment a small company network using VLANs and enforce traffic restrictions using ACLs.

### VLAN Setup
- VLAN 10: Admin — unrestricted access
- VLAN 20: Sales — cannot access Admin VLAN
- VLAN 30: Guest — limited access (no internal network)

### ACL Configuration
- Admin (VLAN 10) has full access.
- Sales (VLAN 20) can only reach Guest VLAN.
- Guest (VLAN 30) is restricted to external access.

### Tools Used
- Cisco Packet Tracer 8.x
- Cisco 2960 Switch
- Cisco 2811 Router

### Learning Outcome
- VLAN creation and trunking
- Inter-VLAN routing (Router-on-a-Stick)
- Basic Access Control Lists (ACLs)
