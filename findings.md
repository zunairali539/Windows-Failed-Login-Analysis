# Windows Failed Login Analysis — Findings

## Event Information
- **Event ID:** 4625
- **Event Type:** Failed Logon
- **Logon Type:** 2 — Interactive Logon
- **Failure Reason:** Unknown user name or bad password
- **Tool Used:** Windows Event Viewer

## Analysis
Event ID 4625 indicates an unsuccessful login attempt. The failure reason suggests that the username was not recognized or the password was incorrect.

Logon Type 2 generally indicates an interactive login attempt directly at the computer.

## Security Observation
A failed login does not automatically indicate a cyberattack. It may result from a typing mistake or an incorrect password. Additional events and context are needed to determine whether the attempt is suspicious.

## Evidence
A screenshot of the Windows Event Viewer event details has been saved for documentation.

## Conclusion
Windows Security Event ID 4625 can help identify and investigate unsuccessful login attempts during basic security monitoring.

**Project:** Windows Failed Login Analysis
