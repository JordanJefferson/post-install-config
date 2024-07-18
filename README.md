
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
-Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
-Configure SLA
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

<h3>(1) Create Role</h3>
  
In the admin panel, click Agents -> Panels -> Add New Role.  Create a role called "Supreme Admin" to manage all aspects of the system.    

Enable all Tickets, Tasks, and Knowlegebase. Click "save changes".  
![image](https://github.com/user-attachments/assets/18cb00b8-b9af-4d79-834b-269b5258ae4a) 

<br> 
<br>
<br>

<h3>(2) Create Department</h3>   

Click Agents -> Departments -> Add New Departmment. Create department called "System Administrators".  

leave settings default and click "save changes".  

![image](https://github.com/user-attachments/assets/1a85c69f-c1fc-423e-9bb5-b04582018811)   

<br> 
<br>
<br>

<h3>(3) Create teams</h3>   

click Agents -> Teams -> Add New Team. Create ne team called "Level 2 Support".   

Add Yourself as a member and click "save changes".

![image](https://github.com/user-attachments/assets/65c0d724-f6e0-4e58-952a-c150a4ceff8c)   

![image](https://github.com/user-attachments/assets/b1b57175-bb16-4ff9-97db-5d3dca7b18f4)   

<br> 
<br>
<br>

<h3>(4) Confirm anyone is allowed to create tickets</h3>   

Admin panel -> Settings -> users.  

Make sure "Registration Required" is unchecked and click "save changes".   

![image](https://github.com/user-attachments/assets/149f6f33-1148-456f-a6ef-bd083560dd92)

<br> 
<br>
<br>  

<h3>(5)Configure Agents</h3>   

Admin panel -> Agents -> Agents -> Add New Agent    



![image](https://github.com/user-attachments/assets/6a78cc25-06d5-456d-984d-f684ec997799)   

Add to "System Administrators" and "Supreme Admin"  
![image](https://github.com/user-attachments/assets/44bccc05-e353-4406-851f-1913c3f3dbb5)   

Add to "Level 2 Support" and click "Create".  
![image](https://github.com/user-attachments/assets/3affc33c-b60f-4063-b0bb-d2b2aaa9b9bf)

<br> 
<br>
<br>

<h3>(6) Configure Users</h3>
