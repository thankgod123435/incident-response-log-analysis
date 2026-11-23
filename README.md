# Incident Response and Log Analysis

## Project Overview
This project demonstrates basic Windows incident response and security log analysis using Windows Event Viewer.

## Objectives
- Understand Windows Security logs.
- Identify successful and failed logon events.
- Investigate repeated failed login attempts.
- Interpret Windows Security Event IDs.

## Tools Used
- Windows 11
- Windows Event Viewer
- Windows Security Logs

## Events Investigated

| Event ID | Description |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4672 | Special privileges assigned to a new logon |

## Investigation Findings
- More than 50 failed logon events (Event ID 4625) were observed.
- Events occurred across several days during November 2026.
- Failure reason: Unknown user name or bad password.
- Logon Type: 2 (Interactive).
- Workstation Name: Local computer.
- Logon Process: Advapi.
- Authentication Package: Negotiate.
- The account referenced was the Windows account.

## Initial Assessment
The repeated failed logon events require further investigation. The available evidence does not establish whether the attempts were malicious or caused by an application or normal sign-in activity.

## Learning Outcomes
- Navigating Windows Event Viewer.
- Filtering Windows Security events.
- Understanding authentication events.
- Recording and interpreting security findings.
- Practising basic incident documentation.

## Disclaimer
This project was performed on my own Windows computer for educational and defensive cybersecurity learning.

## Author
Cybersecurity Student
