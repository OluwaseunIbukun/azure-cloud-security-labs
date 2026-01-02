# Week 1 – Azure Core & Lab Setup

## Objective
Deploy and secure Linux and Windows virtual machines in Microsoft Azure, configure basic network security, and enable centralized logging.

## Resources Created
- Resource Group: rg-week1-core
- Linux VM: vm-linux-week1 (Ubuntu Server)
- Windows VM: vm-win-week1 (Windows Server 2022)
- Log Analytics Workspace: law-week1

## Key Activities
- Created and scoped resources using a single resource group
- Deployed Linux and Windows virtual machines
- Restricted inbound traffic using Network Security Groups (NSGs)
- Enabled Azure Monitor and Log Analytics
- Used Azure Cloud Shell (Bash and PowerShell)

## Validation
- Successfully connected to Linux VM via SSH
- Successfully connected to Windows VM via RDP
- Verified logs in Log Analytics using KQL queries

## Lessons Learned
- Resource groups are essential for cost control and cleanup
- NSGs provide first-layer network protection
- Centralized logging is foundational for cloud security monitoring

## Cleanup
- Deleted the entire resource group to avoid ongoing costs
