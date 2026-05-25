# ProxMox-Server



## Technologies Used

### Virtualization
- Proxmox VE

### Security Tools
- Security Onion
- pfSense

### Operating Systems
- Windows 11
- Windows Server 2025
- Kali Linux
- Ubuntu
- Arch Linux

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Overview

Designed and maintained a Proxmox VE enterprise-style home lab focused on virtualization, network segmentation, security monitoring, and system administration. The environment was built to simulate real-world IT and cybersecurity infrastructure using VLANs, firewall policies, SIEM monitoring, and multi-OS virtualized systems.

---

## Key Responsibilities & Configurations

- Deployed and managed virtualized environments within Proxmox VE, including Windows Server 2025, Windows 11, Kali Linux, Ubuntu, Arch Linux, pfSense, and Security Onion.

- Configured virtual switches, network bridges, VLAN segmentation, and inter-VLAN routing to simulate enterprise network architectures.

- Implemented pfSense firewall policies,and VLAN-based traffic controls to secure and regulate communication between virtualized networks.

- Configured Security Onion for centralized security monitoring, log analysis, and intrusion detection using Elastic Stack and Zeek.

- Tested and troubleshot connectivity, firewall filtering, Elastic Agent communication, and network routing between segmented VLAN environments.

- Performed system hardening, vulnerability management, and security testing within isolated lab environments to strengthen cybersecurity operations knowledge.

- Continuously refined and expanded the lab environment by deploying additional systems, modifying network configurations, and testing enterprise security concepts.

<img width="1539" height="1022" alt="ChatGPT Image May 25, 2026, 02_53_34 AM" src="https://github.com/user-attachments/assets/da96ec97-0af1-43da-9a0d-0501a5206462" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Networking Configuration

### VLAN Segmentation
Configured multiple VLANs within pfSense to separate management, client, server, monitoring, and isolated security networks.

| VLAN | Purpose |
|------|----------|
| VLAN 10 | Management Network |
| VLAN 20 | Client Devices |
| VLAN 30 | Server / Security Onion Network |
| VLAN 40 | SOC Monitoring Network |
| VLAN 50 | Security Tools |

---

### pfSense Configuration
- Configured VLAN interfaces and inter-VLAN routing
- Implemented firewall rules to regulate traffic between segmented networks
- Created NAT rules for internet connectivity and internal communication
- Configured DHCP services for VLAN-based subnet allocation
- Tested inbound and outbound traffic filtering policies

---

### Network Security
- Restricted communication between VLANs using firewall policies
- Validated connectivity using ICMP, TCP port testing, and packet filtering
- Monitored network traffic through Security Onion and Zeek
- Troubleshot routing, DNS resolution, and Elastic Agent communication issues

---

### Virtual Networking
- Configured Proxmox network bridges and virtual NIC assignments
- Integrated pfSense as the primary virtual firewall/router
- Connected virtual machines across segmented VLAN environments


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Lessons Learned

- Improved understanding of VLAN segmentation, inter-VLAN routing, and firewall rule processing within pfSense.

- Gained hands-on experience troubleshooting Elastic Agent enrollment, Fleet communication issues, and Security Onion connectivity across segmented networks.

- Strengthened knowledge of network troubleshooting by diagnosing DNS resolution failures, blocked ports, routing issues, and firewall misconfigurations.

- Learned how NAT rules, interface assignments, and rule order impact traffic flow within virtualized environments.

- Developed practical experience deploying and maintaining virtualized infrastructure using Proxmox VE, including network bridges, virtual switches, and multi-VM environments.

- Improved familiarity with SIEM monitoring, endpoint telemetry, and log analysis through Security Onion and Elastic Stack integrations.
