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

* Designed and administered a multi-tier Proxmox VE home lab environment to simulate enterprise infrastructure, networking, identity management, and security operations workflows.
* Deployed and maintained Windows Server 2025, Active Directory Domain Services (AD DS), Windows 11, pfSense, Security Onion, and Linux-based systems to support infrastructure and cybersecurity testing.
* Configured Active Directory organizational units (OUs), user accounts, security groups, Group Policy Objects (GPOs), and domain-joined endpoints to simulate enterprise identity and access management practices.
* Implemented VLAN segmentation, virtual switches, network bridges, DHCP, DNS, firewall policies, and inter-VLAN routing to create isolated network zones and controlled communication paths.
* Managed pfSense firewall configurations, NAT policies, and access control rules to secure network traffic between client, server, and monitoring segments.
* Integrated Security Onion and Elastic Agents to centralize log collection, endpoint visibility, intrusion detection, and security event monitoring across the lab environment.
* Performed system administration tasks including user provisioning, password management, policy enforcement, operating system updates, troubleshooting, and system hardening.
* Diagnosed and resolved network connectivity, authentication, DNS, Group Policy, Elastic Agent, and firewall-related issues using structured troubleshooting methodologies.
* Documented infrastructure architecture, configurations, implementation procedures, and lessons learned to improve repeatability and operational efficiency.
* Configured and administered Active Directory Domain Services (AD DS), including user account management, password policy enforcement, organizational unit design, security group administration, and Group Policy deployment.



<img width="1539" height="1022" alt="ChatGPT Image May 25, 2026, 02_53_34 AM" src="https://github.com/user-attachments/assets/da96ec97-0af1-43da-9a0d-0501a5206462" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Identity & Access Management

Deployed Windows Server 2025 as an Active Directory Domain Services environment to simulate enterprise user, group, and workstation administration.

- Promoted Windows Server 2025 to a domain controller and configured a lab domain for centralized identity management.
- Created organizational units, domain users, security groups, and basic role-based access structures.
- Joined a Windows 11 client VM to the domain and validated domain authentication.
- Configured Group Policy Objects for password policy, account controls, and workstation management.
- Troubleshot domain login, DNS, password reset, and Group Policy application issues using Windows administrative tools.

----

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
