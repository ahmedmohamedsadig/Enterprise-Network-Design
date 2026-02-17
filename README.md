Enterprise Network Infrastructure Design & Simulation
🌐 Project Overview
This project demonstrates a robust, scalable, and high-availability network architecture designed for a modern enterprise environment. Using Cisco Packet Tracer, I implemented a 3-layer hierarchical model (Access, Distribution, and Core) to ensure network efficiency, redundancy, and security.

🛠️ Technical Features
Hierarchical Design: Implemented Access, Distribution, and Edge layers for structured traffic management.

Redundancy & Load Balancing: Configured EtherChannel (LACP/PAgP) and redundant links to prevent single points of failure.

Network Segmentation: Created VLANs for different departments (HR, IT, and Engineering) to enhance security and reduce broadcast domains.

IP Addressing: Utilized VLSM (Variable Length Subnet Masking) for efficient IPv4 address allocation.

Routing & Switching: Configured Inter-VLAN routing and Layer 3 switching for seamless communication between departments.

📊 Network Topology
VLAN 10: HR Department

VLAN 20: IT Department

VLAN 30: Engineering Department

Management: Secure remote access and DHCP services.

🚀 Tools Used
Cisco Packet Tracer

Cisco IOS (Command Line Interface)

Subnetting Calculators (VLSM)

📂 How to View
Download the .pkt file from this repository.

Open it using Cisco Packet Tracer (Version 8.0 or higher recommended).

You can test connectivity by pinging between different VLANs.
