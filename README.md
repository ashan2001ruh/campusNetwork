# EE8203 FoE-UoR Network Design Project

This repository contains the configuration, automation scripts, Ansible roles, monitoring exports, and documentation for the EE8203 Design and Management of Data Networks group project.

## Project Overview

The project simulates the Faculty of Engineering, University of Ruhuna network using GNS3/Cisco images. The topology includes core, edge, distribution, and access layers with VLAN segmentation, OSPF routing, ACL-based policy enforcement, NAT, automation, and Zabbix monitoring.

## Main Components

- Cisco router and switch configurations
- VLAN and IP addressing plan
- OSPF routing
- NAT overload on edge router
- ACL security policies
- Netmiko automation scripts
- Ansible roles and playbooks
- Zabbix monitoring dashboard export
- MOP and testing evidence

## Repository Structure

- `configs/` - Device configurations
- `netmiko/` - Python Netmiko automation scripts
- `ansible/` - Ansible inventory, playbooks, roles, group_vars, and host_vars
- `zabbix/` - Zabbix dashboard export and monitoring evidence
- `docs/` - Design documents, MOP, and project notes
- `evidence/` - Ping, traceroute, ACL, and Zabbix test evidence

## Note

Cisco images, GNS3 VM files, CML images, and license files are not included in this repository.