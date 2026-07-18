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
* **IP Addressing:** Logical identifiers assigned to network interfaces (e.g., `192.168.75.x`).
* **Subnetting:** Segmenting networks using masks (e.g., `255.255.255.0`) to manage routing boundaries.
* **NAT vs. Host-Only:** Deployed Host-Only topology to sandbox traffic and isolate the target from the internet.
* **OSI vs. TCP/IP:** Frameworks standardizing communication across theoretical (7-layer) and practical (4-layer) models.
* **TCP/IP Suite:** Data delivery protocols focusing on TCP (reliable, connection-oriented) and UDP (fast, connectionless).
* **DNS:** Resolves human-readable domain names into machine-routable IP addresses.
* **HTTP vs. HTTPS:** Compares cleartext web transfer (HTTP) against securely encrypted transfer (HTTPS via SSL/TLS).

### Part 5: Cryptography Basics
* **Symmetric vs. Asymmetric:** Single shared keys for speed vs. public/private key pairs for secure distribution.
* **Hashing:** One-way functions like MD5 (legacy checksums) and SHA-256 (modern standard) used to verify data integrity.
* **Certificates & SSL/TLS:** Domain identity verification via Certificate Authorities to establish encrypted HTTPS tunnels.
* **Hands-on Execution:** Utilizing native `openssl` terminal utilities to handle data encryption and decryption.
*
---
### 🛠️ Part 6: Technical Tool Familiarization Reference
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
