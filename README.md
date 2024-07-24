
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket, ensuring it is fully operational and tailored to your organizations needs.<br />


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
- Allow anyone to Create Tickets
- Configure Agents (workers) 
- Configure Users (customers)
- Configure SLA
- Configure Help Topics


<h2>Configuration Steps</h2>

<h3>(1) Configure Role</h3>   
  
<h4>Objective: Define Roles to manage permissions for different user types.</h4>
  
  
In the admin panel, click Agents -> Panels -> Add New Role.  Create a role called "Supreme Admin".    

Enable all Tickets, Tasks, and Knowledgebase. Click "Save Changes".  
![image](https://github.com/user-attachments/assets/18cb00b8-b9af-4d79-834b-269b5258ae4a) 

<br> 
<br>
<br>

<h3>(2) Configure Department</h3>   

<h4>Objective: Organize Agents into Departments based on their responsibilities.</h4>   

Click Agents -> Departments -> Add New Department. Create department called "System Administrators".  

Leave settings default and click "Save Changes".  

![image](https://github.com/user-attachments/assets/1a85c69f-c1fc-423e-9bb5-b04582018811)   

<br> 
<br>
<br>

<h3>(3) Configure teams</h3>   

<h4>Objective: Group Agents into Teams for better task management.</h4>   

Click Agents -> Teams -> Add New Team. Create new team called "Level 2 Support".   

Add yourself as a member and click "Save Changes".

![image](https://github.com/user-attachments/assets/65c0d724-f6e0-4e58-952a-c150a4ceff8c)   

![image](https://github.com/user-attachments/assets/b1b57175-bb16-4ff9-97db-5d3dca7b18f4)   

<br> 
<br>
<br>

<h3>(4) allow anyone to create tickets</h3>   

<h4>Objective: Ensure that all users can submit tickets without needing an account.</h4>   

Admin panel -> Settings -> Users.  

Make sure "Registration Required" is unchecked and click "Save Changes".   

![image](https://github.com/user-attachments/assets/149f6f33-1148-456f-a6ef-bd083560dd92)

<br> 
<br>
<br>  

<h3>(5)Configure Agents</h3>   

<h4>Objective: Create Agents who will handle the tickets.</h4>   

Admin panel -> Agents -> Agents -> Add New Agent    

Create two Agents, Jane and John  

<h4>Jane</h4>  

![image](https://github.com/user-attachments/assets/3babf588-b93b-41bd-96b9-8fcef97422c8)   
   
Primary Department add "System Administrators" and "Supreme Admin".  Extended Access add "Support" and Supreme Admin.   
![image](https://github.com/user-attachments/assets/0d7ad361-30f6-4524-a6fb-5a2eef61cda1)
  

Add to "Level 2 Support" and click "Create".  
![image](https://github.com/user-attachments/assets/3affc33c-b60f-4063-b0bb-d2b2aaa9b9bf)   

<h4>John</h4>  

![image](https://github.com/user-attachments/assets/b768ca73-5ef4-47f4-ba5a-eae94dbdcef0)   

Add to "Support" and "View only". Click "Create".

![image](https://github.com/user-attachments/assets/98fa1eac-f916-4632-ad87-d3542717195d)


<br> 
<br>
<br>

<h3>(6) Configure Users</h3>   

<h4>Objective: Create Users who will submit tickets.</h4>    

Agent panel -> Users -> Add User    

Create two Users, Lewis and Kate.

<h4>Lewis</h4>   

![image](https://github.com/user-attachments/assets/6fc2a81d-03cd-47c0-b918-584bfdad5bdb)

<h4>Kate</h4>   

![image](https://github.com/user-attachments/assets/6bb70dbf-a0df-4670-8f78-ef71b1cf6667)

<br> 
<br>
<br>

<h3>(7) Configure SLA</h3>   

<h4>Objective: Define Service Level Agreements (SLAs) to manage ticket response times.</h4>

Admin panel -> Manage -> SLA -> Add New SLA Plan   

Create SEV-A, SEV-B, and SEV-C.   

<h4>SEV-A</h4>

![image](https://github.com/user-attachments/assets/0cd1e45f-f582-416b-814c-d61ac274efe3)    

<h4>SEV-B</h4>

![image](https://github.com/user-attachments/assets/5b3052d9-dd87-486f-8a76-c3412bb101c1)   

<h4>SEV-C</h4>   

![image](https://github.com/user-attachments/assets/e5721460-3ef1-4583-9cf8-926b50f2eba9)

<br> 
<br>
<br>  

<h3>(8) Configure Help Topics</h3>   

<h4>Objective: Define categories for ticket submission to streamline support.</h4>   

Admin panel -> Manager -> Help Topics   

Create Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.   

![image](https://github.com/user-attachments/assets/7b3abc36-157f-48a4-a23f-d9ed21326d32)


<h1>Congratulations! You've completed the post installation configuration of osTicket.</h1>
