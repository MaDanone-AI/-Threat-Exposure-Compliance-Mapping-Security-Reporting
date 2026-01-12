Threat Exposure, Compliance Mapping & Security Reporting
This project focuses on identifying critical asset vulnerabilities, mapping them to real-world threat scenarios, and establishing a SIEM-style monitoring and reporting framework.

Core Components:

1. Asset & Threat Mapping

Asset Selection: Identifies and prioritizes critical systems such as Webservers, DB servers, and Domain Controllers.


Vulnerability Analysis: Analyzes the top 10 vulnerabilities per system based on previous scan results.


Scenario Mapping: Links vulnerabilities to specific threats like data theft, ransomware, or privilege escalation.


Impact Assessment: Evaluates threats against Confidentiality, Integrity, and Availability (CIA).

2. Compliance & SIEM Integration

Framework Alignment: Maps threats to regulatory requirements including POPIA, GDPR, PCI DSS, and ISO 27001.


SIEM Alerting: Implements alerting use cases using tools like Wazuh, Splunk, or Elastic Stack to detect exploitation attempts.

3. Operational Performance

KPI Tracking: Measures program success through Mean Time To Remediate (MTTR) and SLA Adherence Rates.


Vulnerability Trends: Monitors the net change in open vulnerabilities month-over-month to ensure a reduction in risk.


Governance: Defines a monthly reporting process involving the Vulnerability Analyst, VM Team Lead, and CISO.

Requirements

Virtualization: VirtualBox.


Scanning Tools: Greenbone/OpenVAS or Nessus Essentials.


Logging: Any major SIEM or log management platform.
