<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This walkthrough outlines the post-install configuration of the open-source help desk ticketing system osTicket. In the last lab we installed all the prerequisites and installed osTicket. In case you took a break, open azure portal and recopy the ip address becuase it might’ve changed if you closed or shutdown the VM. 

There will also be a video demonstration of this portion of the project in it's entirety in the YouTube link below in case of any hiccups along the process. For the short videos provided, you can simply click the video and it should open in a new tab for better guidance.

Now we’ll login into osTicket as the admin through the link provided in the documents and use the shared file as a point of reference to configure osTicket for practice as the admin and end user. 

To keep things simple and short for the entire project we’ll leave the mail settings default. 
<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/Nq5glaCfzyU)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (Microsoft Remote Access in the App Store for MAC users)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
- Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
- Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
- Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
- Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/bccab172-9083-4074-89cd-7e621e316046" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/86b6c31e-17fc-45da-833b-54fc11224f0d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/e342a05a-9f76-4683-9409-3174e816d0a1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/da85bf8a-1e44-4ec7-8c9e-2116e1ca74db" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/832e314a-f4b0-444d-aeff-d427b7279776" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
When configuring the agents, make sure to set the password and do not require password change at login. 
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/cd21beae-fa26-42e4-9a92-533489236614" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/9349b4c7-9bb5-430e-a4af-ff39676e359f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://github.com/montrequonwheeler/post-install-config/assets/127397594/3522a767-656b-46e4-a9ea-ebece2c94e7b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
</p>
<br />
