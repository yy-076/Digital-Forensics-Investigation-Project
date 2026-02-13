# Digital Forensics Investigation on Infected Windows 10 System

This project demonstrates a digital forensic investigation conducted on an infected Windows 10 virtual machine using industry-standard forensic tools. The investigation follows the Digital Forensic Investigation Methodology (DFIM) to acquire, preserve, analyze, and validate digital evidence in a controlled virtualized environment.

---

## Project Objectives
- Investigate a compromised Windows 10 virtual machine
- Identify malicious files and suspicious processes
- Perform memory (RAM) and disk acquisition
- Analyze malware behaviour and execution patterns
- Maintain integrity of forensic evidence through hash verification

---

## Tools Used
- VMware Workstation (Virtual Environment)
- FTK Imager (Memory Acquisition)
- Volatility Workbench (RAM Analysis)
- Autopsy (Disk Analysis)
- VirusTotal (Malware Verification)
- Windows PowerShell (Hash Extraction)

---

## Investigation Scope
### Static Data Acquisition
- RAM Memory Dump (.mem)
- Virtual Disk Image (.vmdk)
- File Hash Value Extraction (SHA-256)

### Surface-Level Malware Analysis
- Detection of suspicious executable files
- Verification using VirusTotal
- Identification of trojans, keyloggers, downloaders, and hacktools

### Memory Analysis (Volatility)
- Running and hidden process detection
- Code injection analysis
- Malware execution chain discovery
- Process masquerading detection

### Disk Analysis (Autopsy)
- File system investigation
- Suspicious executable detection
- Contacted domains and IP analysis
- Malware behaviour and communication tracking

---

## Key Findings
- Multiple malware instances detected within system memory and disk
- Evidence of process injection and multi-stage execution
- Trojan-based tools disguised as legitimate applications
- Suspicious DNS and IP communication patterns
- Weak system password leading to unauthorized access

---

## Skills Demonstrated
- Digital Evidence Acquisition
- RAM Forensics & Memory Analysis
- Malware Behaviour Analysis
- Hash Verification (SHA-256)
- Disk Image Investigation
- Incident Response Investigation
- Cybersecurity Threat Identification

---

## Report
Refer to:
Digital_Forensics_Investigation_Windows10.pdf
