# IT-Support-Home-Lab Project
A virtual home lab for IT troubleshooting practice.

**Tools Used**: VirtualBox, Cisco Packet Tracer, Wireshark  

## Overview  
This lab simulates a small office network to practice troubleshooting DHCP failures, DNS misconfigurations, and firewall rules.  

## Setup Instructions  
1. **Download Required Tools**:  
   - [VirtualBox](https://www.virtualbox.org/)  
   - [Cisco Packet Tracer](https://www.netacad.com/)  

2. **Replicate the Network**:  
   - Download the Cisco Packet Tracer file: [lab-topology.pkt](cisco-configs/lab-topology.pkt).  
   - Open it in Cisco Packet Tracer to view the network layout.  

3. **Virtual Machine Setup**:  
   - Import the Windows 10 VM configuration from `/docs/windows-vm-setup.md`.  

## Screenshots  
![Network Topology](screenshots/network-diagram.png)  
*Diagram of the lab network*  

## Troubleshooting Examples  
- **DHCP Failure**:  
  - Symptoms: PCs can’t get IP addresses.  
  - Fix: Re-enable the DHCP pool on the router.  

- **DNS Misconfiguration**:  
  - Use the Wireshark capture in [dns-error.pcapng](docs/dns-error.pcapng) to analyze failed queries.  

## Skills Demonstrated  
- Configuring routers/switches in Cisco Packet Tracer.  
- Analyzing network traffic with Wireshark.  
- Automating fixes with PowerShell scripts.  
