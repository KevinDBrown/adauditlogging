# 🔐 Active Directory Logging & Auditing

## 📝 Project Overview
This project demonstrates how to enable and monitor audit logging in Active Directory using Group Policy, Event Viewer, and simulated user activity. It's designed to showcase foundational skills for cybersecurity and IT operations.

## 🛠️ Tools Used
- Windows Server 2019 (Domain Controller)
- Active Directory Users and Computers (ADUC)
- Group Policy Management Console
- Event Viewer
- PowerShell

## ⚙️ Setup Summary
1. Configure a lab environment with a Domain Controller and client machine
2. Create a Group Policy Object (GPO) with audit policy settings
3. Link the GPO and simulate user logins, account creations, and group changes
4. Review security logs in Event Viewer

## 🔍 What I Learned
- How to track security-relevant AD events using Event IDs (4625, 4720, 4732, etc.)
- Practical use of GPOs for enforcing audit policies
- Basics of threat detection in a Windows environment

## 📸 Screenshots
- GPO setup
- Event Viewer logs
- Simulated attack activity

## 🚀 Next Steps
- Forward logs to a SIEM (Splunk, Wazuh)
- Create alert rules for suspicious behavior
