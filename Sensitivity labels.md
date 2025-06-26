# Sensitivity Labels Configuration – Microsoft Purview

This document outlines the sensitivity labels and label policies implemented using Microsoft Purview to enforce data classification and protection across Microsoft 365 apps.

---

## 🎯 Objective

To help the organization classify, protect, and govern sensitive information in emails and documents by using custom sensitivity labels and enforcing default labeling across Exchange and Office apps.

---

## 🛠️ Tools Used

- Microsoft Purview Compliance Center  
- Microsoft 365 Apps (Outlook, Word, Excel, SharePoint, OneDrive)

---

## 🏷️ Labels Created

### 1. **Public**
- Intended for content meant to be openly shared inside or outside the organization.
- No restrictions on sharing or forwarding.

### 2. **Confidential – Internal Only**
- For internal use only; cannot be shared externally.
- Access restricted to authenticated employees.

### 3. **Confidential – Restricted**
- For highly sensitive data (e.g., HR, finance).
- Enforces encryption.
- Limits access to specific groups.
- Prevents downloading, copying, or printing.

---

## 📜 Public Use Label Policy

A default labeling policy was created to enforce the use of the **Public** label for general content and emails. This ensures that all Exchange users have their messages and documents labeled appropriately, even if no manual action is taken.

### 🔧 Key Settings:
- **Published label**: Public
- **Applies to**: Exchange email (all accounts)
- **Label is mandatory for**: Documents and emails
- **Default label**: Public

---

## 🧠 Lessons Learned

- Default labeling helps reduce human error and ensures every email/document has a classification.
- Mandatory labeling encourages users to consider sensitivity before sharing.
- Labels can be expanded later to include automatic classification using sensitive info types.

---

> **Note:** This implementation was based on real-world Microsoft Purview configuration. Screenshots have been sanitized to remove sensitive or organizational information.
