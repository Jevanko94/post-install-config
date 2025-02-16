# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<p align="center">
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/e57ef384-fb94-4fe2-a701-ebc1ab6d2b5a"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


- This link is to log into OsTicket http://localhost/osTicket/scp/login.php

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- OsTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Log into OsTicket with account 
- Add Roles / Departments in OsTicket
- Create new Teams in OsTicket
- Create new Agents in OsTicket
- Give one new agent Supreme Admin Role
- Create new SLA
- Create new Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/ea9eba4d-8747-475b-a0fe-7f8c8746c4d4"

</p>
<p>
Going based off https://github.com/Jacobvillagomez1/osticket-prereqs first go to the link to log into OsTicket Browse to your help desk login page: http://localhost/osTicket/scp/login.php 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f0aa3373-8171-4e70-a7a0-f03ffb3c4091"

</p>
<p>
Next type the name of your user then the password then click log in 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/85f1a101-a84e-4c0c-81dc-0a3abce803d0"

</p>
<p>
Next click Admin panel in the top right corner 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f7c406d4-2bf8-4241-be1f-816d06385ae0"

</p>
<p>
Now click the Agents tab then click Roles 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/78fae611-8aa2-4bd2-bccd-052902401530"

</p>
<p>
Next click add new role 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/24fec6c9-b99c-47ce-bb47-f6a71ad073c9"

</p>
<p>
Now type Supreme Admin then go to the permissions tab 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/946c9b14-67c2-49ba-bf1f-c70e7353507a"

</p>
<p>
Next click all the permissions boxs for the role then click add role 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/87509fcb-83ce-43ea-9f37-f40e007ea84b"

</p>
<p>
Now go to departments in the agents tab and click Support
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/4683f829-86da-4285-8f08-455370fda710"

</p>
<p>
From the settings just make sure the type is on public and the name System Administrator then click add role at the bottom 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0358d679-825d-4e94-b908-d0f5321ba4fd"

</p>
<p>
You will then be greeted with a loading screen 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/fda5478d-e381-40e2-b0be-4c76ac6d3bec"

</p>
<p>
Next go to the department tab and click System Administrators the one we created
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/7bb44636-fba6-469f-a2a4-40a351fb9154"

</p>
<p>
Now click the Teams tab then click add new team 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c5cb637a-6e2c-460f-bffc-b4fbf1ccf528"

</p>
<p>
Next type Level 2 Support then go to the members tab 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/2474c49b-aa14-494d-838f-e2ddd73f9a61"

</p>
<p>
Next in the members tab click josh garcia then click add. Then click create team 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/02435a2b-6c64-4fe9-87bc-579984e7201b"

</p>
<p>
Now click the settings tab then go to the users section 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/47d0d6ac-72b9-4a85-b988-bf132fe3f03e"

</p>
<p>
Next make sure the registration methos is under public and then click save changes 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/371f779e-5833-44f4-9b62-e3c5a4ddab6d"

</p>
<p>
Now click the agents tab then click agents 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/166d2f69-a847-48b2-ba26-3dd54fc5cf8d"

</p>
<p>
Next click add new agent
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5b429440-3a38-4833-a8ae-eca45d7192f8"

</p>
<p>
Next for the name click Jane Doe then for the email type janedoe@osticket.com then for the username type jane doe. Finally click set password 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b0333b01-d971-4719-8651-7e477941c404"

</p>
<p>
Now uncheck the box at the top then type your password I will type Password1 for this example 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/71578846-6389-4cf9-9bdb-19820fd7afcd"

</p>
<p>
Now uncheck the bottom box as well then click set 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/737fe753-0e2f-4c4f-93eb-90380af2847e"

</p>
<p>
Next click access then for the primary department click System Administrators then click Supreme Admin then click create at the bottom 
</p>
<br />

<img src=".https://github.com/user-attachments/assets/93b5230a-5d38-4bd0-81ef-30544ef1b431"/>

</p>
<p>
Now you will see it was succesffully added 
</p>
<br />

<img src="https://github.com/user-attachments/assets/2da5e6dd-e924-4bdd-8a67-362c26e86735"/>

</p>
<p>
Next go to agents tab then agents again you will see Jane Doe was created. Then click add new agent 
</p>
<br />

<img src="https://github.com/user-attachments/assets/7c8e9c2a-a184-443a-a461-48b26275eaf7"/>

</p>
<p>
Now go to the account tab then type john doe. For the email type johndoe@osticket.com then for the username type john doe.
</p>
<br />

<img src="https://github.com/user-attachments/assets/d1ea636e-4487-4654-970f-d56c3ba56c32"/>

</p>
<p>
Next click the access tab then for the primary department click support then click view only. Click the create tab 
</p>
<br />

<img src="https://github.com/user-attachments/assets/960cc4a2-1d62-4532-8e41-bd1e18e83b5f"/>

</p>
<p>
Now go to the agents tab and you will see john doe then click add new agent 
</p>
<br />

<img src="https://github.com/user-attachments/assets/f1a22aec-2f47-483b-9c59-cc7eec2441d9"/>

</p>
<p>
Next type karen karen then for the email address type karenkaren@osticket.com. Then for the username type karenkaren 
</p>
<br />

