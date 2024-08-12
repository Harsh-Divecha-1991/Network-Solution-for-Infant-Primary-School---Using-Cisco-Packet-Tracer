# 🏫 Network Solution for Infant Primary School

## 📑 Table of Contents
1. [Introduction](#introduction)
2. [Network Diagram](#network-diagram)
3. [Equipment Selection and Justification](#equipment-selection-and-justification)
4. [Physical Topology](#physical-topology)
5. [Wireless Technologies and Setup](#wireless-technologies-and-setup)
6. [Network Security and Robustness](#network-security-and-robustness)
7. [Future Recommendations](#future-recommendations)
8. [Conclusion](#conclusion)
9. [References](#references)

---

## 📖 Introduction
This README file provides a comprehensive overview of the network solution designed for an infant primary school that has moved into a new building. The solution includes both the technical and practical aspects of designing a network that meets the school's needs while adhering to a budget constraint of £40,000.

---

## 🖼️ Network Diagram
A visual representation of the network design is crucial for understanding the layout and connectivity of the network components. The network diagram is created using Cisco Packet Tracer to simulate basic network operations.

![Full Diagram](https://github.com/user-attachments/assets/8f834ead-172f-4423-8fdf-ee034a41d842)

## 🛠️ Equipment Selection and Justification
### Routers and Switches
- **Model:** Cisco ISR 4000 Series Router
  - **Justification:** Provides high-performance routing and supports both wired and wireless devices.
- **Model:** Cisco Catalyst 2960 Series Switches
  - **Justification:** Offers scalability and reliability for classroom and office connectivity.

### Wireless Access Points
- **Model:** Cisco Aironet 2800 Series
  - **Justification:** Delivers comprehensive wireless coverage throughout the building, supporting multiple devices and users.

### Cables
- **Type:** Cat6 Ethernet Cables
  - **Justification:** Supports high-speed data transfer, essential for seamless connectivity across all networked devices.

### Other Equipment
- **Firewall:** Cisco ASA 5506-X
  - **Justification:** Ensures network security by monitoring and controlling incoming and outgoing network traffic.

---

## 🔗 Physical Topology
- **Choice:** Star Topology
- **Justification:** Offers ease of scalability and network management. In case of a failure in one of the nodes, the rest of the network remains unaffected, ensuring reliability.

---

## 📶 Wireless Technologies and Setup
- **Wireless Technology:** Wi-Fi 6 (802.11ax)
  - **Justification:** Provides high-speed connectivity and can handle a large number of concurrent connections, essential for a school environment with multiple devices.
- **Setup:** Configured to allow staff access throughout the building with secured SSIDs and appropriate access controls.

---

## 🔒 Network Security and Robustness
### Network Segmentation
- Dividing the network into segments based on the type of users and devices to minimize the impact of security breaches.

### Access Control Lists (ACLs)
- Implementing ACLs to restrict access to certain parts of the network based on predefined criteria.

### Wireless Security
- Utilizing WPA3 encryption for wireless networks to protect data and user privacy.

---

## 🚀 Future Recommendations
1. **Scalability:**
   - Consider implementing a cloud-based management system for easier scalability and centralized management.
2. **Integration of IoT Devices:**
   - Prepare for the integration of IoT devices such as smart lighting and thermostats to improve energy efficiency.

---

## 📝 Conclusion
The network solution presented provides a comprehensive and scalable design for the infant primary school, addressing current needs and future expansion possibilities. By adhering to budget constraints and using high-quality equipment, the network ensures reliability, security, and efficiency.

---

## 📚 References
- [Cisco ISR 4000 Series](https://www.cisco.com/c/en/us/products/routers/4000-series-integrated-services-routers-isr/index.html)
- [Cisco Catalyst 2960 Series Switches](https://www.cisco.com/c/en/us/products/switches/catalyst-2960-series-switches/index.html)
- [Cisco Aironet 2800 Series](https://www.cisco.com/c/en/us/products/wireless/aironet-2800-series-access-points/index.html)
- [Cat6 Ethernet Cables Specifications](https://www.cablematters.com/blog/Networking/what-is-cat6-ethernet-cable)
- [Cisco ASA 5506-X](https://www.cisco.com/c/en/us/products/security/asa-5506-x-firewall/index.html)
