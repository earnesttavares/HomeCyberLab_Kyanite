<p align="center">
  <img src="images/Kyanite.png" alt="Kyanite Banner" width="100%">
</p>

<div align="center">
    <h1>⚗️ Home SOC Lab 🪨</h1>
</div>

Welcome to Kyanite! 👋 My personal Security Operations Center (SOC) lab, created to explore and practice real-world cybersecurity operations from a home environment. Using security tools, attack simulations, and investigative workflows I am developing hands-on experience in **threat detection, incident response, log analysis, and digital forensics**. This lab serves as both a learning platform and a project portfolio, helping me build practical defensive security skills while preparing for the CompTIA CySA+ certification.  

---

## 📖 Table of Contents

- 📝 [Objectives](#-objectives)
- 🛠️ [Lab Infrastructure](#%EF%B8%8F-lab-infrastructure)
  - 🌐 [Network Topology](#-network-topology)
  - 💻 [Hardware Specifications](#-hardware-specifications)
- 🛡️ [Security Stack](#%EF%B8%8F-security-stack)
- 🚨 [Detection & Response Workflows](#-detection--response-workflows)
- 🗂️ [Planned Projects & Exercises](#%EF%B8%8F-planned-projects--exercises)
- 💼 [Key Skills Demonstrated](#-key-skills-demonstrated)
- 🔬🥼 [Lab Scenarios](#-lab-scenarios) 

---

## 📝 Objectives 

&ensp;☒ Build & maintain a functional home SOC environment. <br>
&ensp;☐ Develop skills in network monitoring, log analysis & threat detection. <br>
&ensp;☐ Perform vulnerability assessments to identify & evaluate security weaknesses. <br>
&ensp;☐ Conduct malware analysis & digital forensics investigations. <br>
&ensp;☐ Document security findings, investigative processes & remediation efforts. <br>
&ensp;☐ Document challenges, resolutions & key lessons learned to support continuous improvement. <br> 

---

## 🛠️ Lab Infrastructure  

### 🌐 Network Topology 

```mermaid
--- 
config:
  theme: neo-dark
  themeVariables:
    primaryColor:
---

flowchart TD
    Internet["🌐 Internet"]
    Router["📡 ISP Router"]
    Switch["🔀 TP-Link Managed Switch"]

    Internet --> Router
    Router --> Switch

    subgraph Host["💻 Lenovo IdeaPad Y700 (Kali Linux)"]
        direction LR
        VBox["📦 VirtualBox"]-->VM["🧊 Metasploitable 2 VM"]

        VBox --> VM
    end

    Switch --> VBox
```

### 💻 Hardware Specifications 
| **Component** | **Details** | 
| --- | --- | 
| **Host Machine** | Secondhand Lenovo IdeaPad Y700 w/ 32GB RAM |
| **Host Operating System** | Kali Linux | 
| **Hosted Hypervisor** | VirtualBox | 
| **Virtual Machines** | Kali Linux, Metasploitable 2 | 

---

## 🛡️ Security Stack

&emsp;➔ Wireshark <br>
&emsp;➔ Volatility 3 <br>
&emsp;➔ Snort <br>

---

## 🚨 Detection & Response Workflows 

This lab is designed around the following SOC workflows: 

1. Log Collection
2. Alert Generation
3. Investigation
4. Evidence Collection
5. Incident Documentation
6. Remediation Validation

---

## 🗂️ Planned Projects & Exercises 

&ensp;☐ Deploying & Tuning Snort IDS <br>
&ensp;☐ Network Traffic Analysis w/ Wireshark <br>
&ensp;☐ Vulnerability Assessment of Metasploitable 2 <br>
&ensp;☐ Threat Detection & Alert Investigation <br>
&ensp;☐ Digital Forensics & Incident Response <br>
&ensp;☐ Fortinet FortiGate 60D Firewall Security Hardware Research <br>
&ensp;☐ Wrap-Up: Lab Challenges, Troubleshooting & Lessons Learned <br>

---

## 💼 Key Skills Demonstrated

&emsp;➔ Security Monitoring <br>
&emsp;➔ Log Analysis <br>
&emsp;➔ Network Traffic Analysis <br>
&emsp;➔ Incident Response <br>
&emsp;➔ Linux Administration <br>
&emsp;➔ IDS/IPS Operations <br>
&emsp;➔ Digital Forensics <br>
&emsp;➔ Documentation & Reporting <br>

---

## 🔬🥼 Lab Scenarios

Scenario 1: Port Scan Detection [Project Documentation Link]

&emsp;➔ Generated traffic with Nmap <br>
&emsp;➔ Triggered IDS alerts <br>
&emsp;➔ Investigated logs <br>

<p align="center">
  <img
    src="https://hyperweave.app/a/inneraura/dividers/zeropoint"
    alt="divider"
    width="100%"
  />
</p> 
