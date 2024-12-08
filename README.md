
# Building a Comprehensive Office Network Using Cisco Packet Tracer

## **Course Information**
- **Course Name:** Computer Networks  
- **Course Code:** CSE – 312  
- **Batch:** D – 68  
- **Group Members:**  
  - Roll 01  
  - Roll 03  
  - Roll 09  
  - Roll 45  

---

## **Project Overview**
This project involves designing a professional-grade office network for a simulated environment with 40 PCs distributed across four departments: HR, IT, Sales, and Marketing. Using **Cisco Packet Tracer**, the network is structured with VLANs, inter-VLAN routing, and essential security features, ensuring a functional, secure, and scalable design.

---

## **Project Objectives**
1. **Design a structured network:**  
   - Divide the office into four VLANs for logical segmentation.  
   - Assign specific subnets to each department.  

2. **Enable inter-department communication:**  
   - Use inter-VLAN routing with a Layer 3 switch.  

3. **Provide internet connectivity:**  
   - Connect the internal network to external systems using a router.  

4. **Implement security measures:**  
   - Restrict unauthorized access with ACLs and use secure management protocols like SSH.  

5. **Test the network design:**  
   - Validate the functionality and scalability of the network through simulations.

---

## **Network Design**
1. **VLAN Configuration:**
   - HR: VLAN 10 (192.168.10.0/24)  
   - IT: VLAN 20 (192.168.40.0/24)  
   - Sales: VLAN 30 (192.168.70.0/24)  
   - Marketing: VLAN 40 (192.168.100.0/24)  

2. **Network Components:**
   - **Hardware (Simulated):**
     - 40 PCs (10 per department)  
     - Layer 2 switches (1 per department)  
     - Layer 3 switch for inter-VLAN routing  
     - Router for internet access  
     - Optional: Server for shared resources and firewall for added security  
   - **Software:** Cisco Packet Tracer  

3. **Topology:** Star topology with a central Layer 3 switch connecting to department Layer 2 switches and a router for internet access.

---

## **Setup Instructions**
1. **Network Design and Implementation:**
   - Connect PCs to Layer 2 switches for each department.  
   - Link Layer 2 switches to the central Layer 3 switch.  
   - Connect the Layer 3 switch to the router for external access.  

2. **Configuration:**
   - Assign VLANs to ports on Layer 2 switches based on department.  
   - Configure inter-VLAN routing on the Layer 3 switch.  
   - Assign IP addresses to devices based on the VLAN subnet scheme.  
   - Enable security features like ACLs and SSH on switches and the router.  

3. **Testing and Validation:**
   - Test connectivity within and across VLANs.  
   - Verify ACL rules to restrict unauthorized access.  
   - Simulate external access using the router.

---

## **Testing Steps**
1. **Ping Test:**  
   - Ping between devices within the same VLAN.  
   - Ping across VLANs to validate inter-VLAN routing.  

2. **Security Test:**  
   - Ensure ACLs block traffic from unauthorized devices.  
   - Test SSH connectivity to manage devices securely.  

3. **Internet Access Test:**  
   - Simulate internet connectivity via the router.  

---

## **Results**
- A functional, scalable office network with VLAN segmentation and inter-VLAN communication.  
- Basic security measures implemented to protect the network.  
- Successful testing of connectivity and security features in Cisco Packet Tracer.  

---

## **Future Enhancements**
1. Add advanced security features like firewalls and intrusion detection systems (IDS).  
2. Implement Quality of Service (QoS) for traffic prioritization.  
3. Extend the design to include wireless networks for mobile devices.  

---

## **References**
- Cisco Networking Academy. (2024). *Introduction to Packet Tracer*.  
- Cisco Networking Academy. *Introduction to VLANs and Inter-VLAN Routing*.  
- Tanenbaum, A. S., & Wetherall, D. J. (2020). *Computer Networks (6th ed.)*. Pearson.  
- Cisco Systems Official Website: [https://www.cisco.com](https://www.cisco.com)  

---

## **Authors**
This project was completed by Group D-68, Batch CSE-312.  
Group Members: Roll 01, 03, 09, 45  
