# Hi, I'm Yustinus Hendi Setyawan 

### Cybersecurity Researcher | Computer Science Undergraduate @ Diponegoro University

Aspiring Chief Information Security Officer (CISO) specializing in Malware Analysis, Reverse Engineering, Low-Level Defense Architecture, and Offensive Security Automation. 

My core research revolves around engineering proactive defense mechanisms, identifying sophisticated threat vectors through malicious event detection, and developing robust Breach and Attack Simulation (BAS) frameworks to emulate real-world adversarial tactics. I am passionate about bridging the gap between offensive operations and defensive engineering.

---

### Core Competencies & Tech Stack
<p align="left">
  <a href="https://www.python.org" target="blank">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python"/>
  </a>
  <a href="https://en.wikipedia.org/wiki/C_(programming_language)" target="blank">
    <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="c"/>
  </a>
  <a href="https://www.kali.org/" target="blank">
    <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="kali"/>
  </a>
  <a href="https://wazuh.com/" target="blank">
    <img src="https://img.shields.io/badge/Wazuh-00B0FF?style=for-the-badge&logo=wazuh&logoColor=white" alt="wazuh"/>
  </a>
  <a href="https://ghidra-sre.org/" target="blank">
    <img src="https://img.shields.io/badge/Ghidra-DF0000?style=for-the-badge&logo=ghidra&logoColor=white" alt="ghidra"/>
  </a>
  <a href="https://nmap.org/" target="blank">
    <img src="https://img.shields.io/badge/Nmap-000000?style=for-the-badge&logo=nmap&logoColor=white" alt="nmap"/>
  </a>
  <a href="https://www.wireshark.org/" target="blank">
    <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="wireshark"/>
  </a>
  <a href="https://flask.palletsprojects.com/" target="blank">
    <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="flask"/>
  </a>
  <a href="https://www.docker.com/" target="blank">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="docker"/>
  </a>
  <a href="https://git-scm.com/" target="blank">
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="git"/>
  </a>
  <a href="https://code.visualstudio.com/" target="blank">
    <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="vscode"/>
  </a>
  <a href="https://www.gnu.org/software/bash/" target="blank">
    <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="bash"/>
  </a>
</p>

<br/>

## Featured Engineering & Research

| Architecture/Tool | Security Domain | Technical Description |
| :--- | :--- | :--- |
| **[Purple-Team-BAS](https://github.com/uusrajaminyak/Windows-11/tree/main/BAS)** | Adversary Emulation | Engineered a Python-driven Breach & Attack Simulation framework aligned with the **MITRE ATT&CK** matrix. Automates Discovery, Exfiltration, and Persistence tactics to validate and tune SIEM/EDR detection rulesets. |
| **[PyWAF](https://github.com/uusrajaminyak/Windows-11/tree/main/PyWAF)** | Application Security | Developed a custom Layer 7 Web Application Firewall acting as a reverse proxy. Utilizes complex Regex pattern matching to intercept and neutralize OWASP Top 10 vulnerabilities (SQLi, XSS, LFI) in real-time. |
| **[Malware Unpacker](https://github.com/uusrajaminyak/Kali-Linux/tree/main/Malware_Unpacker)** | Reverse Engineering | Architected an automated dynamic analysis pipeline leveraging the **Qiling Framework** to heuristically detect Original Entry Points (OEP) and extract payloads from UPX-obfuscated binaries. |
| **[Symbolic De-virtualizer](https://github.com/uusrajaminyak/Kali-Linux/tree/main/De-virtualization%20%26%20Symbolic%20Execution%20Tool)** | Binary Analysis | Implemented a sophisticated de-obfuscation pipeline utilizing **Triton** and **Z3 Theorem Prover** to simplify heavily virtualized execution paths and resolve complex logic constraints. |
| **[eBPF EDR](https://github.com/uusrajaminyak/Kali-Linux/tree/main/eBPF_EDR)** | Kernel-Level Security | Prototyped an experimental Endpoint Detection & Response (EDR) sensor leveraging **eBPF** (Extended Berkeley Packet Filter) to trace system calls and identify kernel-level rootkits with minimal performance overhead. |
| **[Process Integrity Scanner](https://github.com/uusrajaminyak/Kali-Linux/tree/main/Process%20Integrity%20Scanner)** | Memory Forensics | Engineered a user-space memory forensics utility to actively scan executing processes, detecting malicious code injection and API hooking techniques. |

<br/>

## Security Arsenal

### 🔴 Offensive Security (Red Team)
| Project | Description |
| :--- | :--- |
| **[Keylogger](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Malware-Analysis/Keylogger_Lab)** | Developed a stealthy user-mode keystroke logger to study heuristic evasion and behavioral analysis. |
| **[Ransomware Simulator](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Malware-Analysis/Lab_Ransomware)** | Built a cryptographic ransomware emulator demonstrating asymmetric/symmetric file encryption mechanics for educational environments. |
| **[API Fuzzer](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Offensive-Tools/API_Fuzzer)** | Scripted a Dynamic Application Security Testing (DAST) utility to fuzz REST API endpoints, identifying edge-case crashes and unhandled exceptions. |
| **[Web Auditor](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Offensive-Tools/Web_Auditor)** | Created an automated vulnerability scanner targeting common web infrastructure misconfigurations. |

### 🔵 Defensive Security (Blue Team)
| Project | Description |
| :--- | :--- |
| **[Mini SOC](https://github.com/uusrajaminyak/Cybersecurity/tree/main/Mini_SOC/wazuh-docker)** | Architected a containerized Security Operations Center (SOC) deploying Wazuh SIEM integrated with Sysmon telemetry for proactive threat hunting. |
| **[Simple FIM](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Defensive-Tools/Simple_FIM)** | Implemented a File Integrity Monitoring (FIM) daemon utilizing SHA-256 cryptographic hashing to baseline and alert on unauthorized filesystem modifications. |
| **[IR Triage](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Forensics/IR_Triage)** | Scripted a Digital Forensics and Incident Response (DFIR) artifact collector to acquire volatile memory states and network connections from compromised hosts. |
| **[Stego Lab](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Cryptography)** | Conducted research on steganographic payload delivery via Least Significant Bit (LSB) manipulation in multimedia files. |
| **[Secure Chat](https://github.com/uusrajaminyak/CybersecurityArsenal/tree/main/Cryptography)** | Developed a secure communication protocol implementing End-to-End Encryption (E2EE) principles. |

<br/>

### GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=uusrajaminyak&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
  &nbsp;&nbsp;&nbsp;
  <img src="https://streak-stats.demolab.com?user=uusrajaminyak&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" height="150" alt="streak graph"  />
</div>

### Certifications & Affiliations

[![ISC2 Candidate](https://images.credly.com/size/220x220/images/9180921d-4a13-429e-9357-6f9706a554f0/image.png)](https://www.credly.com/badges/41aba984-8093-4d1a-9ddd-f1aff6e9ff9d/public_url)

---
<p align="center">
  <i>"Securing the future, one byte at a time."</i><br>
  <b>Yustinus Hendi Setyawan</b>
</p>
