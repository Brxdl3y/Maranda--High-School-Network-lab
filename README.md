**Maranda High School – Enterprise Network Topology**

This project simulates the **Maranda High School network infrastructure** using Cisco Packet Tracer.  

The design represents a scalable and secure LAN/WAN deployment, integrating advanced routing and switching concepts within the various departments; **Laboratory, Library, Administration Block, Staffroom, Humanities** and **Faiba** acting as the ISP vendor. 

However, it also highlights enterprise-grade routing(OSPF), switching, and security implementation suitable for modern academic institutions. Perfectly aligned with CCNA/CCNP-level skills and practical network design principles.

**Objectives**

- Provide **connectivity across departments** (Admin, Staffroom, Library, Humanities).  

- Implement **efficient routing** using OSPF for inter-network communication.  

- Ensure **network security** through MD5 authentication and passive interfaces.  

- Apply **subnetting & VLAN segmentation** for structured IP addressing.  

- Simulate **ISP connectivity** to represent real-world internet access.


⚙️ Features & Configurations  
### 🔹 Routing & WAN
- **OSPFv2 Routing** implemented for dynamic route exchange.  
- **Passive Interfaces** configured to minimize routing overhead.  
- **Serial WAN links** established between departments and ISP.  
- **MD5 Authentication** applied for OSPF neighbor security.  
- **Loopback Interfaces** configured for router identification & testing.  

### 🔹 LAN & Switching
- **Subnetting** applied to efficiently allocate IP addresses across VLANs.  
- **Departmental VLANs** configured for Admin, Staffroom, Library, and Humanities.  
- **Inter-VLAN routing** enabled for communication across departments.  

### 🔹 Security & Reliability
- **MD5 OSPF Encryption** ensures secure routing updates.  
- **Access Control** via VLAN segmentation.  
- **Scalable Design** allowing future departmental expansion.  

### 🔹 End Devices
- PCs in Admin & Staffroom VLANs with gateway connectivity.  
- ISP connectivity simulated for real-world internet access.  


Subnetting Summary
| Department      | Subnet         | Gateway       | VLAN | Host Range          |
|-----------------|---------------|--------------|------|---------------------|
| Admin Office    | 10.0.1.0/24   | 10.0.1.254   | 10   | 10.0.1.1 – 10.0.1.254 |
| Staffroom       | 10.0.2.0/24   | 10.0.2.254   | 20   | 10.0.2.1 – 10.0.2.254 |
| Library         | 192.168.34.0/30 | 192.168.34.2 | 30   | /30 P2P Link        |
| Humanities Dept | 192.168.245.0/29 | 192.168.245.3 | 40 | 192.168.245.1 – 192.168.245.6 |


📌 Skills Demonstrated

✅ Enterprise Network Design  
✅ OSPF Dynamic Routing & Authentication  
✅ VLAN & Subnetting Expertise  
✅ WAN Connectivity (Serial Links & ISP Simulation)  
✅ Secure & Scalable Architecture  
✅ Documentation & Professional Network Engineering Practices  


 How to Use

1. Open the `.pkt` file in **Cisco Packet Tracer**.  
2. Load `command.txt` for step-by-step configurations.  
3. Test connectivity via **ping** & **OSPF neighbor adjacencies**. 

 Connect With Me
  Author - Bradley Giovanni
- **Email**: giovanniibradley@gmail.com 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bradley-giovanniii293)

