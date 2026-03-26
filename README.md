# Network Sentinel v1.1
## High-Availability Infrastructure Monitoring & Automated Triage

### 📌 Overview
Network Sentinel is a proactive diagnostic suite engineered to eliminate "silent failures" within enterprise IT environments. By shifting from a reactive support model to automated, real-time monitoring, this tool ensures 100% visibility into critical network paths and service availability.

### 🚀 Core Features
* [cite_start]**Multi-Path Diagnostics:** Performs asynchronous ICMP and DNS resolution cycles to monitor gateway health and external connectivity.
* **Real-Time Alerting:** Integrated with the Telegram Bot API for instantaneous mobile notifications upon service failure.
* [cite_start]**Data Persistence & Fallback:** Implements a local Python Logging Engine to maintain an immutable audit trail for post-incident analysis and reporting[cite: 65].
* [cite_start]**KISS Architecture:** Developed with a "Keep It Super Simple" approach—zero-license dependency and minimal resource overhead for maximum reliability.

### 🛠️ Technical Implementation
* **Language:** Python 3.x
* **Integrations:** Telegram API (Primary), Local File System (Fallback Logging)
* [cite_start]**Methodology:** Automated ICMP/DNS Triage & Systems Hardening [cite: 64]

### 💼 Business Impact
* [cite_start]**Reduced MTTR:** Automates the initial 15-minute diagnostic phase, allowing technicians to arrive at the hardware with the solution already identified.
* **Proactive Resolution:** Identifies network "brown-outs" and service spikes before they are reported by end-users.
* **Operational Transparency:** Provides a detailed log history for infrastructure audits and service-level agreement (SLA) verification.

---
*Note: The source code for this project is maintained in a private repository to protect proprietary logic and system security. Architectural walkthroughs are available upon request during professional consultations.*
