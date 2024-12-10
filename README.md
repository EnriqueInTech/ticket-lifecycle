<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
  <strong>1. Open a New Ticket as an End-User:</strong><br>
  - Start by visiting the Support Center page: http://localhost/osTicket<br>
  - Click on Open a New Ticket at the top right.<br>
  - Enter the contact information, select a topic, create an issue summary title and finally provide a description of the issue.<br>
  - Click Create Ticket at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/BoWi7k5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/OX7Lgjq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>2. Configure New Role:</strong><br>
  - Click on the Agents tab and select Roles.<br>
  - For Name, type Supreme Admin for the new role we'll be creating.<br>
  - Before clicking on Add Role, click on the Permissions tab next to Definition.<br>
  - We are going to allow this role to have all permissions. To do so, select all available options under Tickets, Tasks and Knowledgebase. Each option should be checked.<br>
  - Once all options have been checked, click on Add Role at the bottom.
</p>

<br>

<p>
  <img src="https://i.imgur.com/C56v4Ud.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/mA9GnpQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>3. Configure New Department:</strong><br>
  - Click on the Agents tab and select Departments.<br>
  - Click on Add New Department.<br>
  - For Parent, select Support from the drop-down options.<br>
  - For Name, type SysAdmins for the new department we'll be creating.<br>
  - Click on Create Dept at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/jm5fOee.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>4. Configure New Team:</strong><br>
  - Click on the Agents tab and select Teams.<br>
  - Click on Add New Team.<br>
  - For Name, type Online Banking for the new team we'll be creating.<br>
  - Click on Create Team at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/gWL043m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>5. Configure New Agent:</strong><br>
  - Click on the Agents tab and select Agents.<br>
  - Click on Add New Agent.<br>
  - On the Account tab, enter a name, email address and username.<br>
  - On the Access tab, select Support/SysAdmins as the department and select Supreme Admin as the role from the drop-down options.<br>
  - On the Teams tab, select Online Banking as the team from the drop-down options.<br>
  - Click on Create at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/9A23XY2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/ppycbCY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/o4hOJNZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>6. Set Agent Password:</strong><br>
  - Click on the Agents tab and select Agents.<br>
  - Click on the Agent you just created.<br>
  - On the Account tab, click on Set Password next to Username.<br>
  - Uncheck the reset email option and enter a password for the agent.<br>
  - Click Update at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/4FD4ocp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>7. Configure New User:</strong><br>
  - Click on Agent Panel at the top right.<br>
  - Click on the Users tab and select Add User.<br>
  - Enter an email address and full name.<br>
  - Click Add User at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/j1j34uv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/x83qzwo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>8. Configure Service Level Agreement (SLA):</strong><br>
  - Click on the Admin Panel at the top right.<br>
  - Click on the Manage tab and select SLA.<br>
  - Click on Add New SLA Plan.<br>
  - Enter a name, grace period and schedule.<br>
  - Click Add Plan at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/fZAXcCY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>

<p>
  <strong>9. Configure Help Topic:</strong><br>
  - In the Admin Panel, click on the Manage tab and select Help Topics.<br>
  - Click on Add New Help Topic.<br>
  - Enter a topic and select a parent topic from the drop-down options.<br>
  - Click Add Topic at the bottom.
</p>

<p>
  <img src="https://i.imgur.com/VlsOEbG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
