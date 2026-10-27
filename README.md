<div align="center">

# 🛡️ Cyberster Blue Team Internship

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Role](https://img.shields.io/badge/Focus-Blue%20Team%20%26%20DFIR-0A66C2?style=for-the-badge)](#)
[![SIEM](https://img.shields.io/badge/SIEM-Wazuh-00A9E0?style=for-the-badge)](#)
[![IDS/Firewall](https://img.shields.io/badge/Network-Suricata%20%7C%20pfSense-FF6C37?style=for-the-badge)](#)
[![Forensics](https://img.shields.io/badge/DFIR-Autopsy%20%7C%20Wireshark-4EAA25?style=for-the-badge)](#)

*A comprehensive portfolio of defensive security operations, threat detection engineering, digital forensics, and incident response.*

</div>

---

## 📌 Overview
This repository documents my hands-on work, technical reports, and lab artifacts completed during the **Cyberster Blue Team Internship**. Throughout this intensive 12-week program, I focused on enterprise security operations (SOC), network defense, endpoint monitoring, digital forensics, and incident response (DFIR).

---

## 🏆 Awards & Certifications
Upon successfully completing the 12-week technical curriculum and the capstone forensic investigation, I was awarded the **Certificate of Completion** and **Letter of Experience** by Cyberster.

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Certificate of Completion</b></td>
      <td align="center"><b>Letter of Experience</b></td>
    </tr>
    <tr>
      <td><img src="awards/certificate%20of%20completion.jpg" alt="Certificate of Completion" width="420"/></td>
      <td><img src="awards/letter%20of%20experience.jpg" alt="Letter of Experience" width="420"/></td>
    </tr>
  </table>
</div>

---

## 🗓️ 12-Week Curriculum Breakdown

| Week | Module / Focus Area | Key Activities & Deliverables |
| :--- | :--- | :--- |
| **Week 1** | **SOC Foundations & Lab Setup** | Network topology design, multi-VM lab deployment (Kali, Ubuntu, Windows), packet analysis (Wireshark), Wazuh SIEM deployment, and initial ransomware/brute-force telemetry testing. |
| **Week 2** | **Detection, Custom Rules & Log Analysis** | File Integrity Monitoring (FIM), custom XML rule authoring in Wazuh, Windows Event ID tracking (`4625`, `4672`, `4720`), USB detection, and automated active response (`iptables`). |
| **Week 3** | **Suricata IDS Integration With Wazuh** | Suricata IDS deployment, custom NIDS rules (ICMP flood, Nmap scan, HTTP exploit), `eve.json` log integration with Wazuh, DNS sinkholing, and `ipset` blocklisting. |
| **Week 4** | **pfSense Firewall & Advanced Monitoring** | Enterprise firewall configuration, network segmentation, rule enforcement, and advanced traffic monitoring. |
| **Week 5** | **Malware Analysis & Incident Response** | Static and dynamic malware analysis, behavioral triaging, containment strategies, and incident response reporting. |
| **Week 6** | **Insider Threat Simulation & IR** | Simulating privileged abuse and data staging, building detection logic for anomalous user behavior, and executing IR playbooks. |
| **Week 7** | **Digital Forensics Foundations** | Forensic disk imaging, maintaining chain of custody, file system analysis, and foundational evidence recovery. |
| **Week 8** | **Host Forensics & Recovery Analysis** | Deep-dive analysis of Windows Event Logs, Prefetch files, system cache, and deleted artifact recovery. |
| **Week 9** | **Advanced Browser & Artifact Forensics** | Browser history/cache forensics, `Shell/LNK` file analysis, jump lists, and cross-artifact correlation. |
| **Week 10** | **Autopsy Triage & Timeline Reconstruction** | Full case management using Autopsy (*Mantooth Case*), automated artifact hunting, and chronological timeline reconstruction. |
| **Week 11** | **Email Forensics & Super Timelines** | Phishing/email header forensics, attachment analysis (*Jean Disk Image*), and generating comprehensive super timelines. |
| **Week 12** | **M57.biz Capstone Project** | Full-scale disk, memory, and data exfiltration forensic investigation. |

---

## 📂 Repository Structure
> **Note:** Folders are organized chronologically below. The `Screenshots/` directories in Weeks 1–3 contain **120+ lab verification `.png` captures** (covering Wireshark packet captures, Wazuh alerts, Suricata logs, and configuration proofs), which have been summarized in the tree to maintain readability.

```text
Cyberster-Blue-Team-Internship/
│
├── awards/
│   ├── certificate of completion.jpg
│   └── letter of experience.jpg
│
├── Week 1/
│   ├── Screenshots/          → [52 PNGs] Network topology, Wireshark, Wazuh setup & attack telemetry
│   ├── Cyberster Week1 Task.docx
│   ├── SOC Foundations and Lab Setup.docx
│   └── SOC Foundations and Lab Setup.pdf
│
├── Week 2/
│   ├── Screenshots/          → [33 PNGs] FIM setup, custom XML rules, Windows Event IDs & Active Response
│   ├── Cyberster Week 2.docx
│   ├── Detection, Custom Rules, and Log Analysis.docx
│   └── Detection, Custom Rules, and Log Analysis.pdf
│
├── Week 3/
│   ├── Screenshots/          → [43 PNGs] Suricata IDS setup, custom rules, Wazuh integration & DNS sinkholing
│   ├── Cyberster Week3.docx
│   ├── Suricata IDS Integration With Wazuh.docx
│   └── Suricata IDS Integration With Wazuh.pdf
│
├── Week 4/
│   ├── Cyberster Week4.docx
│   ├── Cyberster Week4.pptx
│   ├── pfSense Firewall and Advanced Monitoring.docx
│   └── pfSense Firewall and Advanced Monitoring.pdf
│
├── Week 5/
│   ├── Cyberster Week5.docx
│   ├── Malware Analysis and Incident Response.docx
│   └── Malware Analysis and Incident Response.pdf
│
├── Week 6/
│   ├── Insider Threat Simulation and Incident Response.docx
│   ├── Insider Threat Simulation and Incident Response.pdf
│   └── Week 6.docx
│
├── Week 7/
│   ├── Digital Forensics Foundations Disk Imaging, File Systems, and Evidence Analysis.docx
│   ├── Digital Forensics Foundations Disk Imaging, File Systems, and Evidence Analysis.pdf
│   ├── Week 7.docx
│   └── Week 7.pptx
│
├── Week 8/
│   ├── Event Logs, Prefetch, Cache, and Recovery Analysis.docx
│   ├── Event Logs, Prefetch, Cache, and Recovery Analysis.pdf
│   ├── Week 8.docx
│   └── Week 8.pptx
│
├── Week 9/
│   ├── Advanced Browser Forensics, ShellLNK Analysis, and Artifact Integration.docx
│   ├── Advanced Browser Forensics, ShellLNK Analysis, and Artifact Integration.pdf
│   ├── Week 9.docx
│   └── Week 9.pptx
│
├── Week 10/
│   ├── Autopsy Triage, Artifact Hunting, and Timeline Reconstruction.docx
│   ├── Autopsy Triage, Artifact Hunting, and Timeline Reconstruction.pdf
│   ├── Mantooth Case.zip
│   ├── Week 10.docx
│   └── Week 10.pptx
│
├── Week 11/
│   ├── Email Forensics and Super Timeline Analysis.docx
│   ├── Email Forensics and Super Timeline Analysis.pdf
│   ├── Jean Disk Image Link.txt
│   ├── Week 11.docx
│   └── Week 11.pptx
│
├── Week 12/
│   ├── The M57.biz Capstone Disk, Memory, and Exfiltration Analysis.docx
│   ├── The M57.biz Capstone Disk, Memory, and Exfiltration Analysis.pdf
│   └── Week 12.docx
│
├── LICENSE
└── README.md
```

---

## 🛠️ Key Skills & Technologies Demonstrated

* **SIEM & Threat Detection:** Wazuh deployment, agent management, File Integrity Monitoring (FIM), custom XML rule creation, MITRE ATT&CK mapping, and automated active response.
* **Network Defense & IDS:** Suricata IDS integration, custom signature writing, packet capture analysis (Wireshark), pfSense firewall administration, `iptables`/`ipset` blocklisting, and DNS sinkholing.
* **Digital Forensics (DFIR):** Disk imaging, memory forensics, Autopsy case triage, super timeline reconstruction, email forensics, and Windows artifact hunting (Event Logs, Prefetch, LNK files, Browser caches).
* **Incident Response:** Malware triage, ransomware simulation analysis, SSH brute-force mitigation, and insider threat investigation.

---

## 📑 Capstone Project: M57.biz Investigation
**The M57.biz Capstone: Disk, Memory, and Exfiltration Analysis (`Week 12/`)**  
* Conducted an end-to-end forensic investigation across raw disk images and volatile memory dumps.
* Uncovered illicit data staging, identified exfiltration vectors, and attributed actions to specific threat actors.
* Reconstructed a comprehensive forensic timeline and delivered an executive-ready incident report backed by verifiable digital evidence.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RazaJavaid2004/Cyberster-Blue-Team-Internship.git
   ```
2. **Explore the modules:**
   Navigate into any `Week X/` directory to review the lab reports, presentations (`.pptx`), and step-by-step screenshot evidence.
3. **Read the documentation:**
   All primary technical reports are provided in both `.pdf` (recommended for quick viewing directly on GitHub) and `.docx` formats.

---

## 🙌 Acknowledgments
This internship was made possible thanks to the guidance and resources provided by **Cyberster**.  
Special thanks to the Cyberster mentorship team for their structured training modules, realistic lab scenarios, and hands-on exposure to real-world Blue Team and DFIR practices.

---

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author
**Muhammad Raza**  
🔗 [GitHub Profile](https://github.com/RazaJavaid2004)
