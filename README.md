

---

# 🛡️ Multi-Layer Security Integration Based on SIEM Solution

## 📌 Project Overview

This project implements a **multi-layer, defense-in-depth security architecture** using open-source security tools integrated into a centralized **SIEM-driven SOC framework**. The objective is to simulate real-world cyberattacks, detect them in real time, and analyze incidents across network and host layers.

The setup reflects how modern **Security Operations Centers (SOC)** operate, with emphasis on **visibility, correlation, and incident response**.

---

## 🎯 Objectives

* Simulate realistic cyberattack scenarios
* Detect malicious activity in real time
* Correlate logs from multiple security layers
* Analyze incidents using SIEM dashboards
* Demonstrate SOC workflows suitable for SMEs and learners

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
* Detects network-level threats (scanning, exploitation, C2 traffic)
* Forwards alerts to the SIEM

### 📊 Wazuh (SIEM / HIDS)

* Centralized log collection
* Log correlation and rule-based detection
* Real-time alerting and visualization
* Host-based intrusion detection (HIDS)
* Incident investigation and analysis

### 🧪 Kali Linux (Attack Simulation)

* Red-team testing platform
* Simulates attacks such as:

  * Network scanning
  * Brute-force attempts
  * Exploitation testing
  * Credential attacks

---

## 🧩 Project Workflow

1. Attacks are generated from **Kali Linux**
2. Traffic passes through **pfSense** firewall
3. **Suricata** inspects and flags malicious patterns
4. Logs and alerts are sent to **Wazuh SIEM**
5. Security events are correlated and analyzed
6. Incidents are reviewed via SIEM dashboards

---

## 🧠 Key Learning Outcomes

* Hands-on SOC operations experience
* SIEM integration and log correlation
* Network and host-based detection techniques
* Blue-team monitoring and analysis
* Incident response fundamentals

---

## 🏢 Use Cases

* Academic cybersecurity laboratories
* SOC analyst training environments
* SME-level security monitoring prototypes
* Defensive security research

---

## 🛠️ Tools & Technologies

* pfSense
* Suricata
* Wazuh
* Kali Linux
* VirtualBox / VMware

---

## 👥 Team Members

* **Sujal Lamichhane**
* [Add other team members]

---

## 📌 Disclaimer

This project is intended **solely for educational and research purposes**. All testing is performed in an isolated lab environment. Unauthorized testing against live systems is illegal.

---

