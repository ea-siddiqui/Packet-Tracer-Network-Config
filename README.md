# Packet-Tracer-Network-Config

This repository contains the configuration for a basic network setup created using **Cisco Packet Tracer**. The network includes routers, switches, and PCs, connected to demonstrate basic networking concepts such as IP addressing, routing, and switching.


## Network Overview

The network setup includes:

- **Router (1941 Router0)**: Acts as the central router connecting two network segments.
- **Switches (2960-2 TT Switch0 & Switch1)**: Used to connect the PCs and route traffic between them.
- **PCs (PC0, PC1, PC2, PC3)**: End devices connected to switches that communicate across the network.
  
The configuration aims to teach fundamental networking principles, including:

- **Basic IP Addressing**: Assigning IPs and subnet masks to devices.
- **Router Configuration**: Configuring router interfaces and static routing.
- **Switch Configuration**: Setting up switches for network connectivity.
- **Connecting End Devices (PCs)**: Configuring static IPs and ensuring communication.
- **Network Troubleshooting**: Using **ping** and simulation mode to verify connectivity.
- **Simulation and Testing**: Verifying network setup using Cisco Packet Tracer’s simulation mode.


### Network Diagram
![Network Diagram](Network%20Config%20Diagram.jpg)


## Task Instructions

1. **Add Components**:
   - Start by adding the required network components:
     - **Router**: Add a **Cisco 1941 Router** (Router0).
     - **Switches**: Add **Cisco 2960-2 TT Switches** (Switch0 and Switch1).
     - **PCs**: Add four **Cisco PCs** (PC0, PC1, PC2, PC3).

2. **Connect the Components**:
   - Use the appropriate cables to connect the devices:
     - Use **Copper Straight-Through cables** to connect the PCs to the switches.
     - Use **Copper Straight-Through cables** to connect the switches to the router's Ethernet interfaces.
     - Ensure each device is connected to its corresponding port.

3. **Configure the Router**:
   - Configure the router’s **interface IP addresses**:
     - Assign IP addresses to the interfaces that connect to the switches.
     - Configure static routing if needed to route traffic between the two network segments.
   - Enable **interfaces** and check for successful interface activation.

4. **Configure the PCs**:
   - Assign **static IP addresses** to each PC.
   - Set the **default gateway** for the PCs to the router's interface IP that is connected to their respective network.

5. **Simulate and Verify**:
   - Switch to **Simulation Mode** in Cisco Packet Tracer.
   - **Ping** from PC0 to PC1, PC2, and PC3 to check connectivity.
   - Use the **Packet Tracer’s simulation features** to verify the traffic flow and ensure that all devices can communicate with each other.
   - Troubleshoot any connectivity issues and verify the network functionality.


## How to Use

1. Download **Cisco Packet Tracer** (if you don't have it installed).
2. Clone or download this repository to get the network configuration file (`.pkt`).
3. Open the `.pkt` file in Packet Tracer.
4. Review the configuration, modify as needed, or test the network setup.


## Technologies Used

- **Cisco Packet Tracer**: Network simulation tool used to create and test network configurations.
- **Router**: Cisco 1941 series router.
- **Switches**: Cisco 2960-2 TT switches.
- **PCs**: Cisco PCs for testing connectivity.


## About the Project

This project involves setting up a basic network using **Cisco Packet Tracer** to demonstrate essential networking concepts such as IP addressing, router configuration, and switch setup. The goal was to configure a router, switches, and PCs to ensure proper network connectivity and communication across different segments. The project also aimed to teach fundamental skills in network troubleshooting, simulation, and testing within the Packet Tracer environment.


## Contact

For any questions or feedback, feel free to open an issue or reach out to the repository owner.

