# Windows Lab 2 — User Accounts, Lockout Policy, and Password Policy

## Overview
This lab demonstrates creating and managing users, testing logons, configuring account lockout policies, and enforcing password complexity requirements on Windows 10 Pro.

---

## 🔹 Steps & Screenshots

### Step 1 — System Info
![Windows version](step1_winver.png)  
*Verified Windows version for lab environment.*

### Step 2 — Configure Password Policy
![Password policy settings](step2_password_policy_screen_with_settings_applied.png)  
*Applied password policy settings via Local Security Policy.*

### Step 3a — Weak Password Attempt
![Weak password rejected](step3a_weak_password_attempt_error.png)  
*Weak password rejected per policy.*

### Step 3b — Strong Password Success
![Strong password accepted](step3b_strong_password_success.png)  
*Strong password accepted successfully.*

### Step 4 — Create New User
![Create TestUser2](step4_create_new_user_in_active_directory.png)  
*Created new user (TestUser2).*

### Step 5a — Failed Logon Event
![Event ID 4625](step5a_Event_4625_failed_logon.png)  
*Event ID 4625 recorded for failed logon attempt.*

### Step 5b — Successful Logon Event
![Event ID 4624](step5b_Event_4624_successful_logon.png)  
*Event ID 4624 recorded for successful logon.*

### Step 6 — Account Lockout
![Account locked after invalid attempts](step6_account_lockout_policy_test.png)  
*Account locked after 3 invalid attempts.*

### Step 7a — Password Policy Enforcement (Fail)
![Password policy fail](step7a_password_policy_enfrcmnt_fail.png)  
*Password rejected for not meeting complexity requirements.*

### Step 7b — Password Policy Enforcement (Success)
![Password policy success](step7b_password_policy_enfrcmnt_success.png)  
*Password accepted after meeting complexity requirements.*

---

## 🔑 Key Skills Practiced
- Local user and group management  
- Password and account lockout policy configuration  
- Security event log analysis (Event IDs 4624 & 4625)  
- Troubleshooting locked accounts & password resets  

---

## 📌 Next Lab
Lab 3 — Group Policy Objects (GPO) and domain join tests.

