# Port-Scanning
Port scanning to detect open ports on a website.
# Nmap Port Scanning – testphp.vulnweb.com

## Project Overview

This project focused on using **Nmap** to detect open ports on the target website `testphp.vulnweb.com`. The aim was to simulate a real-world reconnaissance task by identifying available services running on the host. This hands-on experience helped deepen my understanding of network enumeration and port scanning in ethical hacking practices.

---

## Skills Learned

- Understanding of full TCP port scanning using Nmap.
- Interpretation of port states and services.
- Identification of open HTTP ports for further analysis.
- Introduction to network enumeration as part of penetration testing.

---

## Tools Used

- Nmap for scanning open ports and services.
- testphp.vulnweb.com (provided by Acunetix) as a legal target for security testing.
- Linux terminal environment (Ubuntu) for command-line execution.

---

## Steps

1. **Identify Target**

   Target: `testphp.vulnweb.com`  

2. **Run Full Port Scan**

   Command:
   ```bash
   nmap -p- testphp.vulnweb.com
-p- tells Nmap to scan all 65,535 TCP ports.

---

**Interpret Findings**
- Port 80/tcp is open and running an HTTP service.
- All other ports are closed.
- Port 80 is commonly used for web traffic and is a potential point of further exploration.

