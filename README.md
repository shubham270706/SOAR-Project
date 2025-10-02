# SOAR Implementation & Distributed SIEM Lab

This repository documents the next phase of my journey in building a Security Operations Center (SOC) Lab, focused on the transition from threat detection (SIEM/XDR) to **automated incident response (SOAR)**. This project upgrades the core Wazuh/ELK environment to include dedicated orchestration and case management platforms.

---

## 🧠 Project Abstract: From Alert to Action

The project is structured to demonstrate the complete incident response lifecycle, proving the ability to reduce **Mean Time to Respond (MTTR)** through codified, automated workflows.

### Key Focus Areas:
* **Orchestration:** Connecting disparate tools (SIEM, Threat Intel, Case Management) into unified workflows.
* **Automation:** Implementing **Human-in-the-Loop** playbooks for consistent and rapid response.
* **Distributed Architecture:** Maintaining system stability and efficiency by distributing heavy services across multiple nodes.

---

## 🧩 Project Structure

| Folder | Description |
|--------|-------------|
| **`PHASE_1_FOUNDATION/`** | **Initial Setup & Architecture:** VM/Pi configuration, network base, VNC/SSH access, and resource optimization. |
| **`PHASE_2_SIEM_TUNING/`** | **Detection Logic:** Custom Wazuh rules, decoders, and EDR configuration (FIM, Vulnerability Detection). |
| **`PHASE_3_SOAR_INTEGRATION/`** | **Automation & Orchestration:** Setup of TheHive/Cortex and Shuffle playbooks for response. |
| **`INCIDENT_CASES/`** | **Analyst Work:** Documented attack simulations, forensic findings, and SOAR outcome reports. |
| **`TROUBLESHOOTING/`** | Common problems encountered and solutions (e.g., Elasticsearch JVM tuning, Static IP errors). |

---

## 🧪 Lab Setup: Distributed Architecture

The environment is designed to simulate a production network with separated roles, utilizing a **Virtual Machine (VM)** for processing power and the **Raspberry Pi 4** as the monitored host.

### 💻 Machines Used

| Role | OS | Description |
|------|----|-------------|
| **SOC Manager** | Ubuntu 24.04 | **VM (6GB+ RAM)** hosting the Wazuh Manager, ELK Stack, TheHive, and Shuffle. |
| **Monitored Endpoint** | Raspberry Pi OS | **Raspberry Pi 4 (2GB RAM)** running the **Wazuh Agent**. |
| **Attacker** | Kali Linux | **VM** used to launch simulated network and host-based attacks against the Monitored Endpoint. |

---

## 🛠️ Tools & Technologies

-   **Wazuh** (SIEM and Open-Source XDR)
-   **Elasticsearch, Kibana** (Data Analysis and Visualization)
-   **TheHive** (Security Incident Response Platform - SIRP)
-   **Cortex** (Threat Intelligence Enrichment Engine)
-   **Shuffle** (Open-Source SOAR Automation Engine)
-   **VNC** / **SSH** (Headless Remote Access)
-   **Python** (Custom Playbook Logic)

---

## 🎯 Objective

The goal of this project is to create an advanced cybersecurity portfolio piece by:

-   **Integrating SOAR:** Establishing a functional alert hand-off pipeline from Wazuh to TheHive and Shuffle.
-   **Codifying Response:** Developing automated playbooks for common threats (e.g., phishing, brute-force).
-   **Demonstrating Expertise:** Showcasing practical skills in system architecture, resource optimization, and modern security operations.

---

## 📬 Contact

**Shubham Mahato**

Email: [shubhammahato224@gmail.com](mailto:shubhammahato224@gmail.com)

GitHub: [@shubham270706](https://github.com/shubham270706)
