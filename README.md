# ApexPlanet Cybersecurity & Ethical Hacking Internship

Documentation, notes, and lab reports completed during my 60-day internship program at ApexPlanet Software Pvt. Ltd.

---

## 📋 Task-1: Foundations of Cybersecurity & Lab Setup

### 🛡️ Part 1: Cybersecurity Basics (Core Concepts)
*   **CIA Triad:** 
    *   **Confidentiality:** Ensuring data is accessible only to authorized individuals.
    *   **Integrity:** Maintaining and assuring the accuracy and completeness of data over its entire life-cycle.
    *   **Availability:** Ensuring reliable and timely access to data and resources for authorized users.
*   **Common Threat Vectors Monitored:** Phishing, Malware, DDoS, SQL Injection, Brute Force, and Ransomware.

---

### 💻 Part 2: Lab Environment Setup Report
*   **Hypervisor:** VMware Workstation
*   **Attacker Machine:** Kali Linux (Debian 13.x 64-bit) 
*   **Target Machine:** Metasploitable2
*   **Network Configuration:** Isolated Host-Only Private Lab Network (`VMnet1`)

#### Network Verification:
*   **Kali Linux IP Address:** `192.168.75.128`
*   **Metasploitable2 IP Address:** `192.168.75.129`
*   **Connectivity Confirmation:** A network ping successfully established a connection across the isolated virtual layout, establishing an active testing bridge.

---

### 🐧 Part 3: Linux Fundamentals Cheat-Sheet

| Command | Purpose | Example Usage |
| :--- | :--- | :--- |
| `pwd` | Print Working Directory (Shows current path) | `pwd` |
| `ls` | List directory contents | `ls -la` (Shows hidden files + details) |
| `cd` | Change directory navigation | `cd /var/www/html` |
| `chmod`| Modify file/folder read/write/execute permissions | `chmod 755 script.sh` |
| `chown`| Change file owner and group ownership | `sudo chown root:root file.txt` |
| `apt` | Package management tool for installation/updates| `sudo apt update && sudo apt install curl` |
| `ifconfig`| Displays active network interfaces and IP addresses | `ifconfig` |
| `ping` | Tests network connectivity to a target host | `ping 192.168.75.129` |
| `netstat`| Shows network connections, routing tables, interface stats| `netstat -antp` |

### Part 4: Networking Basics
*1.   **IP Addressing:** Managed the assignment of unique logical identifiers within our private Class C lab subnet (`192.168.75.x`) to isolate host nodes.
*2.   **Subnetting:** Utilized a standard `/24` subnet mask (`255.255.255.0`) to define network routing boundaries and organize our host addresses efficiently.
*3.   **NAT vs. Host-Only:** Configured a strict **Host-Only** switch topology to sever external internet access, ensuring all target traffic remains safely sandboxed inside the hypervisor.
*4.   **OSI Model vs. TCP/IP Suite:** Analyzed the structural frameworks used to standardize network communications, mapping the theoretical 7-layer OSI model (Physical to Application) directly to the practical 4-layer TCP/IP stack (Network Access, Internet, Transport, Application).
*5.   **TCP/IP Protocol Suite:** Studied how foundational protocols handle data delivery, focusing on **TCP** (a connection-oriented protocol that ensures reliable, ordered data delivery via a 3-way handshake) and **UDP** (a connectionless, fast protocol used for real-time traffic).
*6.   **DNS (Domain Name System):** Explored the decentralized naming system that acts as the "phonebook of the internet," resolving human-readable domain names into machine-routable IP addresses.
*7.   **HTTP vs. HTTPS:** Evaluated the protocols governing web data transfer, contrasting **HTTP** (cleartext, vulnerable to eavesdropping and tampering) with **HTTPS** (secured via SSL/TLS encryption to ensure data confidentiality and integrity).

### Part 5: Cryptography Basics
*1.   **Symmetric vs. Asymmetric:** Analyzed the structural differences between using a single shared secret key (Symmetric) for speed versus mathematically linked public/private key pairs (Asymmetric) for secure key distribution.
*2.   **Hashing Algorithms:** Evaluated one-way mathematical functions like MD5 (legacy checksums) and SHA-256 (modern industry standard) used to verify data integrity by generating unique signatures.
*3.   **Digital Certificates & SSL/TLS:** Explored how trusted Certificate Authorities (CAs) validate public key ownership and how the SSL/TLS handshake protocol establishes secure, encrypted HTTPS tunnels over public networks.
*4.   **Hands-on Execution:** Implemented native **OpenSSL** terminal commands to practically execute file encryption, decryption, and hash verification operations.
*
---
### 🛠️ Part 4: Technical Tool Familiarization Reference
1. **Wireshark:** Used for deep-packet inspection, live traffic analysis, and parsing frame protocol steps.
2. **Nmap:** Used for network mapping, active host discovery, port scanning, and service version enumeration.
3. **Burp Suite:** Operates as a local HTTP intercepting web proxy tool to fuzz, manipulate, and analyze web applications.
4. **Netcat:** The "Swiss Army knife" of networking; used to open raw TCP/UDP ports, establish shells, and debug connections.

-> screenshort of  Metasploitable
<img width="1366" height="745" alt="Debian 13 x 64-bit - VMware Workstation 7_9_2026 5_41_10 PM" src="https://github.com/user-attachments/assets/1c233eb5-69aa-4bdd-82e1-f237bbe3e351" />

-> Screenshort of Kali linux
<img width="1366" height="745" alt="Debian 13 x 64-bit - VMware Workstation 7_9_2026 5_54_07 PM" src="https://github.com/user-attachments/assets/d8c67c5a-9c9e-4cac-9b43-51fee8805041" />

-> Screenshort of Wireshark
<img width="1366" height="745" alt="Debian 13 x 64-bit - VMware Workstation 7_9_2026 5_58_08 PM" src="https://github.com/user-attachments/assets/3a8780dd-37b1-4c2d-9c7e-153d02908bba" />
