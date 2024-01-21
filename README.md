<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Users
- Configure SLA
- Configure Help Topics
  
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/9y0WB5P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Mhh9nRA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles:
Admin Panel -> Agents -> Roles
Supreme Admin
  
Departments:
Admin Panel -> Agents -> Departments
System Administrators

Teams:
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets

Agents (workers):
Admin Panel -> Agents -> Add New
Sam
Lan

Users (customers):
Agent Panel -> Users -> Add New
John
Kim

</p>
<br />

<p>
<img src="https://i.imgur.com/FvA1vSW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
SLA:
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/r0ay0c9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Help Topics:
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

</p>
<br />
