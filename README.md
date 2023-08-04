<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Intake

We'll start by creating some tickets through the Users created during the last tutorial (Karen and Ken).

1. Go to the End User osTicket URL: http://localhost/osTicket/

2. Open a new ticket

3. Create a few tickets using the examples provided below.

Assignment and communication

1. Go to the Admin/Agent login page for osTicket: http://localhost/osTicket/scp/login.php

2. Log in as Jane Doe (jane.doe / Password1)

3. You'll notice when we log in as Jane, we are not able to see tickets. We'll have to go back and make some changes to her Agent permissions/settings.

4. Log in as your main admin account

5. The tickets are visible to the main admin account (while under the Agent panel). Let's make some changes so Jane can view the tickets.

6. Go to the Admin Panel -> Agents -> Jane Doe

7. Under the Access tab, set the Extended Access to the Support dept. Click 'Add' then set the role to Supreme Admin. Save changes.

8. Now log back in as Jane and the tickets will be visible.

9. Let's take a look at the Business Critical Outage ticket. As Jane, we can view the ticket as well as make changes, assignments and updates:
    - Change the Priority level to Emergency. Because this is a severe business impacting incident, it should be categorized accordingly. You'll notice that you can add in notes the changes made. This is so you can give reasoning and explanation for yourself or other Agents who may view the ticket in the future.
    - Assign the ticket to yourself (acting as the manager). Tickets with this type of severity level would normally be escalated up to some type of management.
    - Set the SLA Plan to SEV-A. Again, this is a severe, business impacting incedent. The ticket should be resolved ASAP.
    - Set the dept to System Administrators. Let's say that the System Administrator dept is responsible for the mobile banking platform. Therefore, that dept is best equipped for handling this type of issue.
    - Notice for each change made, there's a ticket thread that keeps a list of any changes made as well as the notes written for each change.
    - Post a reply with an update for the ticket status. This will be visible by the customer and provides a level of transparency when it comes to ticket resolution.


10. Next lets take a look at the ticket with the entire acounting dept down. This issue is High priority, due to it affecting an entire department. It's not quite as severe as a business outage. We'll have John handle this ticket. Follow the example below and make necessary changes to the ticket.

11. Lastly, lets look at the inquiry about a hardware refresh. Since this is just an inquiry, its low priorty. But we can go ahead and provide the information needed and resolve the ticket (Select 'Resolved' on the Ticket Status drop down before posting a response. The ticket will then appear under the 'Closed' section.




<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
