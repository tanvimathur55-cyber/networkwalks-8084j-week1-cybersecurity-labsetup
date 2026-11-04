# networkwalks-8084j-week1-cybersecurity-labsetup
NetworkWalks CyberSecurity lab setup


## Project Overview
The purpose of this assignment is to provide a report about the Cybersecurity Internship task that I carried out in Week 1 for the company Networkwalks, which was setting up a cybersecurity lab through the use of Virtualbox and Kali Linux.

## Objectives
- Install and configure VirtualBox.
- Set up Kali Linux as a virtual machine.
- Configure the Kali VM resources.
- Document the setup process and troubleshooting steps.
- Maintain a controlled environment for cybersecurity learning and testing.

## My Lab Environment

| Component | Configuration |
|---|---|
| Host OS | **10.0.26200 Build 26200** |
| CPU | **CPU Intel(R) Core(TM) Ultra 7 155H** |
| Host RAM | **16.0 GB** |
| Virtualization Software | VirtualBox **Version 7.2.16 r174877 (Qt6.8.0 on windows)**|
| Guest OS | Kali Linux **Debian (64-bit)** |
| Kali RAM | **4 MB ---> 16364 MB** |
| Kali CPU | **1 CPU ---> 32 CPUs** |
| Network Adapter | **NAT Network** |


### 1. Lab Setup Procedure

### Prepare the Host System
Prior to setting up the virtual machine, I ensured that there were enough resources on the system to run Kali Linux, along with hardware virtualization capabilities.
<img width="1242" height="907" alt="image" src="https://github.com/user-attachments/assets/767737d2-5b5b-4d14-97e7-a19240c4fdfe" />
<img width="1907" height="997" alt="image" src="https://github.com/user-attachments/assets/30d2aae3-9021-411a-9a91-dfcbcf2583cc" />

## 2. Installing 7-Zip
I began with the installation of 7-Zip as it would be needed for extraction of the Kali Linux virtual machine which is in a compressed format.
<img width="1462" height="872" alt="image" src="https://github.com/user-attachments/assets/13b564ae-7fcb-4087-97bc-5fb63bb3c9b8" />


## 3. Installing VirtualBox
VirtualBox was installed as the virtualization platform used to run Kali Linux.
After installation, I opened VirtualBox and verified that the application could create and manage virtual machines.
<img width="1017" height="407" alt="image" src="https://github.com/user-attachments/assets/8d3e615e-f5a9-4e24-92da-847674a07569" />

### 4. Import / Create the Kali Linux VM
VirtualBox was used to carry out virtualization of Kali Linux. After completion of the setup process, I started VirtualBox and ensured that all the processes were running smoothly by making sure it could create and manage virtual machines.

**VM configuration:**

- RAM: **4 MB ---> 16364 MB**
- CPU: **1 CPU ---> 32 CPUs**
- Network adapter: **Nat Network**

- <img width="2880" height="1796" alt="image" src="https://github.com/user-attachments/assets/b1b5d019-d058-4c04-a8f3-a30dee339bc0" />
- <img width="1826" height="1170" alt="image" src="https://github.com/user-attachments/assets/c71e6da9-d17d-4821-aa2d-4985388e731a" />

## 5. Configuring the Virtual Network
VirtualBox Manager was configured and provided with dedicated CPU, memory, and virtual networking capabilities to create an effective Kali Linux environment.
Network Type: NAT Network
Network Name: Natnetwork
IPv4 Network: Manual
DHCP: Enabled

Configured network architecture  which created a well-regulated setting for the use of virtual machines in the lab.
 <img width="1832" height="1168" alt="Screenshot 2026-09-11 180609" src="https://github.com/user-attachments/assets/feb82417-fa8d-49e1-b5b4-9a756a03b277" />

## 6.Problems Encountered & Troubleshooting
One of the issues I encountered during the setup was the **Network** option shown in the tutorial was not appearing in my VirtualBox Manager. 
This meant I could not immediately follow the same network configuration steps shown in the guide.
I investigated the VirtualBox installation and configuration rather than assuming that the tutorial interface would be identical to my installation. As in the terminal i was adding my commands as the version which i have is 2026 and it needed some commands in order to run with pinging as well.
But i managed to configure it by myself

**What I learned:**
Functions and management capabilities of VirtualBox  vary depending on its version, installation status and additional modules that are enabled or not. While using a tutorial, sometimes the user interface doesn’t match and therefore, needs to be verified.

##7. Final Working Lab
Despite the number of tries, the following results were obtained for the entry into the browser.
<img width="1267" height="796" alt="image" src="https://github.com/user-attachments/assets/1dcb7a5e-8918-4ce2-b977-b0b4eb9c14df" />


I have added few screenshots of my work above which includes in the README at various points during the lab setup process, starting from installation all the way to the working lab.


## What I Learned from Week 1 Project
This week's task gave me some insights into this lab and hands-on experience with VirtualBox and setting up Kali Linux. It taught me how virtual machines operate, how to configure hardware allocations, and how the networking in VirtualBox works. In addition, I realized that sometimes even when you follow a guide, things don't always turn out exactly as described because you have to configure the settings yourself and learn from that. I would say it was a nice start and a strong introduction into the environment, and looking forward to be learning through this internship.

## Security & Ethical Use
This lab is intended strictly for **authorized cybersecurity learning and testing**.
Any penetration testing, scanning, exploitation, or other security activity performed using this environment should only target systems for which I have explicit permission.
The purpose of the lab is to provide a controlled environment for learning without intentionally affecting systems or networks that I do not own or have authorization to test.

## Tools & Technologies

- Windows
- VirtualBox
- Kali Linux
- 7-Zip
  
## Project Information
**Program:** Cybersecurity Internship — Networkwalks  
**Batch:** B084J 
**Week:** 1  
**Project:** Cybersecurity Lab Environment Setup

**Author:** Tanvi Mathur
## Disclaimer
This repository documents a personal cybersecurity learning environment created for educational and authorized testing purposes. No unauthorized systems should be targeted using the techniques or tools discussed in this project.












