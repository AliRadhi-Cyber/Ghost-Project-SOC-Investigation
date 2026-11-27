# Ghost Project | SOC Analyst Investigation

## Project Overview

Ghost Project is a hands-on cybersecurity investigation designed to simulate real-world Security Operations Center (SOC) analyst responsibilities within a controlled Windows 11 virtual laboratory.

## Project Objectives

- Detect suspicious authentication activity.
- Investigate Windows Security Event Logs.
- Identify and correlate security events.
- Collect and preserve digital evidence.
- Verify evidence integrity using SHA256.
- Reconstruct an incident timeline.
- Map observed behaviors to MITRE ATT&CK.
- Produce a professional SOC incident report.

## Tools and Technologies

- Oracle VirtualBox
- Windows 11
- Windows Event Viewer
- Windows PowerShell
- Windows Security Event Logs
- SHA256 Cryptographic Hashing
- MITRE ATT&CK Framework

## Security Events Investigated

| Event ID | Description |
|---|---|
| 4720 | User account creation |
| 4625 | Failed authentication |
| 4624 | Successful authentication |

## Investigation Workflow

1. Created a controlled Windows laboratory.
2. Created a local test account.
3. Simulated authentication activity.
4. Collected Windows Security Event Logs.
5. Filtered and analyzed authentication events.
6. Exported digital evidence.
7. Verified evidence integrity using SHA256.
8. Reconstructed the incident timeline.
9. Classified the observed activity.
10. Mapped behaviors to MITRE ATT&CK.
11. Completed a professional incident report.

## MITRE ATT&CK Mapping

| Technique ID | Technique |
|---|---|
| T1136.001 | Create Account: Local Account |
| T1110.001 | Brute Force: Password Guessing |
| T1078.003 | Valid Accounts: Local Accounts |

These mappings represent simulated behaviors and potential detection opportunities, not confirmed malicious activity.

## Investigation Results

- One local account creation event identified.
- Two failed authentication events identified.
- One successful authentication event identified.
- Original evidence integrity verified.
- Incident timeline reconstructed.
- Severity: Informational.
- Classification: Authorized Benign Simulation.
- Investigation status: Completed.

## Skills Demonstrated

- Security monitoring
- Incident triage
- Windows event log analysis
- PowerShell
- Authentication analysis
- Digital forensics
- Evidence preservation
- Event correlation
- Threat classification
- Technical documentation

## Disclaimer

This project was conducted in an authorized, controlled virtual laboratory for cybersecurity education and professional development. Original security logs are retained privately to protect sensitive system information.
