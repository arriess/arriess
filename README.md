# Hi, I'm Hicham Essafi 👋

Cybersecurity graduate focused on **Security Operations, Threat Detection, Incident Response, Phishing Analysis, and Blue Team security**.

I build practical SOC analyst skills through hands-on security projects involving **Splunk Enterprise, Microsoft Sentinel, KQL, Windows Security telemetry, Wireshark, phishing triage, IOC analysis, and incident-response documentation**.

## 🔐 SOC & Blue Team Portfolio

### [SOC Analyst Lab](https://github.com/arriess/SOC-Analyst-Lab)

A hands-on **Windows + Splunk + Microsoft Sentinel + Wireshark** security operations portfolio with **5 Splunk detections validated end-to-end**, **2 documented analyst investigations**, and a repeated-failed-logon detection reproduced and validated in **Microsoft Sentinel using KQL**.

Validated Splunk detections include:

- Repeated Windows failed logons — Event ID 4625
- Command Prompt spawning PowerShell — Event ID 4688
- Failed logons followed by successful authentication — Event IDs 4625 + 4624
- New local user account creation — Event ID 4720
- User added to Local Administrators group — Event ID 4732

Microsoft Sentinel expansion includes:

- Windows host onboarding with Azure Arc
- Azure Monitor Agent (AMA)
- Data Collection Rule using Windows Security Events
- `SecurityEvent` telemetry validation
- KQL correlation of 5 failed logons within a 2-minute window

Documented investigations include:

- Windows failed-login analysis
- DNS traffic analysis with Wireshark using A and AAAA query/response filtering

The project demonstrates practical SOC workflows across endpoint, SIEM, and network telemetry, from controlled event generation and collection through detection, triage, investigation, correlation, and sanitized documentation.

---

### [Phishing Analysis & Incident Response Lab](https://github.com/arriess/Phishing-Analysis-Lab)

A controlled SOC portfolio focused on **phishing triage, email-header analysis, IOC extraction, suspicious-link analysis, Business Email Compromise (BEC), and incident-response decisions**.

Completed investigations include:

- **Credential Phishing Analysis** — sender/header review, SPF/DKIM/DMARC analysis, IOC extraction, URL assessment, and MITRE ATT&CK T1566.002
- **Suspicious Link Analysis** — URL parsing, encoded redirects, domain/DNS context, risk assessment, and MITRE ATT&CK T1566.002
- **Business Email Compromise (BEC)** — executive impersonation, Reply-To mismatch, urgent payment-request analysis, financial-risk assessment, and MITRE ATT&CK T1656

The project demonstrates:

- Phishing and BEC triage
- Email-header analysis
- SPF / DKIM / DMARC interpretation
- IOC extraction and documentation
- URL and redirect analysis
- Social-engineering assessment
- Severity and confidence classification
- False-positive analysis
- MITRE ATT&CK mapping
- Containment and response recommendations
- Privacy-conscious evidence sanitization

All scenarios use simulated or benign training samples, reserved test domains, and documentation-only infrastructure. No real credentials, malicious payloads, live phishing infrastructure, or third-party targets are used.

## 🛠️ Practical Skills

**Security Operations**
- Security monitoring
- Alert triage
- Log analysis
- Threat detection
- Incident investigation fundamentals
- Detection engineering fundamentals
- Phishing and BEC triage
- IOC analysis
- MITRE ATT&CK mapping

**SIEM & Detection**
- Splunk Enterprise
- Splunk Search Processing Language (SPL)
- Microsoft Sentinel
- Kusto Query Language (KQL)
- Azure Arc
- Azure Monitor Agent (AMA)
- Data Collection Rules
- Windows `SecurityEvent` telemetry

**Windows Security**
- Windows Security Event Logs
- Windows Event Viewer
- Authentication-event analysis
- Process-creation analysis
- Account and privilege-change monitoring

**Email & Phishing Analysis**
- Email-header analysis
- SPF / DKIM / DMARC interpretation
- Sender / Reply-To comparison
- URL and redirect analysis
- Credential-phishing triage
- Business Email Compromise analysis
- Social-engineering indicator assessment

**Network Analysis**
- Wireshark
- DNS traffic analysis
- Packet filtering
- A / AAAA query-response analysis
- TCP/IP and DNS fundamentals
- Network troubleshooting

**Systems & Scripting**
- Windows
- Linux
- VirtualBox
- PowerShell
- Windows Command Prompt
- Python fundamentals

## 🧪 Hands-on Learning

- 60+ completed TryHackMe rooms
- TryHackMe Top 8% at last profile review
- Windows and Linux security labs
- Cybersecurity and networking exercises
- Phishing and social-engineering simulations

## 📜 Credentials & Training

- Cisco Cybersecurity Essentials
- Cisco Networking Essentials
- Cisco Introduction to Cybersecurity
- Cisco Introduction to IoT
- ISC2 Certified in Cybersecurity (CC) Self-Paced Training
- TryHackMe CompTIA PenTest+ Learning Path — Certificate of Completion

## 🎯 Current Direction

I am continuing to strengthen practical skills in:

- SOC alert investigation
- Splunk and Microsoft Sentinel detection engineering
- Windows security monitoring
- KQL and security-event correlation
- Phishing and BEC investigation
- IOC and email-header analysis
- Network traffic analysis
- Incident-response workflows

## 💼 Opportunities

I am actively seeking **Junior SOC Analyst, Cybersecurity Analyst, Security Operations Analyst, and Junior Security Analyst** opportunities in Germany.

## 🔗 Profiles

- LinkedIn: https://www.linkedin.com/in/hicham-essafi/
- TryHackMe: https://tryhackme.com/p/HichamEssafi
- Credly: https://www.credly.com/users/hicham-essafi
