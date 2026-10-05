# Hi, I'm Ashwin Pratap 👋

I am a CompTIA Security+ certified cybersecurity professional building hands-on experience in vulnerability assessment, security monitoring, network defense, cloud security, web application testing, and incident analysis.

My portfolio includes practical projects using Kali Linux, pfSense, Metasploitable 2, DVWA, Nmap, Greenbone/OpenVAS, Metasploit Framework, Wireshark, Splunk, Microsoft Azure, Active Directory, and OWASP ZAP.

All security testing documented below was conducted against authorized systems in controlled lab environments.

## 🔐 Cybersecurity Projects

### Azure Microsoft Defender for Endpoint

Built an Azure security environment focused on identity management, endpoint detection and response, and SOC-style investigation using Microsoft Defender for Endpoint.

- Created Microsoft Entra ID employee accounts and applied least-privilege RBAC permissions
- Deployed and onboarded a Windows Server endpoint to Microsoft Defender for Endpoint
- Executed a controlled PowerShell attack simulation to generate suspicious endpoint activity
- Investigated a Microsoft Defender alert using alert details and process-tree analysis
- Used Microsoft Defender Live Response for remote endpoint investigation
- Analyzed repeated failed authentication attempts using Azure Log Analytics and KQL

[View Project](https://github.com/ashwinp17/Azure-Microsoft-Defender-Endpoint-Lab)

### Splunk SIEM Security Investigation

Built a Splunk SIEM environment focused on Windows security monitoring, log analysis, threat investigation, and event correlation using Windows logs and the BOTS v3 dataset.

- Monitored Windows Security events, including process creation and firewall activity
- Used SPL queries to search, filter, correlate, and summarize security events
- Investigated suspicious Microsoft 365, SharePoint, and Azure AD activity
- Correlated user activity with a Hong Kong IP address across multiple data sources
- Created saved reports and a Splunk dashboard to document investigation findings

[View Project](https://github.com/ashwinp17/Splunk-SIEM-Security-Investigation-Lab)

### Nessus Vulnerability Management

Performed a vulnerability management project using Tenable Nessus and a Windows virtual machine to identify, analyze, remediate, and validate security vulnerabilities.

- Conducted credentialed vulnerability scans with Tenable Nessus
- Analyzed vulnerability severity, affected software, and remediation guidance
- Identified vulnerable Splunk Enterprise software within the Windows environment
- Remediated vulnerabilities by upgrading affected software
- Performed follow-up scans to verify remediation and compare vulnerability results

[View Project](https://github.com/ashwinp17/Nessus-Vulnerability-Management-Lab)

### NIST 800-53 Security Controls

Implemented and validated Windows security controls on an Azure Windows Server using Group Policy, with a focus on translating NIST 800-53 requirements into technical configurations and testing control effectiveness.

- Configured a 14-character minimum password length and enabled password complexity requirements
- Enforced password history to prevent reuse of the previous 5 passwords
- Configured a 90-day maximum password age to support credential lifecycle management
- Applied updated security policies using `gpupdate /force`
- Created a test account and verified that non-compliant passwords were rejected while compliant passwords were accepted
- Mapped implemented controls to NIST 800-53 AC-2 Account Management and IA-5 Authenticator Management

[View Project](https://github.com/ashwinp17/NIST-800-53-security-controls)

### Wazuh SIEM & Endpoint Monitoring

Deployed and configured a Wazuh SIEM environment in Oracle VirtualBox, connected a Windows 11 endpoint, and validated centralized endpoint monitoring and alert collection.

- Investigated repeated failed logons and reviewed Wazuh rule `60122`
- Configured real-time File Integrity Monitoring and detected file changes
- Tested EICAR file-creation visibility through Wazuh rule `554`
- Distinguished meaningful security activity from benign system events
- Added MITRE ATT&CK context, findings, screenshots, and lessons learned

[View Project](https://github.com/ashwinp17/Wazuh-SIEM-Endpoint-Monitoring-Lab)

### Cloud Security Risk Assessment & GRC Simulation

Conducted a cloud security risk assessment of an Azure-hosted Windows Server environment.

- Assessed risks involving public RDP access, privileged accounts, patching, monitoring, and Azure permissions
- Calculated risk scores using likelihood and business impact
- Recommended controls including MFA, RBAC, restricted RDP access, patch management, and centralized logging

[View Project](https://github.com/ashwinp17/cloud-security-risk-assessment-grc-azure)

### Web Application Vulnerability Scanning with OWASP ZAP

Performed an automated vulnerability assessment against DVWA using OWASP ZAP in an isolated VirtualBox lab.

- Identified Remote Code Execution and Source Code Disclosure findings
- Analyzed missing security headers, anti-CSRF protections, and insecure cookie settings
- Generated a professional vulnerability report with remediation recommendations

[View Project](https://github.com/ashwinp17/owasp-zap-dvwa-vulnerability-scan)

### Linux Log Analysis with Splunk

Analyzed Linux authentication logs using Python automation and Splunk SIEM.

- Investigated authentication activity and suspicious security events
- Processed log data using Python
- Created Splunk searches, dashboards, and alerts
- Documented findings in a security-analysis report

[View Project](https://github.com/ashwinp17/linux-log-analysis-splunk)

### Azure Active Directory SOC Investigations

Deployed and administered an Active Directory environment hosted in Microsoft Azure.

- Configured Windows Server, Active Directory Domain Services, and DNS
- Created and managed domain users and organizational units
- Joined a Windows client to the domain
- Reviewed Windows Security events related to authentication and account activity

[View Project](https://github.com/ashwinp17/azure-active-directory-soc-lab)

### Network Scanning and Host Enumeration with Nmap

Performed network reconnaissance and service enumeration against a vulnerable Linux target.

- Discovered active hosts and exposed network services
- Identified operating-system and service-version information
- Analyzed open ports, legacy protocols, database services, and remote-access services
- Used Nmap NSE scripts to investigate potential vulnerabilities

[View Project](https://github.com/ashwinp17/network-scanning-host-enumeration-nmap)

### Metasploit Exploitation Lab — DistCC Remote Command Execution

Performed authorized exploitation testing against an intentionally vulnerable Metasploitable 2 target using Metasploit Framework.

- Selected and configured the DistCC remote command-execution exploit
- Executed the exploit against the vulnerable service
- Validated successful remote command access
- Documented the security impact and recommended remediation

[View Project](https://github.com/ashwinp17/metasploit-exploitation-lab)

### OpenVAS Vulnerability Assessment

Performed a vulnerability assessment against an intentionally vulnerable Metasploitable 2 target using Greenbone/OpenVAS.

- Identified and prioritized critical, high, medium, and low-risk vulnerabilities
- Analyzed an exposed backdoor service that allowed root-level command execution
- Reviewed affected ports, CVSS severity, security impact, and remediation
- Preserved the scan report and critical-finding evidence

[View Project](https://github.com/ashwinp17/openvas-vulnerability-assessment)

### Wireshark Packet Analysis

Captured and analyzed ICMP and FTP traffic using Wireshark in an isolated cybersecurity lab.

- Verified network connectivity through ICMP echo requests and replies
- Inspected source and destination addresses at the packet level
- Demonstrated that FTP transmitted usernames and passwords in plaintext
- Preserved packet captures and supporting screenshots as evidence

[View Project](https://github.com/ashwinp17/wireshark-packet-analysis)

## 🛠 Tools Used Across Projects and Training

### Security and Monitoring

- Splunk
- Greenbone/OpenVAS
- OWASP ZAP
- Wireshark
- Nmap
- Metasploit Framework

### Systems and Infrastructure

- Kali Linux
- Linux
- Windows Server
- Microsoft Azure
- Active Directory
- pfSense
- Oracle VirtualBox

### Vulnerable Lab Platforms

- Metasploitable 2
- Damn Vulnerable Web Application
- TryHackMe

### Scripting and Documentation

- Python
- GitHub
- Markdown
- Technical security reporting

## 📜 Certification

- CompTIA Security+

## 📌 Current Focus

- Security Operations Center analysis
- Vulnerability assessment and remediation
- Network traffic and log analysis
- Cloud and identity security
- Web application security
- Incident detection and investigation
- Building a professional cybersecurity portfolio

## 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/ashwin-pratap)
- [TryHackMe](https://tryhackme.com/p/ashwinpratap17)
