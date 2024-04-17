<h1>Network Enumeration with enum4linux: (Discovering Windows and Samba)</h1>



<h2>Description</h2>
This repository contains scripts and documentation for using enum4linux, a powerful tool for enumerating information from Windows and Samba systems on a network. Learn how to install, configure, and run enum4linux to gather valuable insights into network shares, user accounts, group memberships, and more. Enhance your network reconnaissance and security assessment capabilities with enum4linux.
<br />
<h2>Overview</h2>
enum4linux is a tool primarily used for enumerating information from Windows and Samba systems. It is commonly used by security professionals and system administrators to gather valuable information about network shares, user accounts, group memberships, policies, and more from Windows and Samba servers. Here's an overview of what enum4linux can check for:

1. NetBIOS Information: enum4linux can retrieve NetBIOS information, including the NetBIOS name, domain/workgroup name, and MAC address of the target system.

2. Shares Enumeration: It can enumerate network shares available on the target system, including their names, permissions, and configurations.

3. User Enumeration: enum4linux can enumerate user accounts on the target system, including their names, SIDs (Security Identifiers), and other related information.

4. Group Enumeration: It can enumerate groups and group memberships on the target system, including group names, SIDs, and membership information.

5. Password Policy Enumeration: enum4linux can retrieve password policy information from the target system, including password length requirements, complexity rules, and lockout policies.

6. System Information: It can gather general system information from the target system, such as the operating system version, system architecture, and domain controller information.

Overall, enum4linux provides valuable insights into the configuration and security posture of Windows and Samba systems, helping security professionals identify potential vulnerabilities and security misconfigurations. It is commonly used as part of security assessments, penetration tests, and network reconnaissance activities to gather intelligence about target systems.


<h2>Utilities Used</h2>

 - <b>enum4linux</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b>
 

<h2>Program walk-through:</h2>

<p align="center">
Downloaded and Configured enum4linux: <br/>
<img src="https://i.imgur.com/luWEaup.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
While trying to set it up I received a  message that says “Dependency info: you will need to have the Samba package installed as this script is basically just a wrapper around rpcclient, net, nmblookup, and smbclient”. This means that the script relies on functionalities provided by the Samba package to work properly. This package includes tools and utilities like rpcclient, net, nmblookup, and smbclient, which are essential for various network-related tasks. To ensure the script functions correctly, it’s necessary to have the Samba package installed on your system.: <br/>
<img src="https://i.imgur.com/h2rLa1o.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
 <br/>
<img src="https://i.imgur.com/5m6Org1.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Successfully installed Samba (smbclient): <br/>
<img src="https://i.imgur.com/i5cva51.jpeg" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Confirm if Samba (smbclient) is successfully installed in your ubuntu using the parameter --version: <br/>
<img src="https://i.imgur.com/Co7r6td.jpeg" alt="Disk Sanitization Steps"/>
<br />

<h2>Results</h2>
<p align="center">
<img src="https://i.imgur.com/fuZQGAt.jpeg" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/J7RV0qM.jpeg" width="80%" alt="Disk Sanitization Steps"/>
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
