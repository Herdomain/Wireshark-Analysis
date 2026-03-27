# 🌐 Network Analysis with Wireshark & Nmap

## 📌 Overview
In this project, I explored how network traffic and system information can be analyzed using Wireshark and Nmap.

My goal was to understand how much information can be gathered from a network and why monitoring and securing that information is important.

---

## ⚙️ What I Did

I used two main tools:

- **Wireshark** to capture and analyze live network traffic  
- **Nmap** to scan the network and identify devices, open ports, and services  

By combining these tools, I was able to:
- Identify devices on the network  
- Observe how they communicate  
- Understand potential security risks  

---

## 🧪 Environment Setup

I set up three virtual machines:

- Windows Server  
- Linux Server (Ubuntu)  
- Kali Linux (used for scanning and monitoring)  

All scans and traffic captures were performed from the Kali machine.

---

## 🖼️ Sample Observations

🔹 TCP Handshake (Wireshark)
![TCP Handshake](https://github.com/Herdomain/Network-Administration/blob/main/images/tcp_handshake.jpg)
Fig 1.1. This capture shows a successful TCP 3-way handshake between two devices, confirming active communication over port 80.

---
🔹 Packet Details (MAC Address Identification)
![Packet Details](https://github.com/Herdomain/Network-Administration/blob/main/images/packet_details.jpg)
Fig 1.2. From this packet, I was able to identify both source and destination MAC addresses and confirm communication between devices.

---

🔹 TCP Stream Analysis
![TCP Stream](https://github.com/Herdomain/Network-Administration/blob/main/images/tcp_stream.jpg)

Fig. 1.3. This stream shows HTTP communication and confirms the server is running on port 80 (Ubuntu).

---

- Cross-verification between Nmap results and Wireshark captures  

## 📊 Key Findings

Through this analysis, I:

- Identified multiple active devices on the network  
- Discovered open ports such as:
  - **80 (HTTP)**  
  - **21 (FTP)**  
  - **3306 (MySQL)**  
- Observed real communication between devices using TCP handshakes  
- Matched Nmap scan results with Wireshark packet data  
- Confirmed how much system and network information can be exposed during scans  

---

## 🎯 Why This Matters

This project helped me understand that:

- Even a basic network scan can reveal detailed system information  
- Open ports can expose services that may be vulnerable  
- Network traffic contains valuable insights into system behavior  
- Using multiple tools together provides better visibility than using one alone  

---

## 🔐 Security Value

This project demonstrates my ability to:

- Discover devices and services on a network  
- Analyze real network traffic  
- Identify potential exposure points  
- Validate findings across multiple tools  
- Build a stronger understanding of network security fundamentals  

---

## 📄 Full Report

See the full detailed analysis and screenshots here:   
👉 [View Full Report](https://docs.google.com/document/d/1FKf9LDBcs-WIxNXnED4KflNUIGKqHZ7Cfl-1yNpHu9s/edit?usp=sharing)





