# 🖧 Packet Tracer | Device Deployment & Network Cabling Lab
📄 **Full Lab Report (Google Doc):**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/Packet-Tracer-Device-Deployment-Network-Cabling-Lab/blob/main/Name_%20Pelumi%20Johnson_Per%20Scholas%20cisco%20packet%20tracer.pdf)


## 📘 Project Summary
This lab demonstrates how to deploy network devices and correctly cable them in Cisco Packet Tracer. I placed multiple PCs, added Cisco 2960 switches, and connected all devices using the proper Ethernet cable types. The goal was to build a functional Layer 2 network, practice interface selection, and understand physical connectivity concepts used in real-world IT and networking roles.

## 🖥️ Devices Used
- 6 PCs (PC0–PC5)
- 2 Cisco 2960 Switches (Switch0, Switch1)

## 🔧 What I Did

### 1. Deployed the Devices
Placed two 2960 switches into the Logical workspace and positioned three PCs around each switch. This created two small groups ready for physical cabling.

### 2. Connected PCs to Switches (Straight-Through Cables)
Used Copper Straight-Through cables to connect each PC’s FastEthernet0 port to a FastEthernet interface on its switch.

Left-side wiring:
- PC0 → Switch0 F0/2
- PC1 → Switch0 F0/3
- PC2 → Switch0 F0/4

Right-side wiring:
- PC3 → Switch1 F0/2
- PC4 → Switch1 F0/3
- PC5 → Switch1 F0/4

Link lights turned amber, then green, confirming physical connectivity.

![Home Network Diagram](https://github.com/Pelumi-Johnson/-My-Local-Network-Home-Topology-Lab/blob/main/Screenshot%202025-11-28%20012506.png)

### 3. Connected Switches Together (Cross-Over Cable)
Linked Switch0 and Switch1 using a Copper Cross-Over cable on GigabitEthernet0/1. This forms a proper switch-to-switch uplink, allowing both sides of the network to communicate.

### 4. Verified the Topology
Used Check Results to confirm all devices were placed correctly, the right ports were used, and all cables matched the required design.

## 🔌 Cable Types Explained

### Copper Straight-Through (PC → Switch)
Used when connecting different device types. This represents the standard Ethernet patch cable a technician uses in real networks.

### Copper Cross-Over (Switch → Switch)
Used when connecting similar device types directly. Packet Tracer enforces this rule to reinforce foundational networking concepts.

## 🧠 Skills Demonstrated
- Deploying end devices and switches
- Selecting correct Ethernet cables
- Understanding FastEthernet vs GigabitEthernet ports
- Building a clean and functional Layer 2 topology
- Recognizing link-light transitions (amber → green)
- Verifying network design using Packet Tracer tools
