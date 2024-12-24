# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br /</b>
<p></p>
  Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
<p></p>
<img src="https://camo.githubusercontent.com/e530f0a2532fbf23afe04bff46849d7c6e0e6de860be12bcae63d063d9480cb0/68747470733a2f2f692e696d6775722e636f6d2f584874657164742e706e67"Disk Sanitization Steps"/>
</p> 

  Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.

<p>
<img src="https://camo.githubusercontent.com/77a8966d70cb15508aaa0ceb967b40cce186c5747409d759e1b6ae3ea94ce4eb/68747470733a2f2f692e696d6775722e636f6d2f64474b3052564d2e706e67"Disk Sanitization Steps"/>
</p>
<p>

  After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/8fe3074389a93b72184d3923929ff5540828f269b496e158bf5be254ac709a15/68747470733a2f2f692e696d6775722e636f6d2f63597a574244322e706e67"Disk Sanitization Steps"/>
</p>
<p>

 Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.


</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/7a41436e49e558fb900b40be17f9606c08ba9661990a836d68561c8246b750c4/68747470733a2f2f692e696d6775722e636f6d2f483171324664682e706e67"Disk Sanitization Steps"/>
</p>
<p>

 It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab
</p>
<br />
<p>
<img src="https://camo.githubusercontent.com/af8216a938bb4fc56a25fce0ece0fd4d81f38f9cdc23ee37797f48b67dc11760/68747470733a2f2f692e696d6775722e636f6d2f3857544f5372652e706e67"Disk Sanitization Steps"/>
</p>

After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new.

<p>
<img src="https://camo.githubusercontent.com/6d7b869a84f8cd0672414adc6d96c1a582e1f9b8f8d8835c7e24be8ca2853bc3/68747470733a2f2f692e696d6775722e636f6d2f784f70724139662e706e67"Disk Sanitization Steps"/>
</p>

SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.

<p>
<img src="https://camo.githubusercontent.com/ea256fcb476f78059f1c54c0d25c67af69b78e09b8b058ea6aa5cbd6133236d3/68747470733a2f2f692e696d6775722e636f6d2f4c706a43614c642e706e67"Disk Sanitization Steps"/>
</p>

Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking.

<p>
<img src="https://camo.githubusercontent.com/e0a6ba4012a5cb9470b1c6513963bb90068cdb0b10f0917042ed310d791b9fb1/68747470733a2f2f692e696d6775722e636f6d2f6b4237727473322e706e67"Disk Sanitization Steps"/>
</p>

