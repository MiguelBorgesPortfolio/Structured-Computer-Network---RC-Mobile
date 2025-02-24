# Structured Computer Network - RC Mobile

## 📌 About the Project  
This project focuses on designing, configuring, and implementing a **structured computer network** for **RC Mobile**, a company establishing a new headquarters.  
The objective was to develop a **secure, scalable, and high-performance network** with **wired and wireless connectivity**, **VLAN segmentation**, and **remote access capabilities**.

---

## 🛠 Technologies Used  
- **Cisco Packet Tracer** (Network Simulation)  
- **Cisco Routers & Switches** (Network Infrastructure)  
- **Structured Cabling** (Ethernet & Fiber Optics)  
- **IPv4 Subnetting & VLAN Configuration**  
- **DHCP, DNS & HTTP Server Configuration**  
- **SSH & Telnet for Secure Remote Management**  

---

## 📂 Network Design  

### **1️⃣ Physical & Logical Topology**  
✔ **Physical Topology**: Structured cabling with **Ethernet & Fiber Optics**  
✔ **Logical Topology**: Hierarchical design with **VLAN segmentation**  
✔ **Interconnection**: Links between **Headquarters, Warehouse, and Branch Office**  

### **2️⃣ VLAN Configuration**  
✔ **Segmentation of network traffic** into dedicated VLANs:  
   - **Employee VLANs** (based on department roles)  
   - **Guest & Internal WiFi VLANs**  
   - **Printer & VoIP VLANs**  
   - **Management VLAN for network devices**  
   - **Vending Machine VLAN**  

### **3️⃣ IP Addressing Scheme**  
✔ **IPv4 Subnetting** to allocate efficient IP ranges for each VLAN:  
   - **192.168.10.0/24** → Headquarters  
   - **192.168.20.0/24** → Branch Office  
   - **192.168.60.0/24** → Warehouse  
   - **Dedicated subnets** for interconnecting routers  

### **4️⃣ Network Services & Security**  
✔ **DHCP Server**: Automatic IP assignment for devices  
✔ **DNS & HTTP Server**: Internal domain resolution & company website hosting  
✔ **SSH & Telnet**: Secure remote access for network management  
✔ **Access Control Lists (ACLs)**: Restrict communication between certain VLANs  
✔ **Network Address Translation (NAT)**: For external internet access  

---

## 📡 WiFi Coverage  
✔ **Enterprise-grade WiFi deployment** using **Meraki MX65W** for full coverage  
✔ **Separate SSIDs for Guests & Employees**  
✔ **Security measures** to prevent unauthorized access  

---

## 🎨 Network Diagram  

### **Physical Network Layout**  
![Physical Topology](https://github.com/user-attachments/assets/e21888f2-035e-4fb4-acfc-52d5594dd5a0)

### **Legend**  
🔴 **Network Outlets**  
🟡 **Cable Trays**  
🔵 **Cable Ducts**  
🟢 **Server Rack**  
🟡 **Access Point**  
🟣 **Wireless Coverage**  

--- 

### **Logical Network Design**  
![Logical Topology](https://github.com/user-attachments/assets/afc250db-9663-444b-8b71-ee210874a1a1)



