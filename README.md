# SSH Authentication Failure Detection Using Wazuh SIEM

## Project Overview
This project demonstrates how to monitor and detect SSH authentication failures using Wazuh SIEM and Ubuntu Linux.

The objective is to simulate an unauthorized SSH login attempt, collect authentication logs, and investigate security alerts through the Wazuh dashboard.

## Tools Used
- Ubuntu Linux
- Wazuh SIEM
- Windows PowerShell
- OpenSSH
- Wazuh Threat Hunting

## Lab Environment
- Ubuntu SOC Lab: Wazuh Manager
- Windows: SSH client
- SSH authentication monitoring

## Practical Implementation

1. Installed and configured Wazuh SIEM.
2. Verified Wazuh services were active.
3. Connected from Windows PowerShell to the Ubuntu SSH server.
4. Simulated an SSH login attempt using an invalid username.
5. Investigated SSH authentication logs in Ubuntu.
6. Verified the security events in Wazuh Threat Hunting.

## Detection Results

Wazuh successfully detected SSH authentication failures.

- Detection Rule ID: 5710
- Alert Description: Attempt to login using a non-existent user
- Alert Level: 5
- Log Source: SSHD
- Event Category: Authentication Failure

## Screenshots

Evidence is available in the screenshots folder:

1. 01-SSH-Failed-Login.png
2. 02-Wazuh-Threat-Hunting.png
3. 03-Wazuh-Rule-5710.png

## Key Learnings

- Understanding SSH authentication.
- Investigating Linux authentication logs.
- Monitoring security events using Wazuh.
- Identifying failed login attempts.
- Understanding Wazuh detection rules.
- Performing basic SOC alert investigation.

## Conclusion

This hands-on project helped me understand how a SOC Analyst monitors SSH authentication events, investigates failed login attempts, and uses Wazuh SIEM to identify potential security threats.

## Author
Maniraj
Aspiring SOC Analyst
