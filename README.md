# CNRoutingAssignment

## Overview
This repository contains the configuration files and documentation for the Computer Networks routing practical assignment. The assignment demonstrates the configuration of Cisco routers across three distinct tasks using Cisco Packet Tracer: Basic Router Configuration, Static Routing, and Dynamic Routing (RIPv2 & EIGRP).

## Student Details
* **Module:** Computer Networks
* **Student ID:** 39123
* **GitHub Repo:** CNRoutingAssignment

## Tasks

### Task 1 - Basic Router Configuration
Established secure router management by configuring a custom hostname (`KandyNSBM_39123`) and securing the console port with password authentication (`NSBM`).

### Task 2 - Static Routing Configuration
Configured IP addressing and static routes across three routers to connect three separate LAN networks:
* **Network A (Computing):** 192.168.1.0/24
* **Network B (Business):** 192.168.2.0/24
* **Network C (Science):** 192.168.3.0/24

Static routes were manually configured on each router to ensure successful end-to-end connectivity between all network pairs.

### Task 3 - Dynamic Routing (RIP & EIGRP)
**Part A: RIP (Routing Information Protocol)**
Implemented RIPv2 dynamic routing across three routers (KandyNSBM, ColomboNSBM, GalleNSBM) connecting two LAN networks (172.16.0.0/16 and 173.16.0.0/16). Configured `no auto-summary` for VLSM support.

**Part B: EIGRP (Enhanced Interior Gateway Routing Protocol)**
Removed RIP and applied Cisco's EIGRP (Autonomous System 1). EIGRP provided faster convergence using the DUAL algorithm and composite metrics.

## Files Included
* Packet Tracer (`.pkt`) configuration files for each task.
