# Packet Tracer Network - Initial Commit

## 📌 Network Overview
This repository contains a **Packet Tracer** network topology designed to demonstrate basic connectivity between different devices. The network consists of a **PC**, **Laptop**, **Switch**, **Router**, and **Server**, all connected using appropriate cabling.

## 🖥️ Network Topology
The network is structured as follows:

1. **PC0**  
   - Connected to **Switch** on **FastEthernet 0/10**  
   - Cable Type: **Copper Straight-Through (Yellow)**  

2. **Laptop0**  
   - Connected to **Switch** on **FastEthernet 0/20**  
   - Cable Type: **Copper Straight-Through (Yellow)**  

3. **Switch to Router**  
   - Switch port: **GigabitEthernet 0/2**  
   - Router port: **GigabitEthernet 0/0**  
   - Cable Type: **Copper Straight-Through (Green)**  

4. **Server to Switch**  
   - Connected to **Switch** on **FastEthernet 0/24**  
   - Cable Type: **Copper Straight-Through (Red)**  

## ⚡ How to Use
1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Power on all devices.
3. Verify connectivity using **ping** or other network tools.

## 🚀 Future Enhancements
- Implement **Static/Dynamic IP Addressing**.
- Configure **Routing (Static or Dynamic)** for network segmentation.
- Enable **DHCP, DNS, or Web Services** on the server.

## 📜 License
This project is open-source. Feel free to modify and improve it.
