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
  <strong>2. Observe the Ticket as a Help Desk Agent:</strong><br>
  - Start by visiting the Agent Login page: http://localhost/osTicket/scp/login.php<br>
  - Once logged in, you should see the new ticket the end-user created listed at the top.<br>
  - Click on the ticket and observe the ticket's properties: Priority, Department, SLA, Assigned To
</p>

<br>

<p>
  <img src="https://i.imgur.com/rfWYxZD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/FKtcSOy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>3. Set Properties to the Ticket:</strong><br>
  - Click on SLA Plan and select Severity Level A (SEV-A) since the ticket in this example appears to be a high critical issue.<br>
  - Provide a reason for the update and click Update.<br>
  - Click on Help Topic and select Business Critical Outage to help the problem being reported more specific.<br>
  - Provide a reason for the update and click Update.<br>
  - Click on Assigned To and select the Online Banking team since there's an actual team for this type of problem.<br>
  - Provide a reason for the assignment and click Assign.
</p>

<p>
  <img src="https://i.imgur.com/pekZyGA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/2cW1641.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/vUqFAGE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>4. Observe the Ticket:</strong><br>
  - Refresh the page to view updates.<br>
  - The Ticket Thread should reflect the updates that were made to the ticket.
</p>

<p>
  <img src="https://i.imgur.com/dzuDhAQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <strong>5. Work the Ticket to Completion as a Different Help Desk Agent:</strong><br>
  - Start by visiting the Agent Login page: http://localhost/osTicket/scp/login.php<br>
  - Once logged in, click on the updated ticket.<br>
  - Click on Assigned To to reassign the ticket to yourself or to the specific help desk agent who will be working the ticket to completion.<br>
  - Provide a reason for the reassignment and click Assign.<br>
  - Scroll down to Post Reply and provide a response to the active recipients of this ticket.<br>
  - Click Post Reply.<br>
  - Before closing the ticket, scroll down to Post Reply and provide a summary.<br>
  - Click Post Reply.<br>
  - Click on Status to change the status of the ticket from Open to Resolved.<br>
  - Click Close.
</p>

<p>
  <img src="https://i.imgur.com/BhGdkJK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/K10OjqX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/NAppsvd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/9MJEgp9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
