# Microsoft 365 Security & Compliance Implementation

This repository documents my hands-on experience configuring and managing core Microsoft 365 security and compliance features. The goal was to secure a remote-first organization using Microsoft 365 E5 tools, while aligning with data protection and cybersecurity best practices (e.g., ISO 27001, NDPR).

---

## 🔐 Key Configurations

### 1. Anti-Phishing Policies
Implemented using the Microsoft 365 Defender portal:
- Created a baseline phishing protection policy for all users.
- Configured a higher-priority policy for executive mailboxes.
- Enabled impersonation and spoof intelligence.
- Deployed the “Report Message” Outlook add-in for staff phishing submissions.

### 2. Sensitivity Labels (Microsoft Purview)
- Created and published labels for Internal, Confidential, and Public content.
- Enforced encryption and sharing restrictions for sensitive content.
- Integrated with Outlook, Word, Excel, SharePoint, and OneDrive.

### 3. User Management & Licensing
- Managed Microsoft 365 E5 licenses using the Microsoft 365 Admin Center.
- Assigned licenses based on department roles.
- Created and managed Microsoft 365 Groups and Azure AD access groups.
- Applied Conditional Access policies to enforce MFA.

### 4. SharePoint Site Creation
- Designed a structured departmental SharePoint site for secure document collaboration.
- Applied permission groups for HR, Finance, and Admin roles.
- Restricted external sharing and monitored access logs.

### 5. Content Search (Microsoft Purview)
- Performed organization-wide content searches to support internal audits and investigations.
- Configured role-based access to eDiscovery features.
- Ensured logs were maintained for auditing and compliance review.

---

## 🛠️ Tools Used

- Microsoft 365 Admin Center  
- Microsoft Defender for Office 365  
- Microsoft Purview (Compliance Center)  
- SharePoint Online  
- Azure AD  
- Power Automate (for alerting/workflows)  

---

## ✅ Real-World Use Cases

- Phishing protection for high-value mailboxes  
- Secure document collaboration across remote teams  
- Sensitive data classification for compliance reporting  
- Lifecycle management of user licenses and access groups  
- Incident support through eDiscovery and audit logging

---

## 📄 Files Included

- `anti-phishing-policy.md` – Real-world phishing policy configuration
- `sensitivity-labels.md` – Label structure, application, and controls
- `user-licensing.md` – License and user group assignment process
- `sharepoint-site.md` – Permissions and governance for SharePoint sites
- `content-search.md` – Process for performing secure content searches

---

## 👩🏽‍💻 About Me

I'm a cybersecurity analyst with hands-on experience in Microsoft 365 security, compliance, and data governance.
I assisted with ISO 27001 recertification efforts and design practical security controls for modern, remote-first organizations.

> This project is based on real implementations, with identifying details redacted to maintain confidentiality.

---

