

---

# 🛡️ Multi-Layer Security Integration Based on SIEM Solution

## 📌 Project Overview

This project implements a **multi-layer, defense-in-depth security architecture** using open-source security tools integrated into a centralized **SIEM-driven SOC framework**. The goal is to simulate real-world attacks, detect threats in real time, correlate security events, and alert administrators promptly.

The architecture mirrors real **Security Operations Center (SOC)** environments with emphasis on **detection, visibility, and response**.

---

## 🎯 Objectives

* Simulate realistic cyberattack scenarios
* Detect malicious activity in real time
* Correlate logs across network and host layers
* Perform host-based intrusion detection (HIDS)
* Send automated email alerts to administrators
* Enhance malware detection using threat intelligence

---

## 🧱 Architecture Components

### 🔥 pfSense (Firewall)

* Network perimeter security
* Traffic filtering and access control
* Network segmentation and routing
* First line of defense

### 🛡️ Suricata (IDS/IPS)

* Deep Packet Inspection (DPI)
* Signature-based and anomaly-based detection
* Detection of scans, exploits, and suspicious traffic
* Alerts forwarded to SIEM

### 📊 Wazuh (SIEM / HIDS)

* Centralized log collection and correlation
* Rule-based and behavior-based detection
* Host-based intrusion detection (file integrity, rootkits, log analysis)
* Real-time alerts and dashboards
* Integration with external threat intelligence

### 📧 Postfix (Email Alerting Server)

* Configured SMTP server for alert delivery
* Sends real-time security alerts to administrators
* Enables rapid awareness and response
* Integrated with Wazuh alerting mechanisms

### 🧪 Kali Linux (Attack Simulation)

* Red-team testing platform
* Simulates:

  * Network scanning
  * Brute-force attacks
  * Exploitation attempts
  * Credential-based attacks

### 🧬 VirusTotal Integration (HIDS Enhancement)

* Integrated with Wazuh HIDS
* Suspicious files and hashes are checked against VirusTotal
* Improves malware detection accuracy
* Adds threat intelligence context to alerts

---

 ### Architecture
 siemprj.drawio.png


## 🧩 Project Workflow

1. Attacks are launched from **Kali Linux**
2. Traffic passes through **pfSense**
3. **Suricata** inspects network traffic
4. Hosts generate logs and file integrity events
5. **Wazuh SIEM** correlates all security events
6. File hashes are validated using **VirusTotal**
7. Critical alerts are sent via **Postfix email server**
8. Administrator analyzes incidents using SIEM dashboards

---

## 🧠 Key Learning Outcomes

* Practical SOC operations and workflows
* SIEM integration and multi-source log correlation
* Network-based and host-based detection
* Malware validation using threat intelligence
* Automated alerting and incident awareness

---

## 🏢 Use Cases

* Academic cybersecurity laboratories
* SOC analyst training and simulation
* SME-level security monitoring solutions
* Defensive security research and blue-team practice

---

## 🛠️ Tools & Technologies

* pfSense
* Suricata
* Wazuh
* Postfix
* VirusTotal API
* Kali Linux
* VirtualBox / VMware

---

## 👥 Team Members

* **Sujal Lamichhane**
* **Ujjwal Kandel**
* **Nirmal Adhikari**

## Supervisor
* **Anuj Khanal**
* **+977-9865206191**

---

## 📌 Disclaimer

This project is intended **strictly for educational and research purposes**. All testing is performed in an isolated lab environment. Unauthorized testing on live systems is illegal.

---