<img src="https://github.com/user-attachments/assets/90bcbe21-7599-4d72-9732-cbc534d202d1"/>

</p>
<p>
Now go to the access tab and for the primary department click support then click view only. Then click create 
</p>
<br />

<img src="https://github.com/user-attachments/assets/56d14bf8-2a32-4ca6-9ffd-c2b118cbb4ab"/>

</p>
<p>
Next go back to the agents tab and you will see that karenkaren was created. Click add new agent 
</p>
<br />

<img src="https://github.com/user-attachments/assets/37c4844c-dcff-4df0-b570-1f7ac4b52188"/>

</p>
<p>
Type ken ken for the name section. Then for the email section type kenken@osticket.com followed by the username under kenken 
</p>
<br />

<img src="https://github.com/user-attachments/assets/5d29d525-230c-429b-8014-8a98fcd5b6dc"/>

</p>
<p>
Go to the access tab and for the primary department click support then click view only now click create 
</p>
<br />

<img src="https://github.com/user-attachments/assets/d6acbcc8-871c-4e75-8053-f912eaf2c443"/>

</p>
<p>
Click the manage tab then click SLA 
</p>
<br />

<img src="https://github.com/user-attachments/assets/d59accff-0362-4544-ad21-8a51a3445145"/>

</p>
<p>
Next click add new SLA plan 
</p>
<br />

<img src="https://github.com/user-attachments/assets/24948401-edd9-4c44-99b0-4b2953483c10"/>

</p>
<p>
Now type SEV-A and the grade period type 1. For the schedule click 24/7 then click add plan
</p>
<br />

<img src="https://github.com/user-attachments/assets/64a47579-2508-4757-bf50-148a78fe78a0"/>

</p>
<p>
Now type SEV-B and the grade period type 4. For the schedule click 24/7 then click add plan
</p>
<br />

<img src="https://github.com/user-attachments/assets/e16c87dd-b8ff-4015-8c0a-e81a0fd8550b"/>

</p>
<p>
Click SLA nad you will see SEV-A and SEV-B was created. Next click add new SLA Plan
</p>
<br />

<img src="https://github.com/user-attachments/assets/33f45f73-0989-4d4f-a0a4-0c05fab0bc55"/>

</p>
<p>
Now type SEV-C and the grade period type 8. For the schedule click Monday to Friday 8am to 5pm with US Holiday then click add plan
</p>
<br />

<img src="https://github.com/user-attachments/assets/4c3a0c4c-594a-450d-9099-87794857e83d"/>

</p>
<p>
Click SLA nad you will see SEV-A, SEV-B, and SEV-C was created. Now click help topics 
</p>
<br />

<img src="https://github.com/user-attachments/assets/047a7084-6ad5-46a3-bbdf-e8da78dc58e2"/>

</p>
<p>
Click add new help topic
</p>
<br />

<img src="https://github.com/user-attachments/assets/3e479a69-43a8-4595-ad8a-c3f9be50a6de"/>

</p>
<p>
Type Business Critical Outage then click add topic 
</p>
<br />

<img src="https://github.com/user-attachments/assets/3b263e24-ada2-47f3-95be-9bfaaff79961"/>

</p>
<p>
Click create new help topic then type Personal Computer Issues then click add topic 
</p>
<br />

<img src="https://github.com/user-attachments/assets/a8233476-6ea5-4267-ad6f-93105d4f35c1"/>

</p>
<p>
Next click new ticket options and for the priority section lcik normal and the SLA plan click SEV-C then click add topic 
</p>
<br />

<img src="https://github.com/user-attachments/assets/8e979c8a-2362-4098-82f2-2ef70e63883d"/>

</p>
<p>
Now go back to help topics menu and click Business Ciritical Outage 
</p>
<br />

<img src="https://github.com/user-attachments/assets/cb1f2566-ec64-4366-9820-d1decc7aa71e"/>

</p>
<p>
Next click new ticket options, for the department click Support. The priority section click Emergency and the SLA plan click SEV-A. Finally click save changes 
</p>
<br />

<img src="https://github.com/user-attachments/assets/03b86ff6-9909-484c-ace5-084d90ec57d3"/>

</p>
<p>
Click new ticket then click next type Equipment Request 
</p>
<br />

<img src="https://github.com/user-attachments/assets/86ae6a79-c51a-4d35-9d8c-e0a8781468d4"/>

</p>
<p>
Now click new ticket options for department click Support. Now for priority click low then for SLA plan click SEV-C. Finally click add topic 
</p>
<br />

<img src="https://github.com/user-attachments/assets/d8d7f89a-ea1b-48dd-a481-c671934c48ce"/>

</p>
<p>
Go back to help topics, you will see Equipment request was created then click add new help topics
</p>
<br />

<img src="https://github.com/user-attachments/assets/809fc8fa-2d74-4227-a367-070575f361fb"/>

</p>
<p>
Type Password Reset 
</p>
<br />

<img src="https://github.com/user-attachments/assets/d98ce7bd-fbf2-4674-b670-7a866acda5c7"/>

</p>
<p>
Next click new ticket options. For department click support next for priority click normal. For SLA plan click SEV-C then finally click add topic. Next click the link to continue the Ticket Lifecycle Examples https://github.com/Jacobvillagomez1/ticket-lifecycle
</p>
<br />
