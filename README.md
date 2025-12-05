# Jira Service Management – Tier 1 Help Desk Ticketing & Workflow Lab

## Overview
This project demonstrates a complete Tier 1 Help Desk ticket lifecycle using **Jira Service Management** integrated with a **Hybrid Identity environment** consisting of:

- On-Premises Active Directory (AD DS)
- Microsoft Entra ID (Cloud Sync)
- Microsoft 365
- Jira Service Management (Cloud)

The lab simulates a real MSP-style authentication incident: a user unable to sign in due to a password expiration. The full lifecycle—inbound request, triage, troubleshooting, verification, communication, and closure—is documented end-to-end.

---

## Skills Demonstrated
- Jira Service Management configuration & queue management  
- ITIL-aligned ticket lifecycle (To Do → In Progress → Pending → Done)  
- Hybrid identity troubleshooting (AD DS → Entra ID → M365)  
- Active Directory password reset operations  
- Secure credential handling & documentation  
- Professional end-user communication  
- Entra ID sign-in log analysis  
- Technical reporting & audit trail documentation  

---

# Lab Walkthrough

## Phase 1 — Jira Service Management Setup

### Step 1 — Created Jira Service Management project  
![Jira Summary Page](screenshots/01-Jira-Summary-Page.png)

### Step 2 — Configured service desk structure & queues  
![Empty Jira Queues](screenshots/02-Empty-Jira-Queues.png)

### Step 3 — Created structured request types & portal groups  
![Request Types](screenshots/03-Created-New-Request-Types.png)  
![Portal View](screenshots/04-Customer-Portal-MS365-RequestTypes.png)

---

## Phase 2 — Ticket Lifecycle & Workflow

### Step 4 — Implemented ITIL-aligned workflow  
Workflow: **Start → To Do → In Progress → Pending → Done**

![Workflow In Progress](screenshots/06-ticket-workflow-updated-inprogress.png)

---

## Phase 3 — Authentication Incident (Hybrid AD Password Reset)

### Step 5 — User submits password reset request  
![User Submitted Ticket](screenshots/05-enduser-submitted-ticket-assignedtotech.png)

### Step 6 — Ticket triage & assignment  
![Ticket In Progress](screenshots/06-ticket-workflow-updated-inprogress.png)

### Step 7 — Technician adds initial internal troubleshooting note  
![Internal Note 1](screenshots/07-first-internalnote-inprogress.png)

### Step 8 — Password reset completed in on-prem Active Directory  
![AD Password Reset](screenshots/08-password-reset-onprem-fix.png)

### Step 9 — Updated internal documentation  
![Internal Note 2](screenshots/09-second-internalnote-fixed.png)

### Step 10 — Ticket moved to Pending (awaiting user confirmation)  
![Pending State](screenshots/10-workflow-pending.png)

### Step 11 — Public message sent to end user  
![User Response](screenshots/11-user-response.png)

---

## Phase 4 — Validation & Ticket Closure

### Step 12 — Verified successful authentication via Entra ID  
![Entra Sign-In Logs](screenshots/12-userlogins-documented-entraid.png)

### Step 13 — Internal note confirming login success  
![Internal Note 3](screenshots/13-third-internalnote-userloggedin.png)

### Step 14 — User confirms full resolution  
![User Confirmation](screenshots/14-user-resolution-documented.png)

### Step 15 — Final customer-facing confirmation message  
![Final Public Response](screenshots/15-professional-response-final.png)

### Step 16 — Final internal note + closure summary  
![Final Internal Note](screenshots/16-final-internalnote-closed.png)

### Step 17 — Ticket transitioned to Done  
![Ticket Done](screenshots/17-done-workflow-showcased.png)

---

# Security Practices Enforced
- No passwords or sensitive data stored in ticket comments  
- Strict separation of public comments and internal troubleshooting notes  
- Temporary credentials shared only via secure out-of-band method  
- AD DS and Entra ID authentication verified before closure  
- Full audit trail maintained within Jira  

---

# Final Outcome
- User fully regained access to Microsoft 365 services  
- Password reset successfully propagated across AD DS → Entra ID → M365  
- Ticket resolved using ITIL best practices and MSP-style workflow  
- Professional communication maintained throughout  
- Demonstrates real-world Tier 1 help desk operational skill  

---

# Key Takeaways
This lab validates hands-on capability in:

- Jira Service Management administration  
- Tier 1 support ticket handling  
- Hybrid identity troubleshooting  
- Secure documentation & communication  
- Real MSP-style user support workflows  

Directly applicable to roles such as:

- IT Support Technician  
- Help Desk Analyst  
- MSP Tier 1/2 Technician  
- Junior System Administrator  
- Cloud Support Associate  
