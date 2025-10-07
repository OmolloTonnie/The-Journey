Email Server VLANs Router Setup
Cisco Packet Tracer Project — Email Server with VLANs & Router Inter-VLAN Communication

Overview
This project represents my first full-scale Cisco Packet Tracer setup — a functional email server network integrated with two VLANs connected via a router-on-a-stick configuration.  
It’s designed to simulate real-world enterprise segmentation and inter-VLAN communication, complete with a working mail service using the domain `mail.com`.

---

 Network Components
 End Users 4 in VLAN10 and 2 in VLAN20
 1 Router (for inter-VLAN routing)
 2 Switch (configured with VLANs)
 1 Server (configured as Mail Server)
 VLAN 10 – *Sales Department*  
 VLAN 20 – *IT Department*

---

 Configuration Summary
 VLAN Setup
/ VLAN / Name /  IP Subnet /  Devices  / 
/------/------/------------/----------/ 
/ 10 / sales / 192.168.10.0/24 / PC0, PC1 / PC2 / PC3/ 
/ 20 / IT/ 192.168.20.0/24 / Laptop0/  PC4 / Server0 /

 Router Sub-Interfaces

 Server Setup
- Static IP:`192.168.20.9`
- Services Enabled:
  - DNS  
  - Email  
  Domain:`mail.com`
  Tested communication: in VLAN 10 and VLAN 20 can successfully send and receive mail through the router.

---

 Verification
✅ VLAN segmentation working  
✅ Inter-VLAN routing functional  
✅ Successful ping tests between VLANs  
✅ Email service operational across the network  

---

## 📸 Screenshots
![Network Topology] image attached in the main file

---

## 📂 Files
- [Email_Server_VLAN_Project.pkt](Email_Server_VLAN_Project.pkt)

---

## 🧰 Tools Used
- Cisco Packet Tracer 8.x  
- Basic networking CLI configuration  
- Layer 2 and Layer 3 network design principles  

---

Notes
This project represents my early hands-on implementation of real-world enterprise network design, bridging theory with simulation.  
It marks the start of my journey toward mastering advanced network engineering concepts and server integration.

---

Author:Omollo Hannington 
Email: [omollotonnie@gmail.com](mailto:omollotonnie@gmail.com)  
Date:October 2025  

