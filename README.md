
# Enterprise Network Design with DHCP and Multi-Router Connectivity

## Overview

This project demonstrates the design and implementation of a multi-router enterprise network using Cisco Packet Tracer. The main objective was to establish communication between multiple LAN environments while simplifying host configuration using DHCP.

The network connects several LAN segments through routers and switches, allowing automatic IP assignment to end devices and successful communication between different networks.

No DNS, server services, Telnet, or dynamic routing protocols were used. The focus of this project is on core networking fundamentals such as IP addressing, DHCP configuration, and inter-network connectivity.

---

## Network Features

- Multi-router topology
- Multiple LAN environments
- DHCP-based automatic IP configuration
- IPv4 addressing and subnetting
- End-to-end connectivity testing (ICMP ping)
- Cisco CLI configuration

---

## Technologies Used

- Cisco Packet Tracer
- DHCP (Dynamic Host Configuration Protocol)
- IPv4 Addressing
- Cisco IOS Command Line Interface

---

## Network Architecture

The topology consists of:

- Multiple routers interconnected through WAN links
- Switches connecting end devices within each LAN
- PCs and laptops receiving IP addresses dynamically via DHCP

Each LAN operates within its own subnet while maintaining connectivity with other networks.

---

## DHCP Configuration

DHCP was configured to:

- Automatically assign IP addresses to hosts
- Reduce manual configuration effort
- Ensure consistent network configuration

---

## Testing and Validation

Connectivity was verified through:

- ICMP ping testing between different devices
- Checking DHCP assigned IP addresses
- Verifying routing tables and interface status

Successful communication confirms correct network configuration.

---

## Skills Demonstrated

- Network topology design
- DHCP configuration
- IP subnetting
- Router and switch configuration
- Cisco CLI usage
- Network troubleshooting

---

## Screenshots

### Network Topology

<img width="1175" height="697" alt="Screenshot 2026-02-06 173849" src="https://github.com/user-attachments/assets/2abc8e0a-e40a-4bc2-bf52-9798ddc5cd50" />


### Routing Table Verification

<img width="862" height="860" alt="Screenshot 2026-02-06 174636" src="https://github.com/user-attachments/assets/ae81cb61-ee43-4838-8dc6-2a9aca44d9f1" />


### Connectivity Testing

<img width="926" height="112" alt="Screenshot 2026-02-06 173908" src="https://github.com/user-attachments/assets/efb5f2f2-d6ec-4543-a36e-03ce4ef59be8" />


### DHCP IP Assignment 1

<img width="864" height="870" alt="Screenshot 2026-02-06 174456" src="https://github.com/user-attachments/assets/83cb6590-c986-4305-83e0-10f8dab92c67" />


### DHCP IP Assignment 2

<img width="873" height="868" alt="Screenshot 2026-02-06 174554" src="https://github.com/user-attachments/assets/27d90cd2-d0d7-4a07-8f31-1f3c4df57157" />


---

## Future Improvements

- Add dynamic routing (OSPF or EIGRP)
- Implement network security
- Add remote management (SSH)
- Introduce VLAN segmentation

---

## Author

Gagandeep Kaur
