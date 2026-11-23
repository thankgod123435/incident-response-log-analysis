# Incident Response Report

## 1. Incident Overview
A review of Windows Security logs was conducted using Event Viewer on a Windows 11 computer.

## 2. Investigation Details
- Log source: Windows Security
- Event ID: 4625
- Event description: Failed logon
- Total observed events: 98
- Observation period: November 2026

## 3. Evidence Collected
- Multiple failed logon events were identified.
- Events occurred across several days.
- Failure reason: Unknown user name or bad password.
- Logon Type: 2 (Interactive).
- Workstation Name: Local computer.
- Logon Process: Advapi.
- Authentication Package: Negotiate.

## 4. Initial Assessment
The repeated failed logon events require further investigation. The available evidence does not establish whether the activity was malicious or caused by normal system or application activity.

## 5. Recommended Defensive Actions
- Continue monitoring Windows Security logs.
- Review unexpected authentication activity.
- Check applications that may be using outdated credentials.
- Maintain strong account security.
- Keep Windows security updates current.

## 6. Conclusion
This exercise provided practical experience in identifying and documenting failed authentication events using Windows Event Viewer.

## 7. Disclaimer
This investigation was conducted on my own computer for educational and defensive cybersecurity purposes.
