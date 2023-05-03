<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

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
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/nET9uNE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The osTicket log-in page.
</p>
<br />

<p>
<img src="https://i.imgur.com/Pnah18n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Upon log-in, the agent panel is displayed. In the top right corner, there is an option to switch to the "Admin Panel"; this will be selected, with the aim to configure the roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/YlK7O8g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Admin Panel --> Agents --> Roles" is selected. "Add New Role" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/NnEgofq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within "Add New Role", under the "Definition" tab, "Supreme Admin" is filled in.
</p>
<br />

<p>
<img src="https://i.imgur.com/oob6cur.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Supreme Admin" role, under the "Tickets" tab, everything is selected to give full access.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z8xYlrx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Supreme Admin" role, under the "Tasks" tab, everything is selected to give full access.
</p>
<br />

<p>
<img src="https://i.imgur.com/hoKeCTf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Supreme Admin" role, under the "Knowledgebase" tab, the sole option is selected to again provide full access.
</p>
<br />

<p>
<img src="https://i.imgur.com/btiR3vg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The completed "Supreme Admin" role is displayed.
</p>
<br />

<p>
<img src="https://i.imgur.com/3Hutfrz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The aim is to now configure the departments. "Admin Panel --> Agents --> Departments" is selected. "Add New Department" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/rs3Y6f3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within "Add New Department", information to create the "Systems Administrators" department is configured. "Add Department" is selected, though the button is out-of-frame.
</p>
<br />

<p>
<img src="https://i.imgur.com/CllyWR0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The newly created department "System Administrators" is displayed.
</p>
<br />

<p>
<img src="https://i.imgur.com/hMxayWp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the aim to configure the teams, "Admin Panel --> Agents --> Teams" is selected. "Add New Team" is selected, with the aim to create "Level II Support". "Level I Support" is configured by default.
</p>
<br />

<p>
<img src="https://i.imgur.com/uqesJcV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Level II Support" is configured, and "Create Team" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/JkT6iSm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the aim to configure the agents, "Admin Panel --> Agents --> Agents" is selected. "Add New Agent" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/fJ04Hxx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first agent to be configured is named "Jane Doe".
</p>
<br />

<p>
<img src="https://i.imgur.com/nwbN0hn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane's password is set.
</p>
<br />

<p>
<img src="https://i.imgur.com/BywTjDV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane's access has been set to being a part of the "Systems Administrators" department and to have the "Supreme Admin" role.
</p>
<br />

<p>
<img src="https://i.imgur.com/aiWsrzY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane has been given full permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/wkVikp6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane has been placed in the "Level II Support" team.
</p>
<br />

<p>
<img src="https://i.imgur.com/iLbhF1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Jane has been successfully added as an agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/VJCD3q3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
John Smith is the next agent to be added. His password is set, as Jane's was.
</p>
<br />

<p>
<img src="https://i.imgur.com/pl62sTm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
John's access has been set to being a part of the "Support" department and to have the "Limited Access" role.
</p>
<br />

<p>
<img src="https://i.imgur.com/ADOOvIH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
John has been given full permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/lUPJ81q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
John has been placed in the "Level I Support" team.
</p>
<br />

<p>
<img src="https://i.imgur.com/zszMeQg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Both agents have been successfully added.
</p>
<br />

<p>
<img src="https://i.imgur.com/X1pz7qE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the aim to configure the users, "Agent Panel --> Users --> User Directory" is selected. "Add User" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/evvVazb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Karen Jones is configured as a user.
</p>
<br />

<p>
<img src="https://i.imgur.com/6lEVjps.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Karen Jones has been successfully added as a user.
</p>
<br />

<p>
<img src="https://i.imgur.com/gALRWL8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ken Jackson is configured as a user.
</p>
<br />

<p>
<img src="https://i.imgur.com/w7o67oo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ken Jackson has been successfully added as a user.
</p>
<br />

<p>
<img src="https://i.imgur.com/EAFnScI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the aim to congiure the SLA plans, "Admin Panel --> Manage --> SLA" is selected. "Add New SLA Plan" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/MwcaEfF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sev-A has been configured to have a 1 hour grace period, on a 24/7 schedule. This SLA is meant for business critical emergencies.
</p>
<br />

<p>
<img src="https://i.imgur.com/CDYIlCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sev-B has been configured to have a 4 hour grace period, on a 24/5 schedule.
</p>
<br />

<p>
<img src="https://i.imgur.com/tZcgHNg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sev-C has been configured to have an 8 hour grace period, on a 24/5 schedule.
</p>
<br />

<p>
<img src="https://i.imgur.com/5iuXD2z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sev-D has been configured to have an 8 hour grace period, on a "Monday-Friday 8am-5pm with U.S. Holidays" schedule.
</p>
<br />

<p>
<img src="https://i.imgur.com/wcMzXAF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
All four SLA plans have been successfully created.
</p>
<br />

<p>
<img src="https://i.imgur.com/B75Gt42.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the aim to configure the help topics, "Admin Panel --> Manage --> Help Topics" is selected. "Add New Help Topic" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/xDQcEir.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The "Business Critical Outage" help topic is configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/n8zBwYt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Business Critical Outage" help topic, the SLA plan Sev-A is selected and the priority is set to "Emergency".
</p>
<br />

<p>
<img src="https://i.imgur.com/WcH37WH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The "Personal Computers Issues" help topic is configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/dFq7wak.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Personal Computers Issues" help topic, the SLA plan Sev-B is selected and the priority is set to "Normal".
</p>
<br />

<p>
<img src="https://i.imgur.com/P4Qtpyf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The "Equiptment Request" help topic is configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/asmiy2D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Equiptment Request" help topic, the SLA plan Sev-D is selected and the priority is set to "Normal".
</p>
<br />

<p>
<img src="https://i.imgur.com/fVSZ5KD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The "Password Reset" help topic is configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/opEitez.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the "Password Reset" help topic, the SLA plan Sev-B is selected and the priority is set to "Normal".
</p>
<br />

<p>
<img src="https://i.imgur.com/OWxd54b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The four help topics have been successfully configured.
</p>
<br />
