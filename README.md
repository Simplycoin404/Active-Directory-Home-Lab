# Active Directory Home Lab

## Overview

This project documents my Windows Server 2022 Active Directory home lab built in VirtualBox.

The goal of this lab is to simulate a small enterprise environment and practice real help desk, system administration, and cybersecurity fundamentals.

## Current Lab Setup

- Domain Controller: DC01
- Operating System: Windows Server 2022
- Domain: TestLab.local
- Static IP Address: 192.168.56.10
- Network Type: VirtualBox Host-Only Adapter
- Services Installed:
  - Active Directory Domain Services
  - DNS Server

## What I Configured

1. Created a Windows Server 2022 virtual machine in VirtualBox.
2. Configured the VM on a Host-Only virtual network.
3. Assigned DC01 a static IP address of 192.168.56.10.
4. Installed Active Directory Domain Services.
5. Promoted the server to a Domain Controller.
6. Created a new Active Directory forest and domain.
7. Installed DNS for domain name resolution.
8. Created Organizational Units for departments.
9. Created domain user accounts.

## Skills Practiced

- Windows Server administration
- Active Directory setup
- DNS configuration
- Static IP addressing
- Virtual networking
- User account creation
- Organizational Unit management
- Enterprise identity management

## Next Steps

- Create a Windows 11 client VM
- Join the client to the domain
- Create security groups
- Configure shared folders
- Simulate password reset tickets
- Simulate locked account tickets
- Configure Group Policy
