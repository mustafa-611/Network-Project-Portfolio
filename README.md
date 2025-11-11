# Network-Project-Portfolio
This project demonstrates a complete enterprise-level network infrastructure designed and configured using Cisco routers and switches. It showcases professional-grade networking knowledge, emphasizing scalability, redundancy, flexibility, and security—essential qualities of modern business networks.
# 🧩 Enterprise Network Design and Configuration Project  

This project demonstrates a complete **enterprise-level network infrastructure** designed and configured using **Cisco routers and switches**. It showcases professional-grade networking knowledge, emphasizing scalability, redundancy, flexibility, and security—essential qualities of modern business networks.  

## 🏗️ Network Architecture  

The design follows the **three-layer hierarchical model**:  

### 🔹 Core Layer  
Four Cisco 2901 routers are connected in a full-mesh topology using serial DCE cables to ensure maximum redundancy and high availability. Each router is configured with **OSPF** for dynamic routing, **SSH** for secure remote management, password encryption, and **Access Control Lists (ACLs)** to restrict administrative access.  

### 🔹 Distribution Layer  
Four Cisco Catalyst 3650 Layer 3 switches serve as the central routing points for departments. They handle **VLAN inter-routing**, **DHCP pool management**, and **traffic control** to improve scalability and performance.  

### 🔹 Access Layer  
Multiple Layer 2 switches connect user devices such as PCs, printers, and wireless access points. Each department operates within its own VLAN and subnet, ensuring traffic segmentation, improved security, and efficient management.  

## 🖥️ Server Room and Services  
The Server Room includes **DHCP, DNS, and Web servers** to provide essential services like automatic IP assignment, name resolution, and website hosting.  
Additional configurations include:  
- **Spanning Tree Protocol (PVST)** for loop prevention  
- **ACLs** for access restriction  
- **Port Security** for endpoint protection  

## 🧠 Skills Demonstrated  
- Enterprise network design and documentation  
- VLAN segmentation and DHCP configuration  
- OSPF routing and inter-VLAN communication  
- ACL-based access control and SSH security  
- IPv4 addressing and subnetting  
- Cisco router and switch configuration  

---

📄 **Project Author:** *Mustafa Fadol*  
📘 **Tools Used:** Cisco Packet Tracer, Cisco IOS  
📅 **Year:** 2025  
