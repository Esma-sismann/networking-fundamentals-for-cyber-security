# networking-fundamentals-for-cyber-security
Comprehensive networking fundamentals documentation focused on TCP/IP, DNS, packet structures, and cybersecurity concepts.
<p align="center">
  <img src="https://img.shields.io/badge/CyberSecurity-Networking-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Intermediate%20%2F%20Advanced-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Focus-TCP%2FIP-success?style=for-the-badge">
</p>

# 🌐 Networking Fundamentals for Cyber Security

Comprehensive networking fundamentals documentation focused on TCP/IP, DNS, packet structures, and cybersecurity concepts.

---

# 📌 Project Overview

This repository contains comprehensive networking fundamentals documentation designed for cybersecurity students, developers, and networking enthusiasts.

The project focuses on the core concepts of computer networking including:

- IP Addressing
- Ports
- DNS
- TCP / UDP
- Packet Structures
- Network Diagnostics
- Traffic Analysis Basics

The goal of this project is to build a strong networking foundation required for cybersecurity, penetration testing, and system administration.

---

# 🎯 Why Networking Matters in Cyber Security

Networking is one of the most critical areas in cybersecurity.

Almost every cyber attack, vulnerability scan, traffic analysis process, or penetration testing activity depends on understanding how networks operate.

Understanding networking concepts allows security professionals to:

- Analyze packets
- Detect malicious traffic
- Understand attacks
- Perform reconnaissance
- Monitor systems
- Analyze connections
- Secure infrastructures

---

# 🌍 1. Internet Protocol (IP)

IP (Internet Protocol) is responsible for addressing and routing packets across networks.

Each device connected to a network has a unique IP address.

Example:

```txt
192.168.1.1
8.8.8.8
172.217.169.14
```

---

## 🔹 IPv4

IPv4 uses a 32-bit address structure.

Example:

```txt
192.168.1.100
```

Supports approximately:

```txt
4.3 billion addresses
```

---

## 🔹 IPv6

IPv6 was developed because IPv4 address space became insufficient.

IPv6 uses 128-bit addressing.

Example:

```txt
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

---

# 🔌 2. Ports

Ports are communication endpoints used by applications and services.

While IP identifies the device, ports identify the application running on that device.

---

## 🔹 Common Ports

| Service | Port |
|---|---|
| HTTP | 80 |
| HTTPS | 443 |
| FTP | 21 |
| SSH | 22 |
| DNS | 53 |

---

# 🌐 3. DNS (Domain Name System)

DNS translates domain names into IP addresses.

Humans use:

```txt
google.com
```

Computers use:

```txt
142.250.190.78
```

DNS acts like the phonebook of the internet.

---

# 🔄 4. TCP (Transmission Control Protocol)

TCP is a reliable communication protocol.

Features:

- Connection-oriented
- Error checking
- Packet ordering
- Reliable delivery

---

## 🔹 TCP Three-Way Handshake

TCP connections are established in three steps:

1. SYN
2. SYN-ACK
3. ACK

This process ensures reliable communication between client and server.

---

# ⚡ 5. UDP (User Datagram Protocol)

UDP is a faster but unreliable protocol.

Features:

- Connectionless
- Low latency
- Faster transmission
- No delivery guarantee

---

## 🔹 UDP Usage Areas

| Usage | Reason |
|---|---|
| Online Games | Low latency |
| Video Streaming | Speed |
| VoIP | Real-time communication |
| DNS | Fast responses |

---

# 📦 6. Packet Structure

Data transferred over networks is divided into small units called packets.

A packet usually contains:

| Field | Description |
|---|---|
| Source IP | Sender address |
| Destination IP | Receiver address |
| Source Port | Sender port |
| Destination Port | Receiver port |
| Payload | Actual data |
| Header | Control information |

---

## 🔹 Packet Flow

1. Data is divided into packets
2. Packets travel across routers
3. Routers forward packets
4. Destination receives packets
5. Packets are reassembled

---

# 🛰️ 7. Ping

Ping is used to test connectivity between devices.

It uses the ICMP protocol.

Example:

```bash
ping google.com
```

Ping measures:

- Connectivity
- Latency
- Packet loss

---

# 🛣️ 8. Traceroute

Traceroute shows the path packets take to reach a destination.

Linux:

```bash
traceroute google.com
```

Windows:

```bash
tracert google.com
```

---

# 🔎 9. Nslookup

Nslookup is used for DNS querying.

Example:

```bash
nslookup google.com
```

Used for:

- DNS troubleshooting
- IP lookup
- Mail server analysis

---

# 🛡️ 10. Networking & Cyber Security

Networking knowledge is essential in cybersecurity because attacks occur over networks.

Security professionals frequently analyze:

- Open ports
- Traffic flows
- Packet contents
- DNS requests
- Network anomalies

---

## 🔹 Common Networking Tools

| Tool | Purpose |
|---|---|
| Wireshark | Packet analysis |
| Nmap | Port scanning |
| Tcpdump | Traffic monitoring |
| Netstat | Connection analysis |

---

# 🧠 Skills Demonstrated

This project demonstrates:

✅ Networking fundamentals  
✅ Technical documentation skills  
✅ Cybersecurity awareness  
✅ TCP/IP understanding  
✅ Network diagnostics knowledge  
✅ Protocol analysis understanding  

---

# 🚀 Future Improvements

Possible future additions:

- Wireshark packet analysis labs
- Nmap scanning examples
- TCP packet breakdowns
- DNS analysis demonstrations
- Linux networking commands
- OSI model visualization

---

# 📚 Conclusion

Networking forms the backbone of modern information systems and cybersecurity operations.

Understanding protocols such as:

- TCP
- UDP
- DNS
- IP

is essential for:

- Penetration testing
- Traffic analysis
- System administration
- Threat detection
- Security monitoring

Strong networking knowledge creates the foundation for advanced cybersecurity expertise.

---

# 👨‍💻 Developer

Developed by Esma Şişman

Cyber Security & Networking Enthusiast
