# SOHO-Network-Design-and-Simulation-Cisco-Packet-Tracer
This project demonstrates the design and simulation of a Small Office/Home Office (SOHO) network using Cisco Packet Tracer. The network consists of switches, hosts, and router, configured for basic connectivity and IP addressing.
# Network Topology
- 1 Router (for inter-VLAN and internet access)
- 2 Switches (to segment the network and connect hosts)
- 4 PCs (Hosts) connected to the switches
  
![Network Diagram](Images/soho.png)
## Devices Used

![Network Spreadsheet](Images/Devices.png)

## IP Addressing Plan

![IP Plan Spreedsheet](Images/IP.png)

# Basic Configuration steps
## Router
- IP address and secret Password configuration
![Router](Images/Router.png)

- Confirm Message of the day
![motd](Images/motd.png)

## Switches 
- SVI configuration to enable remote management
![SVI](Images/SVI.png) 

## PCs
- Assign IP addresses manually
![PC IP](Images/PC_IP.png)

# Connectivity Test
- Ping command from PC 1
![PC1 Ping](Images/PC1_Ping.png)

- Ping command from PC 3
![PC3 Ping](Images/PC3_Ping.png)

# Learning Points 
- Designing a structured small office network
- Configuring encrypted password and MOTD banner
- Configuring management VLAN interfaces
- Assigning IP addresses and gateways
- Verifying network connectivity with ping command
- Understanding physical and logical topology
