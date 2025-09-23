# Lab 2 — Windows Group Policy & AD Basics

**Goals:**  
- Explore Local Group Policy Editor (gpedit.msc).  
- Configure password complexity and length policies.  
- Test password requirements on a local account.  
- Enable auditing of logon events.  
- Review Event Viewer for success/failure logons.  
- (Optional) Install RSAT tools for Active Directory preview.  

---

## What I Did

- Confirmed system edition using `winver` (Windows 10 Pro).  
- Opened **Local Group Policy Editor** and set:  
  - Minimum password length = 8  
  - Password must meet complexity requirements = Enabled  
- Created a test local user and attempted weak vs strong passwords.  
- Enabled **Audit logon events (Success & Failure)** in Group Policy.  
- Triggered a failed logon (wrong password) and then a successful logon.  
- Verified logs in **Event Viewer → Security** (Event ID 4625 for failure, 4624 for success).  
- (Optional) Installed **RSAT: Active Directory tools** for later labs.  

---

## Evidence

### Step 1 — Verify Windows Pro edition
![Winver showing Pro](media/lab02_step01_winver.png)

### Step 2 — Configure password policy in Group Policy Editor
![Password policy settings](media/lab02_step02_password-policy.png)

### Step 3 — Test weak vs strong passwords
![Password change attempt failed](media/lab02_step03_failed-password.png)  
![Password change success](media/lab02_step03_success-password.png)

### Step 4 — Enable auditing of logon events
![Audit policy enabled](media/lab02_step04_audit-policy.png)

### Step 5 — View logon events in Event Viewer
![Event 4625 - failed logon](media/lab02_step05_event-4625.png)  
![Event 4624 - successful logon](media/lab02_step05_event-4624.png)

### Step 6 — (Optional) RSAT installed
![RSAT feature installed](media/lab02_step06_rsat.png)

---

## Skills Demonstrated
- Windows Pro administration.  
- Local Group Policy configuration.  
- Password policy enforcement.  
- User account management & testing.  
- Logon event auditing & log review.  
- Familiarity with RSAT/Active Directory tools.  
