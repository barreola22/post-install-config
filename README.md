<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=K7T_JjvEamg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


<h2>Configuration Steps</h2>

1. Change the default administrator username and password:
After installing osTicket, the default username and password for the administrator account are 'admin' and 'password' respectively. It is essential to change these credentials for security purposes. You can do this by logging in to the admin panel, navigating to 'Users' and editing the 'admin' account.

2. Configure the email settings:
osTicket uses email to communicate with customers and staff, so it is essential to configure email settings correctly. Navigate to the admin panel, click on 'Settings,' and then 'Email' to configure email settings. You can specify the email server, SMTP settings, and email templates.

3. Set up departments and staff accounts:
To manage tickets effectively, you need to set up departments and assign staff members to them. To do this, navigate to the admin panel, click on 'Staff' and then 'Departments.' You can create departments, assign managers, and add staff members to each department.

4. Customize ticket forms:
osTicket provides default ticket forms, but you can customize them to meet your specific needs. Navigate to the admin panel, click on 'Forms,' and then 'Tickets.' Here, you can customize fields, create new fields, and arrange them to suit your needs.

5. Configure user registration:
osTicket allows users to register for accounts to create and manage tickets. To enable user registration, navigate to the admin panel, click on 'Settings,' and then 'Registration.' Here, you can configure user registration settings, such as captcha settings and whether to require email verification.

6. Customize your helpdesk:
osTicket provides various customization options, such as themes, logos, and text labels. You can customize your helpdesk by navigating to the admin panel, clicking on 'Appearance,' and then 'Customize.' Here, you can upload logos, change colors, and modify text labels.

These are some of the essential post-installation configurations that you can do to optimize your osTicket installation. By doing these configurations, you can make your osTicket installation more secure, efficient, and user-friendly.
