<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install System Navigation</h1>
This tutorial explains the different objectives used within osTicket to ensure the efficient response to customer inquiries and issues, streamlining the support process and enhancing customer satisfaction.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Objectives</h2>

- Roles
- Departments
- Teams
- Agents
- Users
- SLAs

<h2>Objectives Defined</h2>

<p>

  ![Roles](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/dfd43bd2-e5e7-45a6-9923-b6409e6f3b63)

</p>
<p>
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
</p>
<br />

<p>

  ![Departments](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/4db8e8f7-dbe5-442e-9f2b-7db706850722)

</p>
<p>
Departments in a help desk system are organizational units that categorize and route incoming support tickets based on specific criteria, such as the type of issue or the area of expertise required. Each department is responsible for handling a particular subset of customer inquiries, ensuring that tickets are directed to the appropriate team or agents for efficient and specialized assistance.
</p>
<br />

<p>

  ![Teams](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/bd66541b-83de-4ec9-971e-98203d2fdbc9)

</p>
<p>
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. Having Agents from different Departments assigned to a Team will supersede the parameters of the Agents’ Department rules. For example, you can create a Help Topic associated with a particular product you produce, and assign it to a Team of specialist Agents from different Departments.
</p>
<br />

<p>

  ![Agents](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/3aff0664-e2bb-4ec3-9d76-68f77cf2f75a)

</p>
<p>
Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.

</p>
<br />

<p>

  ![Users](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/12efb14a-cb27-4d7e-b041-bb37817f0c2e)

</p>
<p>
Users (or customers) are the ticket owners of the tickets in the help desk. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk.

</p>
<p>

![SLA](https://github.com/ryanhuntercarline/post-install-config/assets/141659465/11c76604-641b-44ae-ad91-a3815602a138)

</p>
</p>
SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
