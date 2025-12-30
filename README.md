# Hybrid Azure + Linux Security Engineering Lab

## Overview
This project demonstrates a hands-on security engineering lab where an Ubuntu Linux virtual machine is deployed and secured in Microsoft Azure. The lab focuses on defense-in-depth, least privilege, and cloud-native security controls.

## Objectives
- Deploy a Linux VM in Azure using secure defaults
- Restrict network access using Azure Network Security Groups (NSGs)
- Harden the Linux operating system
- Implement logging and monitoring with Azure services
- Document security decisions and trade-offs

## Architecture
- Azure Virtual Network (VNet)
- Network Security Group (NSG)
- Ubuntu Server 22.04 LTS
- Azure Defender for Cloud
- Log Analytics Workspace

## Security Controls Implemented
- SSH access restricted by IP using NSGs
- Password authentication disabled (SSH keys only)
- Root login disabled
- Host-based firewall (UFW)
- Audit logging with auditd
- Cloud security posture management via Defender for Cloud

## Tools & Technologies
- Microsoft Azure
- Ubuntu Linux
- OpenSSH
- UFW
- auditd
- Azure Defender for Cloud
- Log Analytics

## Future Improvements
- Remove public IP and implement Azure Bastion
- Enable disk encryption and Key Vault integration
- Forward logs to Microsoft Sentinel
- Apply CIS Linux benchmarks

## Author
Steven Gant
