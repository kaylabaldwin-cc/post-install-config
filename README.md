<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=8bkXbgbJEGk)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-Log in to Azure virtual machine (Windows 10) through Remote Desktop
- Configure rolls, departments & teams
- Allow anyone (employees) to create tickets
- Configure agents, users & SLA
- Configure help topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/8Cmk3rn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create resource group then virtual machine (Windows 10). Log in to virtual machine with Remote Desktop through VM's public IP address.
</p>
<br />

<p>
<img src="https://i.imgur.com/JPGXgH1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to osTicket, click admin and configure rolls, departments & teams.
</p>
<br />

<p>
<img src="https://i.imgur.com/b6tDVfv.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add SLA plan: Sev-A (1 hour, 24/7). Sev-B (4 hours, 24/7). Sev-C (8 hours, business hours).

</p>
<br />
