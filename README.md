# Project Network Topology

Final network topology design and simulation created for our Semester 2 Networking subject.

## 📌 Project Overview
This repository contains the final Cisco Packet Tracer simulation file (`PROJECT_GROUP1(FINAL).pkt`) developed by Group 1. The project involves designing, configuring, and simulating a functional enterprise-level network infrastructure that seamlessly interconnects multiple departments.

## 🏗️ Network Topology Design
Our network is designed to simulate a comprehensive corporate or campus environment. Key features of the topology include:
*   **Hierarchical Architecture:** The core of the network utilizes central routing and switching to interconnect three main distribution zones across the infrastructure.
*   **Departmental Segregation:** End devices (PCs and laptops) are logically grouped into separate departmental networks or subnets (e.g., HR, IT, Finance, Sales) for efficient traffic management and organizational structure.
*   **Access Layer Connectivity:** Each department utilizes dedicated access switches to provide network connectivity to numerous end-user workstations.
*   **Scalable Design:** The structured layout allows for easy expansion, troubleshooting, and the addition of new end devices or entire departments in the future.

## ⚙️ Prerequisites
To open and interact with this simulation, you will need:
*   **Cisco Packet Tracer** (Version 8.0 or newer recommended) installed on your system.
*   A Cisco Networking Academy (NetAcad) account or Skills for All account to log in to the software.

## 🚀 How to Run the Simulation
Follow these steps to explore and test the network:

1.  **Download the Project:** Navigate to the `PROJECT_GROUP1(FINAL).pkt` file in this repository and click the **Download** (raw) button to save it to your local machine.
2.  **Launch Packet Tracer:** Open the Cisco Packet Tracer application and log in.
3.  **Open the File:** Go to `File > Open` (or press `Ctrl+O`) and select the downloaded `.pkt` file.
4.  **Allow Network Convergence:** Once the file loads, wait a few moments for the routing protocols and spanning-tree instances to converge. The link lights on the connections should turn from amber to **green**.
5.  **Test Connectivity:** 
    *   **Via Command Line:** Click on any PC or Laptop, navigate to the **Desktop** tab, and open the **Command Prompt**. Use the `ping [IP_ADDRESS]` command to test the connection to devices in different departments.
    *   **Via Visual PDU:** Press `P` on your keyboard to use the "Add Simple PDU" tool (the closed envelope icon). Click a source PC and a destination PC to visually verify if the packet travels successfully across the network.
