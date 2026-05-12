SOCForge: Red vs Blue AD-SIEM Lab
Overview

SOCForge is a SOC-focused cybersecurity lab environment designed to simulate real-world enterprise security monitoring and attack detection scenarios using Active Directory and Wazuh SIEM.
The project focuses on Blue Team monitoring, Red Team attack simulation, threat detection, custom rule creation, event analysis, and incident monitoring within an Active Directory infrastructure.

This lab was developed to gain practical experience in Security Operations Center (SOC) workflows and understand how SIEM solutions help organizations detect and respond to cybersecurity threats in real time.

Objectives
Build a secure Active Directory lab environment
Configure centralized log monitoring using Wazuh SIEM
Simulate brute-force and authentication-based attacks
Detect malicious activities through event logs
Create and test custom SIEM detection rules
Perform Red Team and Blue Team security analysis
Understand SOC workflows and incident monitoring processes
Technologies Used
Technology	Purpose
Wazuh SIEM	Security monitoring and event correlation
Active Directory	Identity and access management
Windows Server	Domain Controller environment
Ubuntu Server	Wazuh Manager installation
Windows 11	Wazuh Dashboard access
Sysmon	Advanced Windows event logging
Atomic Red Team	Attack simulation and testing
PowerShell	Administrative and security tasks
Lab Architecture
+-------------------+
|   Attacker System |
+-------------------+
          |
          v
+-------------------+
| Windows Server AD |
| Domain Controller |
+-------------------+
          |
          v
+-------------------+
| Wazuh Agent       |
+-------------------+
          |
          v
+-------------------+
| Ubuntu Wazuh SIEM |
| Manager & Indexer |
+-------------------+
          |
          v
+-------------------+
| Wazuh Dashboard   |
| Windows 11        |
+-------------------+
Features
Real-time security monitoring
Active Directory log collection
Brute-force attack detection
Failed login event monitoring
Custom Wazuh rule creation
Security event correlation
Red Team attack simulation
Blue Team incident monitoring
Alert generation and analysis
SOC workflow simulation
Attack Simulation

The lab includes controlled attack simulations to test the detection capability of the SIEM environment.

Simulated Attacks
Brute-force login attempts
Failed authentication events
Unauthorized access attempts
Suspicious PowerShell activity
Reconnaissance activities
Detection and Monitoring

The following activities were monitored through Wazuh SIEM:

Windows Event Logs
Authentication failures
User account activities
PowerShell execution logs
Sysmon process creation events
Security alerts and rule triggers

Custom rules were added to improve detection accuracy for brute-force and suspicious authentication behavior.

SOC Workflow
Generate attack activity
Collect logs from endpoints
Forward logs to Wazuh Manager
Analyze events using Wazuh Dashboard
Detect suspicious activities
Trigger alerts through custom rules
Investigate incidents
Document findings and responses
Key Learning Outcomes
Understanding SIEM architecture and workflows
Hands-on experience with Wazuh SIEM
Active Directory security monitoring
Real-time event analysis
Threat detection and incident response
Log analysis and event correlation
Rule creation and tuning
SOC Analyst practical workflow understanding
Screenshots
Wazuh Dashboard

Add screenshot here

Brute-Force Detection Alert

Add screenshot here

Custom Rule Configuration

Add screenshot here

Active Directory Environment

Add screenshot here

Future Improvements
Integration with XDR solutions
Automated incident response
Threat intelligence integration
Email alerting system
Advanced malware detection
Dashboard customization
Machine learning-based anomaly detection
Conclusion

SOCForge demonstrates how SIEM solutions and Active Directory environments can be integrated to create a practical SOC monitoring lab for cybersecurity learning and threat detection.
The project helped in understanding enterprise-level monitoring, attack detection, log analysis, and incident response processes through hands-on implementation.

Author

Yuvaraj M

Cybersecurity Enthusiast | SOC Analyst Aspirant | SIEM & Threat Monitoring Learner
