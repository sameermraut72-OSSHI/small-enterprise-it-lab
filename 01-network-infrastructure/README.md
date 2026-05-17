# 01 Network Infrastructure

## Overview

This module documents the enterprise office network infrastructure designed for the Small Enterprise IT Lab project.

The objective was to simulate a realistic small business network environment supporting approximately 30–50 employees across multiple departments.

The network was designed to provide:

- Department segmentation
- Secure traffic separation
- DHCP-based IP allocation
- Inter-VLAN communication
- Printer connectivity
- Voice support
- CCTV network planning
- Internet access simulation

---

## Business Scenario

A growing small office requires a structured network environment to support:

- Human Resources
- Finance
- Operations
- IT Department
- Shared printers
- IP phones
- CCTV surveillance
- Internet access

The design prioritised scalability, security, and departmental segmentation.

---

## Technologies Used

- Cisco Packet Tracer
- Cisco Switches
- Cisco Routers
- VLANs
- Router-on-a-Stick
- DHCP
- Access Ports
- Trunk Ports
- VoIP simulation
- ACL concepts

---

## Network Design

The office network was segmented using VLANs.

Example VLAN structure:

| VLAN ID | Department |
|--------|------------|
| 10 | HR / Admin |
| 20 | Finance |
| 30 | Operations |
| 40 | IT |
| 50 | Printers |
| 60 | CCTV |
| 80 | Voice |

Inter-VLAN communication was configured using router subinterfaces.

DHCP pools were configured to automatically assign IP addresses to clients.

---

## Features Implemented

- VLAN segmentation
- Router-on-a-Stick configuration
- DHCP pool creation
- Switch trunk configuration
- Access port assignment
- IP addressing plan
- Printer connectivity
- Voice VLAN configuration
- CCTV design planning

---

## Skills Demonstrated

- Enterprise network planning
- Cisco switching fundamentals
- VLAN implementation
- DHCP troubleshooting
- Layer 2 / Layer 3 segmentation
- Network troubleshooting
- IP addressing design

---

## Screenshots

<img width="1919" height="1052" alt="image" src="https://github.com/user-attachments/assets/91ff4ac5-98d3-4538-a097-81149267759e" />
_fig i: Network design for small office.

<img width="1344" height="741" alt="image" src="https://github.com/user-attachments/assets/32e51d52-a086-45cd-91ea-4c33a8718466" />
_fig ii: illustrating the vlan brief 

<img width="1913" height="932" alt="image" src="https://github.com/user-attachments/assets/2b4e8766-98f8-474d-901c-cd47a7b6cccc" />
_fig iii: Illustrating Trunk interfaces

<img width="833" height="484" alt="image" src="https://github.com/user-attachments/assets/81d79f53-a329-4480-8a34-90fa3ab32248" />
_fig IV: Illustrating DNS _

<img width="833" height="737" alt="image" src="https://github.com/user-attachments/assets/53209c96-b977-4a55-a3bc-700a56e8165c" />
_Fig V: Illustrating DHCP Binding
_
<img width="1915" height="970" alt="image" src="https://github.com/user-attachments/assets/a1172c51-d44c-4b73-af1c-e38f0f3a142b" />
Fig VI: Cisco IP telephony simulation with dedicated voice VLAN and DHCP option 150



## Future Improvements

Potential future additions:

- OSPF routing
- NAT/PAT internet simulation
- Firewall policies
- VPN connectivity
- Wireless controller simulation
