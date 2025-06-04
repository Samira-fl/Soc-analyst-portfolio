# SOC Fundamentals

Welcome to the first step of your career as a SOC analyst. In this lesson, I introduce the structure of Security Operations Centers (SOCs), the essential tools, and the responsibilities of a SOC analyst.

## 📘 What Will You Learn?

- Structure and operation of a SOC
- SOC Tools and products: SIEM, EDR, SOAR, Log Management
- Analyst workflows and best practices
- Common mistakes made by SOC analysts
- Practical hands-on learning in LetsDefend

## 🧠 Types of SOC Models

- **In-house SOC**: Fully managed internal teams
- **Virtual SOC**: Remote SOC teams with no physical location
- **Co-Managed SOC**: Internal teams + external MSSP
- **Command SOC**: Central command monitoring smaller SOCs

## ⚙ People, Process, and Technology

- **People**: Skilled staff trained in threat detection and research
- **Processes**: Based on NIST, PCI, HIPAA to ensure standardized actions
- **Technology**: Tools for detection, prevention, analysis — aligned with budget and environment

## 👥 SOC Roles

- **SOC Analyst (L1, L2, L3)**: Alert triage, investigation, escalation
- **Incident Responder**: First response to security breaches
- **Threat Hunter**: Proactive threat investigation and APT detection
- **Security Engineer**: Maintains SIEM/SOAR integrations
- **SOC Manager**: Strategy, budgeting, coordination

## 📌 Key Responsibilities of a SOC Analyst

- Investigate threats via SIEM
- Escalate incidents when required
- Analyze using EDR, SOAR, logs
- Communicate findings clearly

## 🛠 Skills Required

- OS Knowledge (Windows/Linux)
- Networking Fundamentals
- Malware Analysis
- Real-time decision making

## 🔄 A Day in the Life

- Review and classify SIEM alerts
- Use tools like EDR, Log Management
- Correlate threat intel
- Communicate with team via shared dashboard

## 💡 SIEM and Analyst Relationship

- SIEM alerts → Analyst reviews
- Analysts validate alerts using EDR, logs, and TI feeds
- Analysts provide feedback on false positives

## 🧾 Log Management

- Central view of logs: OS, proxy, firewall
- Search for IOCs
- Investigate communication with malicious IPs/domains

## 🧪 EDR Use

- Investigate infected hosts
- Search for hashes, processes, IPs
- Contain compromised systems

## 🤖 SOAR Benefits

- Automates repetitive actions
- Connects SIEM, VirusTotal, sandbox, etc.
- Uses playbooks to guide analysts through workflows

## 🌐 Threat Intelligence Feeds

- Use TI feeds like VirusTotal, Talos
- Never trust results blindly — revalidate
- Understand IPs can change owners

## ❌ Common Mistakes

- Over-reliance on VirusTotal
- Short sandbox analysis
- Shallow log analysis
- Ignoring timestamps on scans

