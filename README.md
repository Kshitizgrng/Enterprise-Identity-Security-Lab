# 🛡️ Enterprise Identity, Security & Automation Lab

## 📌 Executive Summary
Designed and deployed a resilient, enterprise-grade Identity Infrastructure using **Windows Server 2022**. The project simulated a mid-sized organization (`corp.vancity.local`) undergoing a rapid expansion.

## 📸 Project Gallery

### Infrastructure & Redundancy
*Dual Domain Controllers (DC-01 & DC-02) syncing via Active Directory Sites & Services.*
![Infrastructure](images/infrastructure.png)

### Automation Logic
*PowerShell script utilizing logic loops to onboard 270+ users in under 60 seconds.*
![Automation Script](images/automation_script.png)

### Directory Structure (Scale)
*Verified onboarding of 270+ users across multiple departments (HR, IT, Sales).*
![Directory Users](images/directory_users.png)

### Security Hardening (Lockout Policy)
*Account Lockout Threshold set to 5 attempts to prevent Brute Force attacks.*
![Lockout Policy](images/lockout_policy.png)

### Forensic Monitoring (Audit Logs)
*Event Viewer capturing "Audit Failure" (Event 4625) for security analysis.*
![Audit Logs](images/audit_logs.png)

### Operational Excellence (GPO)
*Group Policy Configuration mapping the S: Drive for all employees.*
![GPO Config](images/gpo_config.png)
