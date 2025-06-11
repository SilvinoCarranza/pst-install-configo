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

We are going to be Configuring Roles, Departments, Teams, Agents, Users, SLA, and  Help Topics.
and we are going to allow anyone to create tickets
</p>
<br />
There are two panels we are going to be using within osTicket the admin palen and the agent panle you can switch on the top right of the window
</p>
<br />

<img src="https://i.imgur.com/KkecxkV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<img src="https://i.imgur.com/RCpteVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Configuration Steps</h2>
</p>
<br />
Now logged in as a admin user
Go to the admin panle then agents, roles, and add new role
</p>
<br />

<img src="https://i.imgur.com/r86GHPR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We are going to name it Supreme Admin and assign all permmisions
</p>
<br />

<img src="https://i.imgur.com/ci8XjnM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now go to departments and create add new department
leave it as top level department then name it sysAdmins
</p>
<br />

<img src="https://i.imgur.com/Fy3UEZS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now go to teams and add a new team
Name it Online Department 
</p>
<br />

<img src="https://i.imgur.com/MVQcasT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now we are going to allow anyone to create tickets 
go to settings then users and make sure registration required is unchecked
</p>
<br />

<img src="https://i.imgur.com/T5lZU2z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Now we are createing a couple of agent accounts jane doe and john doe.
To set a password click set password then uncheck send the agent a password reset email. Then set the password and click update
For jane doe under access then primary depratments we are going to make jane a sysadmin and supreme admin then under we are making teams we are placeing her in online banking
for john doe under access he will be under support and view only  for team leave it how it is.

</p>
<br />

<img src="https://i.imgur.com/xi0ktNe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<img src="https://i.imgur.com/3WL1SKh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<img src="https://i.imgur.com/8zqNTNX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />

Now we adding new SLAs 
Go to manage then SLA then click add new SLA plan
these are the SLAs we are creating
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)

</p>
<br />

<img src="https://i.imgur.com/zrJY7dt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />

Now we are going to be addin new help topics 
Go to manage then help topics and then click add new help topic
These are the topics we are creating 
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


</p>
<br />

Now we are adding some users karen and ken
Go to the agent panle then users then add user
</p>
<br />
<img src="https://i.imgur.com/RCpteVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<img src="https://i.imgur.com/rQRIkf2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<img src="https://i.imgur.com/HtLfhOu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


