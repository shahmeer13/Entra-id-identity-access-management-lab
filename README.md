# 🔐 Microsoft Entra ID – Identity & Access Management Lab

📌 Overview

This project is a hands-on Identity & Access Management (IAM) lab built using Microsoft Entra ID (Azure Active Directory).
It simulates real-world IT Help Desk and Cloud Identity scenarios, including authentication failures, MFA issues, and administrative recovery.

The lab follows an incident-based approach:

1. Build a working cloud identity environment

2. Intentionally break authentication and access

3. Diagnose issues using logs and admin tools

4. Restore access like a real IT technician

This mirrors how Tier 1–2 Help Desk and Cloud Support Engineers handle Microsoft 365 identity incidents.

# 🧰 Technologies & Tools

• Microsoft Entra ID (Azure AD)

• Microsoft 365 Admin Center

• Multi-Factor Authentication (MFA)

• Temporary Access Pass (TAP)

• Sign-in Logs & Audit Logs

# 🎯 Lab Objectives

• Create and manage cloud users

• Implement group-based access control

• Simulate MFA and authentication failures

• Perform admin-side identity remediation

• Validate fixes using sign-in logs

# 🧪 Lab Walkthrough

1️⃣ Tenant & Admin Context

• Verified Microsoft Entra tenant configuration

• Confirmed Global Administrator role and permissions

• Ensured correct directory context before proceeding

📁 ScreenShots/1.Tenant & Admin Context.md


2️⃣ User Management

• Created multiple cloud users

• Verified user principal names and account status

• Simulated real end-user identities for troubleshooting

📁 ScreenShots/2.User Management.md


3️⃣ Group-Based Access Control

• Created department-based security groups:

• IT Support

• HR

• Finance

• Sales

• Assigned users to groups to simulate role-based access

📁 ScreenShots/3.Groups.md

4️⃣ Incident Simulation & Admin Fix

• Forced MFA re-registration

• Removed broken authentication methods

• Issued Temporary Access Pass (TAP) for account recovery

• Restored secure user access as an administrator

📁 ScreenShots/4.Admin Fix.md


5️⃣ Verification & Validation

• Reviewed Sign-in Logs after remediation

• Confirmed successful authentication recovery

• Ensured no repeated authentication failures

📁 ScreenShots/5.Verification.md

# 🧠 Key Skills Demonstrated

• Identity & access troubleshooting

• MFA remediation and recovery

• User and group lifecycle management

• Log-based diagnosis (Sign-in & Audit logs)

• Professional IT documentation practices
