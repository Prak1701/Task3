Task 3: Basic Vulnerability Scan using Nessus Essentials

Objective - 
The goal of this task is to perform a basic vulnerability assessment on a personal computer using **Nessus Essentials**, a free vulnerability scanner from Tenable. This helps in understanding potential security weaknesses and risks in the system.

Tools Used
- **Operating System:** Kali Linux 2024.4 (running on VMware)
- **Scanner:** Nessus Essentials
- **Scanner Type:** Local Scanner
- **CVSS Base:** Version 3.0

Steps Performed

1. Installed Nessus Essentials on Kali Linux.
2. Enabled the Nessus service using:
   ```bash
   sudo systemctl start nessusd
   sudo systemctl status nessusd
3. Accessed the Nessus web interface via: `https://localhost:8834`.
4. Configured a **Basic Network Scan** targeting the local IP `192.168.108.130`.
5. Started the scan and waited for the results (took about 8 minutes).
6. Collected screenshots and analyzed the vulnerability report.

Key Observations

- Multiple high-risk vulnerabilities were found.
- Critical issues could allow remote access, data leakage, or privilege escalation.
- Recommended actions include:
  - Apply available security patches.
  - Disable unnecessary services and ports.
  - Regularly update the system.
  - Configure firewall rules effectively.

Outputs -

