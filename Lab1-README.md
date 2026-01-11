\# Lab 1: Microsoft 365 Security Hardening – Anti-Phishing Protection



\## Objective

Configure and validate Microsoft Defender for Office 365 anti-phishing protections in a Microsoft 365 tenant.



---



\## Step 1: Access Microsoft Defender Portal

1\. Sign in to Microsoft 365 Admin Center.

2\. Navigate: Security → Email \& collaboration → Policies \& rules → Threat policies → Anti-phishing.



Screenshot: screenshots/defender-dashboard.png



---



\## Step 2: Create Custom Anti-Phishing Policy

1\. Click Create.

2\. Name policy: Enhanced Anti-Phishing Protection.

3\. Assign to test users.

4\. Enable Mailbox intelligence, User and Domain impersonation protection.

5\. Set action: Quarantine.



Screenshot: screenshots/anti-phishing-policy-settings.png



---



\## Step 3: Advanced Protection

1\. Enable Spoof intelligence and Safety tips.

2\. Set High-confidence thresholds.

3\. Enable reporting.



Screenshot: screenshots/advanced-protection-settings.png



---



\## Step 4: Save \& Apply

1\. Save policy.

2\. Confirm status Enabled.



Screenshot: screenshots/policy-enabled.png



---



\## Step 5: Validation

1\. Use Defender test messages or simulations.

2\. Confirm emails are quarantined.

3\. Review alerts.



Screenshot: screenshots/quarantine-validation.png



