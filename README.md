# NETWORKWALKS-Sulafa-B084-Cybersecurity-Internship-Wireshark
# Cybersecurity Internship: Wireshark SOC Labs

## 📌 About This Repository
This repository serves as a practical learning documenting my hands-on network analysis and packet inspection exercises completed during the **Cybersecurity Internship at NETWORKWALKS (Batch B084)**. 

The objective of this repository is to demonstrate the practical knowledge and analytical skills I am developing. It reflects my real-world learning journey in strengthening cybersecurity fundamentals.

*Note: This repository is a personal learning documenting my educational journey. It is not an independent professional project. The exercises are based on training scenarios provided during the internship.*

## 🎯 Learning Objectives
- Perform Deep Packet Inspection (DPI) to identify network anomalies and data leaks.
- Detect and analyze common network attacks (Port Scans, Brute Force).
- Extract and reconstruct plaintext data from unencrypted protocols (HTTP, FTP).
- Analyze VoIP signaling and media traffic (SIP, RTP) for security vulnerabilities.
- Translate raw network packets into actionable Security Operations Center (SOC) findings.

## 🛠️ Tools & Technologies
- **Network Protocol Analyzer:** Wireshark
- **Protocols Analyzed:** TCP, IP, HTTP, FTP, SIP, RTP
- **Techniques:** TCP Stream, Filter Syntax, Payload Extraction

## 📂 Laboratory Exercises (Table of Contents)

| Lab | Title | Core SOC Skill Demonstrated |
| :--- | :--- | :--- |
| **Lab 1** | [Identify the Attacker IP](./Lab-01-Identify-Attacker-IP) | Detecting TCP SYN Port Scans & mapping attacker scope. |
| **Lab 2** | [Follow TCP Stream](./Lab-02-Follow-TCP-Stream) | Reconstructing unencrypted legacy chat streams to find leaked passwords. |
| **Lab 3** | [Follow TCP Stream Part 2](./Lab-03-Follow-TCP-Stream-Part2) | Deep Packet Inspection of HTTP to find hidden HTML data and file downloads. |
| **Lab 4** | [HTTP Plaintext Credentials](./Lab-04-HTTP-Plaintext-Credentials) | Intercepting unencrypted HTTP POST authentication payloads. |
| **Lab 5** | [Brute Force Catch](./Lab-05-Brute-Force-Catch) | Identifying FTP Brute-Force attacks and compromised credentials. |
| **Lab 6** | [VoIP Call Replay](./Lab-06-VoIP-Call-Replay) | Replaying unencrypted SIP/RTP voice calls. |

## 🚀 Skills Developed for SOC L1
- **Incident Triage:** Ability to quickly filter large PCAPs to isolate malicious or suspicious traffic.
- **Protocol Vulnerability Awareness:** Practical understanding of why legacy protocols (HTTP, FTP, SIP, RTP) present severe security risks.
- **Evidence Gathering:** Documenting technical findings clearly using screenshots and specific packet details.
- **Remediation Strategy:** Proposing immediate fixes (e.g., implementing HTTPS, SRTP, SFTP) to mitigate identified vulnerabilities.


# 👤 Author

**Sulafa Abdulrahman**\
SOC Analyst L1

LinkedIn: https://www.linkedin.com/in/sulafa-abdulrahman



## 📌 Repository Information

**Program Name:** Cybersecurity at Networkwalks | **Week:** 01 | **Project:** Wireshark SOC Labs  | **Repository:** GitHub
