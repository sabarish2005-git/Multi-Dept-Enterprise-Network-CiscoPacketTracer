# Multi-Department Enterprise Network
### Built using Cisco Packet Tracer

## About This Project
I built this project to simulate a 
real company network environment. 
The network connects four departments 
using VLANs and provides automatic IP 
assignment, DNS, web server and 
security using ACL rules.

## Departments
| Department | VLAN | Network |
|---|---|---|
| HR | VLAN 10 | 192.168.10.0/24 |
| Finance | VLAN 20 | 192.168.20.0/24 |
| IT | VLAN 30 | 192.168.30.0/24 |
| Management | VLAN 40 | 192.168.40.0/24 |

## What I Used
- Cisco Packet Tracer
- Cisco 2911 Router
- Cisco 3560 Multilayer Switch
- Cisco 2960 Switches
- VLAN and Inter-VLAN Routing
- DHCP Server
- DNS Server
- Web Server
- ACL Security

## What I Configured
- VLANs for each department
- Inter-VLAN routing for communication
- DHCP for automatic IP assignment
- DNS to resolve www.enterprise.com
- Web server for company portal
- ACL to block Finance from IT servers

## Test Results
- HR to Finance ping = Success
- HR to IT ping = Success
- Finance to IT = Blocked by ACL
- Web portal = Accessible from all departments

## Screenshots
### Network Topology
![Topology](01-Network-Topology.png)

### DHCP Pools
![DHCP](02-DHCP-Pools.png)

### Ping Success
![Ping](03-Ping-Success.png)

### ACL Blocking
![ACL](04-ACL-Blocking.png)

### Web Portal
![Web](05-Web-Browser-Portal.png)
