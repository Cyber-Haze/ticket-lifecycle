<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this tutorial we’ll exhibit the complete lifecycle of a ticket. You’ll see how tickets are managed, prioritized using SLAs, and escalated or resolved efficiently. This covers intake, assignment, triaging, and closing tickets within osTicket.
<br />

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

<h2>Intake</h2>

<p>
<img width="829" height="724" alt="image" src="https://github.com/user-attachments/assets/031f4a86-8e03-454c-8268-7219f263e8cd" />

</p>
<p>
  
The Ticket Intake step is where a user’s request (via email, web form, or portal) is captured and logged into the helpdesk system as a new ticket, containing details like issue type, user info, and priority — this is the starting point of the support process.
  
</p>
<br />

<h2>Assignment and Communication</h2>

<p>
<img width="960" height="611" alt="image" src="https://github.com/user-attachments/assets/33a12e8c-1c00-4b39-afd9-24ce7e89b069" />

</p>
<p>
  
This is where ticket assignment to a department or agent, and communication with the user begins.
  
Once the ticket gets created it will be assigned to a support department. This is where we review the info provided to identify the priority & correct department to route it to, if not, we self assign or assign it to a team member. We also set the SLA based on severity of the issue report.

NB// In some cases the user may not select the right priority however based on reviewing the issue notations and probing the customer for better understanding we can adjust the priority to match the correct SLA as the issue requires.

</p>
<br />

<p>
<img width="718" height="707" alt="image" src="https://github.com/user-attachments/assets/1bf125ce-198d-4612-b3f0-15027d52cb20" />

</p>
<p>
  
We previously observed the ticket priority as normal, SLA not set and unassigned to a team or support member.

- Agent John, after reviewing ticket, adjusted its Priority, set its SLA based on severity of the issue and transfered the ticket to the correct department for assigment and issue resolution.

</p>
<br />


<h2>Working the Issue</h2>

<p>
<img width="721" height="365" alt="Screenshot 2025-09-04 025725" src="https://github.com/user-attachments/assets/0373e483-c3b0-456e-a02e-44dd10da8a6f" />

</p>
<p>

This stage is the most crucial part of the tickets life. This is where the assigned agent works on resolving the issue and/or  provides updates to the customer along the way. 
  
</p>
<br />

<h2>Resolution</h2>

<p>
<img width="706" height="330" alt="image" src="https://github.com/user-attachments/assets/055a0abc-ac70-4feb-9d26-8ebeda6e5564" />
</p>
<p>
  
The problem is resolved, and the ticket is closed after verifying the solution with the user.
  
</p>
<br />

<H2> Key Points </H2>

<p> 
  
 <H3> SLA's ( Service Level Agreements) </H3> 
  
SLAs are critical to ensuring that tickets are resolved within an agreed-upon timeframe, depending on the severity of the issue.
This ticket required immediate action so we selected;

- Sev-A (1 hour, 24/7): This is the highest priority for critical issues, such as when the entire mobile or online banking system is down. The SLA requires a resolution within 1 hour, and the ticket is immediately escalated to the SysAdmins team for 24/7 handling.

Other System SLA's include:

- Sev-B (4 hours, 24/7): These are important but less urgent issues, like members the accounting department needing an software upgrade. The SLA ensures a 4-hour response and resolution time, still available around the clock.

- Sev-B/C (8 hours, business hours): This represents lower-priority issues, such as the Computers running slowly. The SLA guarantees a 8-hour resolution, but only within standard business hours.

By adhering to these SLAs, osTicket ensures that critical issues are dealt with immediately while balancing lower-priority tasks efficiently.

 <H3> Triaging Tickets: Identifying and/or Escalating Issues </H3> 

The example given showed how tickets are evaluated to either solve the problem directly or escalate it to a higher level of support if needed. Triaging is key to managing workflow efficiently and avoiding delays.

<H3> Solving Problems and Closing Tickets </H3> 

Lastly we showed how the problem is addressed, the solution is provided and communicated to the user, and the ticket is marked as closed once the issue is fully resolved within the SLA.

</p>

