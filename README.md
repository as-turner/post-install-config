<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=HGywPhfKt4E)

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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/krBpxVm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login as User Admin. Notice on the top right there’s an Admin Panel button. Click on it to switch into the Admin Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/51ts815.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After switching to the Admin Panel, you’ll see the same button allows you to switch back to Agent Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/LBkU3CS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Stay on the Admin Panel and click on the Agents Tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/Vaj3fCn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/f9kNbsV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Add New Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/oPaDStW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Supreme Admin Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/cI1inTD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the Permissions Tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/7OduFy0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Tickets, select all options.
</p>
<br />

<p>
<img src="https://i.imgur.com/g2PCw0O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Tasks, select all options.
</p>
<br />

<p>
<img src="https://i.imgur.com/21gjUPK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Knowledgebase, select the option and finally click Add Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/LoOGAQu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/Zs4bVj6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Add A New Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/eYwQrLt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in the name, select options and create the Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/SVtLVRM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Teams.
</p>
<br />

<p>
<img src="https://i.imgur.com/GjbltH1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Add Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/NbzV3A0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the Team and create it.
</p>
<br />

<p>
<img src="https://i.imgur.com/wGxcGS3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Members and add yourself to the team.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZlKBVlB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Settings, Users, Settings, uncheck Require Registration.
</p>
<br />

<p>
<img src="https://i.imgur.com/CyjAL3R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click the Agents Tab and Add New Agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/scvVbwf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create your first Agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/QkfyKWH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Uncheck the boxes and set password.
</p>
<br />

<p>
<img src="https://i.imgur.com/8lHiKvg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set Access Settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/XYamuDF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Create after selecting Team. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KyJVgie.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back to Agents and repeat steps for Agent 2. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Snim125.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set Access Settings for Agent 2.
</p>
<br />

<p>
<img src="https://i.imgur.com/wRGuDAB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Users by going into the Agent Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/FSFTOsu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click the Users Tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/FFhuleb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a new User.
</p>
<br />

<p>
<img src="https://i.imgur.com/SYNCZbV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click User Directory and repeat steps for 2nd User.
</p>
<br />

<p>
<img src="https://i.imgur.com/xqunPJF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to Admin Panel, Manage, and SLA.
</p>
<br />

<p>
<img src="https://i.imgur.com/f74xkIr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Add New SLA Plan.
</p>
<br />

<p>
<img src="https://i.imgur.com/VYLcHXz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name and set rules for 1st SLA.
</p>
<br />

<p>
<img src="https://i.imgur.com/ATY2Sxp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create rules for 2nd SLA.
</p>
<br />

<p>
<img src="https://i.imgur.com/Bs53KhX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create rules for 3rd SLA.
</p>
<br />

<p>
<img src="https://i.imgur.com/zCicQwm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics.
</p>
<br />

<p>
<img src="https://i.imgur.com/r6bCFGu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Business Critical Outage and repeat the steps for the others. All Helps Topics are listed on the final slide.
</p>
<br />

<p>
<img src="https://i.imgur.com/ABOX4N4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Final list of Help Topics. Congratulations on finishing the Post-Install Configuration!
</p>
<br />
