# Corporate Private Network Lab

## Overview

This project simulates a small company network using Windows Server and Windows client machines. The goal was to build a private internal network with centralized user authentication, automatic IP addressing, DNS, and shared resources.

## Project Goals

- Configure a Windows Server as a domain controller
- Set up Active Directory users
- Configure DHCP for automatic IP assignment
- Configure DNS for domain name resolution
- Join Windows client machines to the domain
- Test domain user login
- Configure shared folder access for authenticated users

## Technologies Used

- Windows Server
- Active Directory Domain Services
- DNS
- DHCP
- Windows 10 Client
- VirtualBox
- Private Network / Host-only Network

## Lab Design

The lab contains one Windows Server and two Windows client machines connected to the same private network.

| Device | Role | Purpose |
|---|---|---|
| Windows Server | Domain Controller | AD, DNS, DHCP |
| Client 1 | Windows Client | Domain login testing |
| Client 2 | Windows Client | Domain login and file sharing test |

## Features Implemented

- Centralized domain login
- Domain users created in Active Directory
- DHCP automatic IP assignment
- DNS configured for the internal domain
- Client machines joined to the domain
- Shared folder access for domain users

## Screenshots

Screenshots will be added in the `screenshots` folder.

Planned screenshots:

1. Server Manager showing AD DS, DNS, and DHCP
2. Active Directory users
3. DHCP lease list
4. Client joined to the domain
5. Domain user login
6. Shared folder access

## What I Learned

- How to set up a basic company-style private network
- How Active Directory centralizes user authentication
- How DHCP assigns IP addresses automatically
- How DNS supports domain communication
- How to join client computers to a Windows domain
- How to troubleshoot domain login and shared folder access

## Future Improvements

- Add Group Policy settings
- Add more client computers
- Add password policy
- Add network drive mapping
- Add backup configuration
