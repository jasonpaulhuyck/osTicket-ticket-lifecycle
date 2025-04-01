<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Creating and Working Tickets</h1>

Project outlines the life cycle of a ticket from creation, to resolution. Making changes to the tickets, assigning tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication. 
<br/>
In continuation of the [osTicket: Post Installation Configuration](https://github.com/jasonpaulhuyck/osTicket-post-install-config) project.
<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Creating and Working Tickets Objectives</h2>

- Create tickets as "end user"
- Login and assign the tickets in osTicket as an "Agent"
- Close the tickets once the issue is resolved

<h2>Project Walk-through</h2>
<p align="center">
  
  Open the Web Browser, navigate to http://localhost/osTicket/ and open a New Ticket:

![image](https://github.com/user-attachments/assets/15841a42-e8b5-4a9c-ad25-3e8b7dab9c7b)

<p align="center">
Create a ticket stating that the entire mobile/online banking system is down, users are unable to access it or log in.

![image](https://github.com/user-attachments/assets/911a3f90-3508-4af0-a98a-02f2f7181de0)

<p align="center">
  
In a new window, navigate to http://localhost/osTicket/scp/login.php and login using the Agent credetials we created in the last project: JDoe/Password1

![image](https://github.com/user-attachments/assets/36072545-6d53-4223-87cd-54c0a09e1e08)


<p align="center">
Under the Tickets tab, you'll be able to see the ticket that was created by "Karen Ticketton"

![image](https://github.com/user-attachments/assets/6d63740f-0f32-4285-a1d9-2e853eb636e8)

<p align="center">
Click on the ticket to open it up and make changes to it:
  
![image](https://github.com/user-attachments/assets/33f3536b-bf9d-46e5-9029-2145492117e8)

<p align="center">
You can assign the ticket to an agent or team:

![image](https://github.com/user-attachments/assets/19d9938e-cd7c-4319-be30-f713d7ed6941)

<p align="center">
You can set the SLA (Service Level Agreement):

![image](https://github.com/user-attachments/assets/f85402f1-a1a8-4882-a336-a9622b9485a0)

<p align="center">
You can change the priority level:

![image](https://github.com/user-attachments/assets/a933192b-518c-4f35-8ef1-685047531566)

<p align="center">
You can make notes on the ticket to communicate to team members:

![image](https://github.com/user-attachments/assets/4bba9d78-ffa0-4b3f-b6e4-130211778c08)

<p align="center">
Once the ticket has been resolved, change the status to "Resolved" and the ticket will be closed:

![image](https://github.com/user-attachments/assets/bfdbe9b0-9d9b-4c5e-9977-049693e3f026)

![image](https://github.com/user-attachments/assets/3f55d7bb-6447-4a44-aa42-28cbb4abdaf7)





