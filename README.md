<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>
<ul>
<li>Microsoft Azure (Virtual Machines/Compute)</li>
<li>Remote Desktop</li>
<li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
<li>Windows 10 (21H2)</li>
</ul>

<h2>Post-Install Configuration Objectives</h2>
<p>
We will be configuring Roles, Departments, Teams, Agents, Users, SLA plans, and Help Topics. We will also configure osTicket to allow anyone to create tickets.
</p>

<p>
There are two panels used in osTicket: the <strong>Admin Panel</strong> and the <strong>Agent Panel</strong>. You can switch between them using the top-right dropdown menu.
</p>

<img src="https://i.imgur.com/KkecxkV.png" width="80%" alt="Admin Panel Screenshot"/>
<img src="https://i.imgur.com/RCpteVY.png" width="80%" alt="Agent Panel Screenshot"/>

<h2>Configuration Steps</h2>

<h3>Step 1: Create a New Role</h3>
<ol>
<li>Log in as an admin user.</li>
<li>Go to the <strong>Admin Panel</strong> → <strong>Agents</strong> → <strong>Roles</strong> → <strong>Add New Role</strong>.</li>
<li>Name the role <strong>Supreme Admin</strong> and assign all permissions.</li>
</ol>
<img src="https://i.imgur.com/r86GHPR.png" width="80%"/>
<img src="https://i.imgur.com/ci8XjnM.png" width="80%"/>

<h3>Step 2: Create a Department</h3>
<ol>
<li>Go to <strong>Departments</strong> → <strong>Add New Department</strong>.</li>
<li>Leave it as a Top-Level Department and name it <strong>sysAdmins</strong>.</li>
Also we will DELETE the Maintenance Department
</ol>
<img src="https://i.imgur.com/Fy3UEZS.png" width="80%"/>

<h3>Step 3: Create a Team</h3>
<ol>
<li>Go to <strong>Teams</strong> → <strong>Add New Team</strong>.</li>
<li>Name the team <strong>Online Department</strong>.</li>
</ol>
<img src="https://i.imgur.com/MVQcasT.png" width="80%"/>

<h3>Step 4: Allow Public Ticket Creation</h3>
<ol>
<li>Go to <strong>Settings</strong> → <strong>Users</strong>.</li>
<li>Make sure <strong>Registration Required</strong> is unchecked.</li>
</ol>
<img src="https://i.imgur.com/T5lZU2z.png" width="80%"/>

<h3>Step 5: Create Agent Accounts</h3>
<p>Create accounts for Jane Doe and John Doe.</p>
<ul>
<li>Set passwords manually by unchecking "Send the agent a password reset email" and clicking <strong>Set Password</strong>.</li>
<li><strong>Jane Doe</strong>: Assign to <strong>sysAdmins</strong> department, <strong>Supreme Admin</strong> role, and <strong>Online Banking</strong> team.</li>
<li><strong>John Doe</strong>: Assign to <strong>Support</strong> department with <strong>View Only</strong> access; leave the team unchanged.</li>
</ul>
<img src="https://i.imgur.com/xi0ktNe.png" width="80%"/>
<img src="https://i.imgur.com/3WL1SKh.png" width="80%"/>
<img src="https://i.imgur.com/8zqNTNX.png" width="80%"/>

<h3>Step 6: Create SLA Plans</h3>
<ol>
<li>Go to <strong>Manage</strong> → <strong>SLA</strong> → <strong>Add New SLA Plan</strong>.</li>
<li>Create the following SLA plans:
<ul>
<li><strong>Sev-A</strong>: Grace Period - 1 hour, Schedule - 24/7</li>
<li><strong>Sev-B</strong>: Grace Period - 4 hours, Schedule - 24/7</li>
<li><strong>Sev-C</strong>: Grace Period - 8 hours, Schedule - Business Hours</li>
</ul>
</li>
</ol>
<img src="https://i.imgur.com/zrJY7dt.png" width="80%"/>

<h3>Step 7: Create Help Topics</h3>
<ol>
<li>Go to <strong>Manage</strong> → <strong>Help Topics</strong> → <strong>Add New Help Topic</strong>.</li>
<li>Create the following help topics:
<ul>
<li>Business Critical Outage</li>
<li>Personal Computer Issues</li>
<li>Equipment Request</li>
<li>Password Reset</li>
<li>Other</li>
</ul>
</li>
</ol>

<h3>Step 8: Add Users</h3>
<ol>
<li>Switch to the <strong>Agent Panel</strong>.</li>
<li>Go to <strong>Users</strong> → <strong>Add User</strong>.</li>
<li>Create users <strong>Karen</strong> and <strong>Ken</strong>.</li>
</ol>
<img src="https://i.imgur.com/RCpteVY.png" width="80%"/>
<img src="https://i.imgur.com/rQRIkf2.png" width="80%"/>
<img src="https://i.imgur.com/HtLfhOu.png" width="80%"/>

<p><strong>✨ Configuration Complete!</strong></p>


