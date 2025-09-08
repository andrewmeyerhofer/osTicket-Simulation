<p align="center">
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/64682542-313e-4d29-b846-fd0c2cb95e80" />
</p>

<h1>osTicket - Ticketing System Simulation</h1>
In this project, I used the open-source ticketing system osTicket to simulate the process of ticket intake and resolution that would occur in an IT helpdesk. This project helped me gain a better understanding of how ticketing software is commonly used in a helpdesk setting. The resources used and objectives of this project are listed below.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket (Open Source Ticketing System)

<h2>Operating Systems Used </h2>

- Windows 11</b> (24H2)

<h2>Simulation Objectives</h2>

- Understanding ticket intake
- Understanding how to properly assign incoming tickets
- Understanding how to communicate with the end-user
- Understanding the process of working the issue
- Understanding ticket resolution

<h2>Simulation:</h2>

<p>
<img width="1067" height="812" alt="image" src="https://github.com/user-attachments/assets/61c7c161-5025-4486-bb49-e6c34929add1" />

</p>
<p>
To start, I opened the osTicket support center page (for my helpdesk) from the perspective of an end-user. I clicked the Open a New Ticket button and pretended to be a user named Karen who claimed that the entire Online Banking portal was down. As Karen, I labeled the Help Topic as "Report a Problem," though it should have been labeled as "Business Critical Outage" (this is to simulate an end-user choosing the wrong Help Topic for their issue).
</p>
<br />

<p>
<img width="1201" height="807" alt="image" src="https://github.com/user-attachments/assets/4d670bee-f9f5-4a7f-92f2-ff8452e55af9" />

</p>
<p>
Once the ticket went through, I logged into osTicket as the Agent John. Because of the permissions I assigned in the osTicket-Setup project, John only has access to view incoming tickets. Upon logging in as John, I was imediately brought to the ticket page where Karen's ticket was the only one present. Here I could see all of the important information regarding the ticket, including the status, priority, department, SLA, due date, user information, help topic selected, and the communication thread. Since the end-user put in the ticket information themself, some things needed to be added or changed. I logged out of John's account so I could log back in as an account with edit permissions. 
</p>
<br />

<p>
<img width="1188" height="707" alt="image" src="https://github.com/user-attachments/assets/d1b38f80-1ef4-46e1-8884-6e2e32da00e0" />

</p>
<p>
I logged back into osTicket using my own account, and was greeted with the same ticket page that John had seen. I now had access to edit the ticket, so I started by determining the SLA plan. I set the SLA plan to SevA, as this issue appears to have a wide impact on business operations. 
</p>
<br />

<p>
<img width="1205" height="761" alt="image" src="https://github.com/user-attachments/assets/12acc00c-dc43-4b01-aaf0-b812ebd350a8" />

</p>
<p>
Next, I decided to change the help topic, originally put in as "Report a Problem," to "Business Critical Outage." Customers being unable to use the Online Banking portal is a significant issue, so labeling the ticket as a critical outage is important.
</p>
<br />

<p>
<img width="1170" height="557" alt="image" src="https://github.com/user-attachments/assets/b71855b4-f82a-43c2-938a-e157f461f509" />

</p>
<p>
I also decided to assign the ticket to the Online Banking team, seeing as the issue is related to the Online Banking portal. After making these changes to the ticket, I made sure everything was saved then logged out of my personal account. 
</p>
<br />

<p>
<img width="1187" height="705" alt="image" src="https://github.com/user-attachments/assets/1bd4197f-8796-4adc-996e-74360f6a7e51" />

</p>
<p>
I then logged in as Agent Jane (who was part of the Online Banking team) and was able to see the ticket with the changes I had just made. Since the ticket was assigned to Online Banking, any Agent who is not part of that team (such as John) will not be able to see the ticket. I then went a step further and had Jane assign the ticket to herself, meaning she will be the one to work it to completion. 
</p>
<br />

<p>
<img width="1172" height="752" alt="image" src="https://github.com/user-attachments/assets/56db6a2c-bbfd-43ce-bfdb-f08487729db3" />

</p>
<p>
As Jane, I clicked the reply button in the ticket thread to send an initial response to Karen. After I pressed the post reply button, this would be the point where Jane and the Online Banking team actually work the ticket and try to find a resolution. In this case, the resolution would likely involve rolling back the recent Banking portal update and contacting the vendor. Since this is a SevA ticket, it is also important to send hourly updates to the end-user and anyone involved, assuming it takes more than an hour to fix. 
</p>
<br />

<p>
<img width="1195" height="757" alt="image" src="https://github.com/user-attachments/assets/97232278-333e-4c49-b9d5-135750f51b83" />

</p>
<p>
After a resolution was found (assuming it took under and hour), I sent another message to Karen explaining the cause of the issue and how we were able to fix it. 
</p>
<br />

<p>
<img width="1217" height="592" alt="image" src="https://github.com/user-attachments/assets/ab3170d7-7ff4-454e-baa4-b2ba8663b2df" />

</p>
<p>
After posting the reply, I went to the status button and changed it from open to resolved. With that, the ticket became offically resolved and the tickets page became empty. 
</p>
<br />

<p>
<img width="1056" height="811" alt="image" src="https://github.com/user-attachments/assets/ff889ab4-88ac-4495-86d2-cb2d008a31ca" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1197" height="551" alt="image" src="https://github.com/user-attachments/assets/3b62b78a-6079-4c05-bccd-844b80fb79bd" />

</p>
<p>
Logged back in as Andrew. In this situation, it would be smart to contact Karen and ask for more specific details on the situation. 
</p>
<br />

<p>
<img width="1202" height="778" alt="image" src="https://github.com/user-attachments/assets/c52acd16-4b6d-4399-8b79-ff6f960fcf7a" />

</p>
<p>
Issue determined to only effect two people after talking to Karen. Set to SevC.
</p>
<br />

<p>
<img width="1216" height="747" alt="image" src="https://github.com/user-attachments/assets/d27acb6d-b1d6-4254-a794-393a15c21da6" />

</p>
<p>
Set status to resolved as well.
</p>
<br />

<p>
<img width="1042" height="796" alt="image" src="https://github.com/user-attachments/assets/39b1d51d-4c90-4d3a-ae96-331ea5d65f02" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1215" height="523" alt="image" src="https://github.com/user-attachments/assets/f1f3de0b-0ba5-42f6-a476-ba702d885225" />

</p>
<p>
Set to SevB and assigned to self. It would be smart to actually call the CFO to understand what happend.
</p>
<br />

<p>
<img width="1186" height="751" alt="image" src="https://github.com/user-attachments/assets/797ef4fd-fd5d-417b-8c50-991a238f27f1" />

</p>
<p>
Ticket is resolved.
</p>
<br />
