<p align="center">
  <img src="images/Kyanite.png" alt="Kyanite Banner" width="100%">
</p>

<div align="center">
    <h1>⚗️ Home SOC Lab 🪨</h1>
</div>

Welcome to Kyanite! 👋 My personal Security Operations Center (SOC) lab, created to explore and practice real-world cybersecurity operations from a home environment. Using security tools, attack simulations, and investigative workflows I am developing hands-on experience in threat detection, incident response, log analysis, and digital forensics. This lab serves as both a learning platform and a project portfolio, helping me build practical defensive security skills while preparing for the CompTIA CySA+ certification.    

<br>

## 📋 Objectives 

&ensp;☒ Build and maintain a functional home SOC environment. <br>
&ensp;☐ Develop skills in network monitoring, log analysis, and threat detection. <br>
&ensp;☐ Perform vulnerability assessments to identify and evaluate security weaknesses. <br>
&ensp;☐ Conduct malware analysis and digital forensics investigations. <br>
&ensp;☐ Document security findings, investigative processes, and remediation efforts. <br>
&ensp;☐ Document challenges, resolutions, and key lessons learned to support continuous improvement. <br> 

<br>

## 📅 Planned Projects & Exercises 

&ensp;❖ Deploying and Tuning Snort IDS <br>
&ensp;❖ Network Traffic Analysis with Wireshark <br>
&ensp;❖ Vulnerability Assessment of Metasploitable 2 <br>
&ensp;❖ Threat Detection and Alert Investigation <br>
&ensp;❖ Digital Forensics and Incident Response <br>
&ensp;❖ Fortinet FortiGate 60D Firewall Security Hardware Research <br>
&ensp;❖ Lab Challenges, Troubleshooting, and Lessons Learned <br> 

<br>

## ⚒️ Lab Infrastructure  

| **Component** | **Details** | 
| --- | --- | 
| **Host Machine** | Secondhand Lenovo IdeaPad Y700 w/ 32GB RAM |
| **Host Operating System** | Kali Linux | 
| **Hosted Hypervisor** | VirtualBox | 
| **Virtual Machines** | Kali Linux, Metasploitable 2 | 

```mermaid
---
title: HomeCyberLab_Kyanite Network Topology 
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


<p align="center">
  <img
    src="https://hyperweave.app/a/inneraura/dividers/zeropoint"
    alt="divider"
    width="100%"
  />
</p> 

<br>
<br>

## 🖬 Tools & Technologies 

### 🔺 Security Tools

In Progress...

---

## 🗐 Project Documentation

## Key Skills Demonstrated 

