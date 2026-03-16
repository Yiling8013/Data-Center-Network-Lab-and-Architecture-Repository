# VXLAN EVPN Data Center Lab

## Overview

This project demonstrates a VXLAN EVPN-based spine-leaf data center architecture.  
The lab focuses on implementing an EVPN control plane with VXLAN overlay to provide scalable Layer 2 and Layer 3 connectivity across the fabric.

This repository includes topology diagrams, device configurations, and validation commands used to build and test the environment.

---

## Topology

![Topology](topology/topology.png)

### Network Design

- Spine-leaf Clos architecture
- Layer 3 underlay network
- VXLAN overlay network
- EVPN control plane using BGP
- Anycast gateway for distributed routing

---

## Lab Environment

| Component | Platform |
|---|---|
| Network Emulator | EVE-NG |
| Switch OS | Cisco Nexus 9000v |
| Routing Protocol | OSPF |
| Control Plane | BGP EVPN |
| Overlay Technology | VXLAN |

---

## Topology Structure
