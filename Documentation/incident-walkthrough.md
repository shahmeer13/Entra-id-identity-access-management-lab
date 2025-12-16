# Identity Incident Walkthrough – Microsoft Entra ID (IAM)
Incident Summary

A Microsoft Entra ID user (SarahAhmed) experienced a sign-in failure due to invalid or missing multi-factor authentication (MFA) methods. The issue prevented successful authentication and required administrative intervention to restore secure access.

This incident simulates a real-world Microsoft 365 Cloud Identity Help Desk ticket involving MFA remediation and account recovery.

# Environment

• Platform: Microsoft Entra ID (Azure AD)

• Tenant: Default Directory

• Admin Role: Global Administrator

• User Type: Cloud-only user

• Authentication: MFA-enabled

# Problem Description

The affected user had no usable authentication methods registered, resulting in MFA failure during sign-in.
An initial review of the account confirmed that the existing authentication methods were either invalid or misconfigured.

Sign-in logs showed no successful interactive sign-ins, indicating an authentication block rather than a password issue.

# Investigation & Diagnosis

The following checks were performed:

• Reviewed user Authentication Methods

• Verified MFA registration state

• Checked Sign-in Logs for authentication attempts

• Confirmed no Conditional Access policies were applied (license limitations)

Root cause was identified as broken MFA registration, a common issue after device changes or incomplete MFA setup.

# Remediation Actions

1. To restore access securely, the following steps were taken:

2. Forced MFA re-registration to clear invalid authentication methods

3. Issued a Temporary Access Pass (TAP) to enable secure recovery

4. Guided user to re-register MFA on next sign-in

Ensured no permanent bypass of MFA controls

# Verification & Validation

• Confirmed authentication method reset completed successfully

• Reviewed Sign-in Logs post-remediation

• Verified MFA flow was functional, and user access was restored

No account disabling or password resets were required.
