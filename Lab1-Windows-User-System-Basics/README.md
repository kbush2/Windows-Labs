# Lab 1 — Windows User & System Basics

**Goals:**  
- Create and manage local users.  
- Generate and review failed logon events.  
- Install/uninstall software.  
- Verify networking with NAT vs Bridged.  
- Practice device management basics.  

## What I Did
- Created local user `labuser` using `net user`.  
- Generated a failed logon and captured Event ID 4625 in Event Viewer.  
- Installed and uninstalled Notepad++.  
- Verified IP configuration and connectivity with `ipconfig` and `ping`.  
- Compared NAT vs Bridged modes in VirtualBox.  

## Evidence

## Evidence

## Evidence

### Step 1 — Created local user
![Created user](media/01_net-user-labuser.png)

### Step 2 — Failed logon captured in Event Viewer
![Failed logon Event 4625](media/02_wrong-password-attempt.png)

### Step 3 — Installed software
![Installed 7-zip](media/04_Installed-App-List.png)

### Step 4 — Verified connectivity (ping)
![Ping 8.8.8.8](media/07_ping-8888.png)

### Step 5 — NAT network mode
![NAT connectivity](media/08_NAT-connectivity.png)

### Step 6 — Bridged network mode
![Bridged connectivity](media/09_Bridged-connectivity.png)



## Skills Demonstrated
- Windows account administration  
- Event log analysis (Security/System)  
- Software installation/removal  
- Network troubleshooting (NAT vs Bridged)  
- Device management basics  
