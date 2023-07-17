<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial goes over the post-install configuration of the open-source help desk ticketing system osTicket.<br />



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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/kc0PoQg.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/cuCYMeu.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/yGC81PT.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/yrdVbPl.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://i.imgur.com/0OlUijP.png" height="75%" width="100%" alt="Sys Admin Success"/>
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/09i8zbx.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://i.imgur.com/B2ufBbI.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/9kzcLH9.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/ipQ2ySx.png" height="75%" width="100%" alt="agent one access"/>
  <img src="https://i.imgur.com/G6ZiYCm.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/ZqgYSkX.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/3tC51X1.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Karen Smith:
</p>
  <img src="https://i.imgur.com/IbZcWdj.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Ken Smith.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/xkIn58M.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/t6t4kN4.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/fgcCY38.png" height="75%" width="100%" alt="sev three"/>
  <img src="https://i.imgur.com/Qno7fbu.png" height="75%" width="100%" alt="sla plan"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
  <img src="https://i.imgur.com/SYRbjJv.png" height="75%" width="100%" alt="business critical outage"/>
</p>
<p>
  Personal Computer Issues.
  <img src="https://i.imgur.com/Jto094h.png" height="75%" width="100%" alt="personal computer issues"/>
  
</p>
<p>
  Equipment Request.
  <img src="https://i.imgur.com/fpdItLj.png" height="75%" width="100%" alt="equipment request"/>
</p>
<p>
  Password Reset.
  <img src="https://i.imgur.com/FX8tllT.png" height="75%" width="100%" alt="password reset"/>
</p>

<br />
<br />
<p>
  And that's it! This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. You can practice triaging and solving tickets.
</p>
<p>
  I believe this is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
