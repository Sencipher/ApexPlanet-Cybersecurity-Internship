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

---

### 🛠️ Part 4: Technical Tool Familiarization Reference
1. **Wireshark:** Used for deep-packet inspection, live traffic analysis, and parsing frame protocol steps.
2. **Nmap:** Used for network mapping, active host discovery, port scanning, and service version enumeration.
3. **Burp Suite:** Operates as a local HTTP intercepting web proxy tool to fuzz, manipulate, and analyze web applications.
4. **Netcat:** The "Swiss Army knife" of networking; used to open raw TCP/UDP ports, establish shells, and debug connections.
<img width="1366" height="745" alt="Debian 13 x 64-bit - VMware Workstation 7_9_2026 5_41_10 PM" src="https://github.com/user-attachments/assets/1c233eb5-69aa-4bdd-82e1-f237bbe3e351" />
