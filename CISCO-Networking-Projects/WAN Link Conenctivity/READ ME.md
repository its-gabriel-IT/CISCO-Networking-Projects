WAN Connectivity Lab with Static Routing
-----------------------------------------------------------------------------------------------------------------------------

Overview

This project simulates a wide area network (WAN) connection between two geographically separated Local Area Networks (LANs) using Cisco Packet Tracer.
The lab demonstrates how independent networks communicate across routers using a point-to-point WAN link and static routing.

-------------------------------------------------------------------------------------------------------------------------------

Objectives

* Configure and verify a point-to-point WAN link
* Assign IP addressing using efficient subnetting (/30)
* Enable communication between two separate LANs
* Implement and validate static routing
* Practice structured network troubleshooting

--------------------------------------------------------------------------------------------------------------------------------

Technologies & Concepts Used

* IPv4 Addressing & Subnetting
* /30 Point-to-Point WAN Networks
* Static Routing
* Cisco Router Configuration (CLI)
* Interface Configuration (GigabitEthernet & Serial)
* Basic Switching (Layer 2 connectivity)
* End-to-End Connectivity Testing (ICMP / ping)

--------------------------------------------------------------------------------------------------------------------------------

Network Architecture

Topology Summary:
* 2 Routers (WAN edge devices)
* 2 Switches (LAN access layer)
* Multiple end devices (PCs & Laptops)
* 1 Serial WAN link between routers (DCE)

--------------------------------------------------------------------------------------------------------------------------------

IP Addressing Scheme

Office 1 LAN:

Network: `192.168.0.0/24`
Gateway: `192.168.0.1`

Office 2 LAN:

Network: `172.16.0.0/24`
Gateway: `172.16.0.1`

WAN Link:

Network: `192.168.1.252/30`
Router0: `192.168.1.253`
Router1: `192.168.1.254`

-------------------------------------------------------------------------------------------------------------------------------

Skills Demonstrated

* WAN design using point-to-point links
* Efficient subnetting with /30 networks
* Router interface configuration
* Static route implementation
* Layered network troubleshooting methodology
* Understanding of routing tables and packet flow

-------------------------------------------------------------------------------------------------------------------------------

Files Included

* Packet Tracer file (.pkt)
* Network topology diagram

-------------------------------------------------------------------------------------------------------------------------------

Author

Gabriel Bernardes
Network Security Enthusiast

All rights reserved ©
