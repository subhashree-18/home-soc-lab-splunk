# Multiple Failed Login Attempts

## Objective
Detect brute-force login attempts.

## SPL Query

```spl
source="WinEventLog:Security" EventCode=4625
| stats count by Account_Name, Source_Network_Address
| where count > 3
```

## MITRE ATT&CK

T1110 - Brute Force

## Findings

Multiple failed authentication attempts were observed from the same source.