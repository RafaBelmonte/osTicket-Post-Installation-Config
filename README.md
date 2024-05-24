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
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

Configuring Roles

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/2cd6cefb-3b31-4a2b-aa8d-7cff3ce4c481)

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/032a0b44-a61d-4f56-bbb2-d43e1696099d)

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/fe8a0af7-fea7-4c5e-914e-41be69aeb4a1)



Using the Admin Panel - Agents - Roles to add or remove roles to specific Agents.
</p>
<br />

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/aeed063c-240b-427b-b554-be29dc4b528d)


Configuring Departments

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/45e129d7-4f7f-4af1-886d-ac8b51cacdb0)

  
In the same Admin - Agents tab you can access the Departments tab. Since tickets are routed through Departments, this allows you to create settings for different Departments. 
</p>
<br />

Configuring Teams

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/8ef9beed-5c24-47f3-9dbb-6476c423c80a)

Under the same Agents tab, navigate to the Teams tab where it allows you to pull Agents from different Departments and organize them to handle specific issues.

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/c1201467-d149-44c2-ae73-5fb910b388fe)


</p>
<br />

Allowing anyone to create Tickets

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/d98ee10c-0936-45fc-a088-97b4f05545d6)

Still in the Admin Panel, go to Settings, User Settings to enable anyone to create tickets.

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/c0449ece-f792-4cab-8951-4aff2cb5d4d6)

</p>
<br />

Creating Agents

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/3009fa98-a67e-4308-9f3c-dbec3bc01a5d)

You can create new Agents by going into the Agents tab - add new, and configuring your new Agent. Agents are given access to respond and resolve the tickets created by the customers. They need to be assigned to a primary department and role so the correct tickets can be routed to them.
</p>
<br />

Creating Users

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/176ebab0-e50e-4c82-bab2-17ebf92ec065)

This section is done through the Agent Panel. Go to the Users tab and then Add New to create new users. They can create tickets and check on ticket's status. They are associated with their email address as their unique identifier.

Configuring SLAs (service Level Agreements)

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/2b58e70e-c15c-4b0b-9f1b-790afd7a19f0)

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/16ce593c-3c69-448b-84f2-cddd710e2bf7)


This is done through the Admin Panel. Navigating to the Manage tab - SLA, and from there you can create new SLAs where we can define the maximum response time per ticket depending on the severity of the ticket.
</p>
<br />

Configuring Help Topics

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/9413ff7c-b1a8-441b-9b8f-bbe539118d50)

![image](https://github.com/RafaBelmonte/osTicket-Post-Installation-Config/assets/170759303/c3786003-fe65-4ae8-ab57-f1619624b56b)


This step is also done through the Admin Panel by going into Settings - Help Topics.

Here you can create new Help Topics for users to select. Resetting passwords, equipment refresh, requests for new equipments are examples of help topics that users can select (if created).
</p>
<br />
