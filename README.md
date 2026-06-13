
# Home SOC Lab using Splunk

## Overview

This project demonstrates a Security Operations Center (SOC) home lab built using Splunk Enterprise and Windows Event Logs.

## Environment

- Windows 10 VM
- VMware Workstation
- Splunk Enterprise
- Windows Security Logs

## Detection Rules

1. Multiple Failed Login Attempts (Event ID 4625)
2. User Account Creation (Event ID 4720)
3. User Account Deletion (Event ID 4726)

## Screenshots

### Failed Login Detection

![Failed Login](Screenshots/failed-logins.png)

### Account Creation Detection

![Account Created](Screenshots/user-created.png)

### Account Deletion Detection

![Account Deleted](Screenshots/user-deleted.png)

## MITRE ATT&CK Mapping

| Detection | MITRE Technique |
|------------|----------------|
| Failed Login | T1110 |
| Account Creation | T1136 |
| Account Deletion | T1531 |

## Skills Demonstrated

- SIEM Administration
- Log Analysis
- Detection Engineering
- Security Monitoring
- Threat Hunting
- Splunk SPL