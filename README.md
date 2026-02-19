# Network Lab: Multi-Protocol Routing & VLAN Implementation

Project Overview
This project involves building and simulating a multi-segment network in GNS3, including routers, switches, and PCs. The focus is on implementing routing protocols, VLANs, EtherChannel, and IP addressing schemes to create a fully operational network.

Objectives
- Build and simulate the network diagram in GNS3 with proper device labeling.
- Configure RIP, OSPF, and EIGRP routing protocols across Segments 1–3.
- Implement correct redistribution between routing protocols for full connectivity.
- Configure VLANs (311, 321, 331, 341) with proper subnetting.
- Implement EtherChannel and Spanning Tree Protocol (STP) with manual root bridge configuration.
- Apply IP addressing: Class C for Segments 1 & 2, VLSM for Segment 3.
- Plan and implement 60 client subnets across VLANs using private IP ranges.

Tools & Technologies
- Cisco routers & switches (simulated in GNS3)
- VLANs, EtherChannel, STP
- Routing Protocols: RIP, OSPF, EIGRP
- IP Addressing: Class C, VLSM

Key Skills Demonstrated
- Network design and implementation
- Multi-protocol routing configuration
- VLAN segmentation and inter-VLAN routing
- Network redundancy via STP
- EtherChannel configuration
- IP addressing & subnetting

  
Results
- Full connectivity across all devices confirmed via ping tests
- Proper VLAN segmentation achieved
- Correct routing and redistribution implemented across protocols

## Repository Contents
- `topology.png` → network diagram
- `router_config.txt` → router configurations
- `switch_config.txt` → switch configurations
- README.md → project documentation
