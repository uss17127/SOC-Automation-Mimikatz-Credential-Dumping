# SOC Automation – Mimikatz Credential Dump Detection Lab

## Overview
This project simulates a Security Operations Center (SOC) detection environment designed to identify credential dumping attacks using Mimikatz. The lab tests detection visibility, log telemetry, and alerting logic to evaluate defensive monitoring effectiveness.

---

## Security Skills Demonstrated
- Detection engineering
- Threat simulation
- Windows event log analysis
- SIEM investigation workflow
- Incident triage
- MITRE ATT&CK mapping
- Alert validation and tuning

---

## Attack Scenario
A credential dumping attack was simulated using Mimikatz to evaluate whether defensive monitoring systems could detect suspicious activity and generate alerts.

---

## Detection Methodology
Detection was based on identifying:
- Suspicious process execution
- Privileged access anomalies
- Known Mimikatz behavioral indicators
- Abnormal authentication activity

---

## Detection Workflow
1. Execute simulated attack
2. Generate system logs
3. Forward logs to monitoring platform
4. Apply detection logic
5. Trigger alert
6. Investigate indicators

---

## MITRE ATT&CK Techniques Observed
- Credential Dumping (T1003)
- Privilege Escalation Indicators
- Credential Access Techniques

---

## Architecture Diagram
See full architecture diagram inside the technical report PDF below.

---

## Evidence
Screenshots of logs, alerts, and detections are included in the full report.

---

## Lessons Learned
- Initial rules required tuning to reduce false positives
- Increased log verbosity improved detection visibility
- Detection accuracy improved after refining indicators

---

## Future Improvements
- Automated alert enrichment
- Threat intelligence integration
- Expanded detection rule library
- Additional attack simulations

---

## Full Technical Walkthrough
Detailed documentation and screenshots:
- [Project Report (PDF)](Mimikatz_Project_Report.pdf)
