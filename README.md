<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- OsTicket 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- ConFigure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure Service Level Agreements (SLA)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
  
<h3>Configure Roles</h3>

Admin Panel > Agents > Roles

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/94456706-0b5b-4830-9dd3-1779ff633037)

 
Create a Supreme Admin with all available Permissions

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/0212ac84-1412-496d-9246-b41b5c40cd81)

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/85950fd7-9fed-4744-b997-f0f9d97a43d1)



<h3>Configure Departments</h3>


Admin Panel > Agents > Department 
![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/69f29479-c523-462b-94b4-b30fe55f8beb)

System Administrators 
![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/8b83d816-d1ad-4bac-a18c-9221c285b851)



<h3>Configure Teams</h3>

Admin Panel -> Agents -> Teams
![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/b6aa7284-ad6f-496e-96da-458d4622115c)

Level II Support 

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/e3ebe565-ee2b-4e55-b9c5-9d7754cca10b)



<h3>Configure Users</h3>

Agent Panel > Users > User Directory 

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/ac2f2316-32a0-4036-b2b8-d63794cc0a12)

Create a new user
<p>Agent Panel > Users > Add new</p>

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/37b6cf79-86f2-42a5-9a23-4678b8ec3c39)



Give users permission to create tickets  
Admin Panel > Settings > User 
![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/aff6457e-d419-4c9a-b751-483b115cc7f5)

<h3>Confire Agent</h3>

Admin Panel > Agents > Add 
<p>Create users John Doe</p>

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/351f3f03-8c13-421d-8a0d-532f7b793e8f)



<h3>Confire SLA (Service Level Agreements)</h3>
<p>Admin Panel > Manage > SLA </p>

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/05112643-25d7-44f9-b2ef-4b3904fc63c0)

Create 3 Levels of Severity 
- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, Business hours)

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/5b9e42ab-1c57-468d-8afe-5dee39db8894)

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/383e8627-edaf-4aad-a936-5ad46b8c2171)

<h3>Configure Help Topics</h3>

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset

  

<p>Admin Panel > Manage > Help Topics </p>

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/0df105ed-a79b-4512-a5be-467918ff1909)

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/7f31eb46-509f-4ca2-89bd-32bf7cb0a131)

![image](https://github.com/YArroliga/Os-ticket-configure/assets/139689160/2a328a0e-7e35-4a68-92dd-c7aa373fa78b)


