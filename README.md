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

- Set up agent roles
- Create departments and teams
- Add and manage agents
- Configure SLAs and help topics
- Finalize user access settings

<h2>Configuration Steps</h2>

<p>
<img width="431" height="349" alt="AaUntitled" src="https://github.com/user-attachments/assets/fda3edbb-28db-4c5f-962b-3bfb2d956ff2" />
</p>
<p>
Log in to the osTicket admin panel using an administrator account to begin post-install configuration.
</p>
<br />

<p>
<img width="935" height="530" alt="agent panel" src="https://github.com/user-attachments/assets/9e755041-f8cc-4fb3-8f59-a57431f334e5" />
</p>
<p>
Open the Agents → Roles page to review existing roles and access levels for agents.
</p>
<br />

<p>
<img width="935" height="719" alt="Screenshot 2025-10-11 at 3 36 45 PM" src="https://github.com/user-attachments/assets/fd5296c1-0aff-4770-9941-45de69da7a99" />
</p>
<p>
Use the Add New Role form to enter a role name (Supreme Admin) and any internal notes before assigning permissions.
</p>
<br />

<p>
<img width="937" height="860" alt="Screenshot 2025-10-11 at 3 37 27 PM" src="https://github.com/user-attachments/assets/d72365aa-925d-4466-afc9-f0e64b10df3b" />
</p>
<p>
Switch to the Permissions tab and select the ticket and task permissions required for the role.
</p>
<br />

<p>
<img width="931" height="447" alt="Screenshot 2025-10-11 at 3 38 15 PM" src="https://github.com/user-attachments/assets/1d740a51-1979-4d26-8252-886612951c15" />
</p>
<p>
Confirm the newly created role appears in the roles list and that its status is set to Active.
</p>
<br />

<p>
<img width="932" height="680" alt="Screenshot 2025-10-11 at 3 47 47 PM" src="https://github.com/user-attachments/assets/4d085309-a1d5-42db-b458-63dd7817adb2" />
</p>
<p>
Create a new department: set the department name, status, type, and ticket assignment options.
</p>
<br />

<p>
<img width="932" height="561" alt="Screenshot 2025-10-11 at 3 47 54 PM" src="https://github.com/user-attachments/assets/8fd84aca-6cc7-4f89-8558-0ced562b9db8" />
</p>
<p>
Use the Access tab to add primary members or grant extended access to agents for the department.
</p>
<br />

<p>
<img width="926" height="710" alt="Screenshot 2025-10-11 at 3 57 41 PM" src="https://github.com/user-attachments/assets/a8700327-1884-49c2-a617-fcdb43af7968" />
</p>
<p>
Create or update a Team (for example “Online Banking”), set the team lead, and configure assignment alerts.
</p>
<br />

<p>
<img width="923" height="376" alt="Screenshot 2025-10-11 at 3 59 10 PM" src="https://github.com/user-attachments/assets/2d6e25ef-eb40-4837-a69b-5b39a4977a1d" />
</p>
<p>
Open Users settings to configure registration and authentication options for portal access.
</p>
<br />

<p>
<img width="738" height="341" alt="Screenshot 2025-10-11 at 4 06 42 PM" src="https://github.com/user-attachments/assets/2d871348-a7a9-4336-a6e3-db5dc1d4ba16" />
</p>
<p>
Add a new agent account by entering the agent’s name, email, and username details.
</p>
<br />

<p>
<img width="931" height="486" alt="Screenshot 2025-10-11 at 4 11 03 PM" src="https://github.com/user-attachments/assets/834ff653-3fbb-4c2f-b140-fd2761f2e351" />
</p>
<p>
Manage an agent’s account details and verify authentication settings and contact information.
</p>
<br />

<p>
<img width="646" height="389" alt="Screenshot 2025-10-11 at 4 14 01 PM" src="https://github.com/user-attachments/assets/042a808f-a6c0-44f5-9626-6444b8cef4e0" />
</p>
<p>
Set or reset the agent’s password and optionally require a password change at next login.
</p>
<br />

<p>
<img width="924" height="335" alt="Screenshot 2025-10-11 at 4 37 42 PM" src="https://github.com/user-attachments/assets/a2308c2b-6a82-4abb-a72b-ecaf2c5b9516" />
</p>
<p>
Define SLA plans and response targets for different severities used by the support team.
</p>
<br />

<p>
<img width="932" height="684" alt="Screenshot 2025-10-11 at 4 38 30 PM" src="https://github.com/user-attachments/assets/8d479e4c-ecb4-4ae7-9a35-44b0869a0c2f" />
</p>
<p>
Configure help topics that customers will see in the portal to categorize incoming tickets.
</p>
<br />
